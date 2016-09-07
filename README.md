# Leccion 20 - Ejercicio 2
#### INICIO
var feature = 'closures'; 
(function () {     
if ( typeof feature === 'undefined' ){         
var feature = 'callbacks';         
console.log('JS coders love its ' + feature );     
} else {         
console.log('JS developers love its ' + feature );     
} 
})();
#### FINAL
var feature = 'closures'; 
(function () {     
    if ( typeof feature === 'undefined' ){                  
        console.log('JS coders love its ' + feature );     
    } else {         
        console.log('JS developers love its ' + feature );     
    } 
})();

###### Modifique la linea : var undefined = "feature", por que feature es variable global, y undefined no esta declarada. Por eso lo eliminé.