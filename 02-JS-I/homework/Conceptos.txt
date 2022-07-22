Conceptos de JS dirigido a chicos.

Variables: Las variables son espacios en memoria donde puedo guardar un dato, cualquiera que desee, puede ser un número, una cadena de texto, un booleano, etc. Las cuales pueden ser accesibles para usar su dato guardado.

String: Traducido como 'hilo', string, es una cadena que se usa para almacenar texto. Por ej, es correcto decir:
var nombre = 'Enzo';
var apellido = "Magurno";

Funciones: Las funciones en JS tienen la particularidad de realizar una acción, o devolver algo, las funciones se usan para reciclar código, para no escribir lo mismo varias veces, puedo crear una función, que desde su invocación, altere los datos planteados en la misma (los argumentos) son los parámetros que se expresan entre () como por ej:


function cuentaBancaria ( nombre, saldo ){
return `Hola ${nombre}, su saldo es de ${saldo}`
}
cuentaBancaria(Enzo, 500)
El return que vemos en la función, ejecuta una devolución de datos, un retorno de información.


Declaraciones (if/else): Las declaraciones son bifurcaciones de código que pueden accionar código de maneras distintas tomando un parámetro como consigna. IF(si esta consigna se cumple, ejecuta este código), ELSE(si lo anterior no se puede ejecuta este otro) Por ej:

let saldoBilletera = 200

if (saldoBilletera >= 200){
return 'Podés comprar este artículo'
}else (saldoBilletera<200){
return 'No podés comprar este artículo, trata con otro'}


Valores booleanos: Los valores booleanos se conocen con true y false, donde true es verdadero y false es falso. Se usan en, por ej:
var juegoVoley = true;
var tengoGatos = false;