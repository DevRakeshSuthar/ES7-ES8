# ES7-ES8

## String.prototype.padStart/padEnd

     const string = '12345' ;
     
     console.log(string.padStart(10,'.'));
     console.log(string.padEnd(10,'.'));


## Object.values

    const public = {
                       name : "arrve",
                       age : 23 ,
                       hobby : [ 'cricket ', 'TV']
                    }
                    
    console.log(Object.values(public))   // [ 'arrve ' , 23 , ['cricket ', 'TV']]

## Object.entries
      const public = {
                       name : "arrve",
                       age : 23 ,
                       hobby : [ 'cricket ', 'TV']
                    }
                    
    console.log(Object.entries(public))   // [ ['name' , 'arrve '] , ['age' , 23 ] ,[hobby  , ['cricket ', 'TV']] ]
  
## Async functions

 -    visit repo currency converter 

## Exponentiation
    
     console.log( Math.pow(2 ,3);
     console.log( 2 ** 3);
     
## Trailling Commas

     const object = { name : 'aarvee' , age : 89 , } or { name : 'aarvee' , age : 89  }
     const array = [ 'aarvee' , 89 , ] or [ 'aarvee' ,  89  ]
     const array = ['aarvee',  ,  , 89  ]   // array.length = 4 
