# ejercicio_clousure
0. Ejercicio Original
1. var num2 = 0;

function suma(num1) {
return function() {
return num1 + num2;
}
} 

var suma2 = suma(2);
console.log(suma2(5)); // Debería mostrar 7 de resultado

var suma12 = suma(12);
console.log(suma12(76)) // Debería mostrar 88 de resultado.

1. Eliminar la variable global var num2 = 0;
2. Se modifica parametro de function 2
3. fin
