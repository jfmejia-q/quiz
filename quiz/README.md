# 07 **Validador de números primos gemelos**

**Instrucción:** Crea un programa en Java que encuentre todos los pares de números primos gemelos dentro de un rango especificado por el usuario. El programa debe:

1. Solicitar al usuario dos números enteros positivos: inicio y fin del rango
2. Encontrar y mostrar todos los pares de números primos gemelos en ese rango
3. Contar cuántos pares de primos gemelos se encontraron en total

Los números primos gemelos son pares de números primos que tienen una diferencia de 2 entre ellos (como 3 y 5, 11 y 13, 17 y 19, etc.).

El programa debe incluir una función para verificar si un número es primo y otra para verificar si dos números forman un par de primos gemelos.

Ejemplo: Si el rango es de 10 a 30, el programa debe mostrar los pares (11,13), (17,19) y (29,31) si 31 está dentro del rango.

Solucion
Lo primero que hacemos es pedir al usuario dos numeros por teclado (num1), aqui inicializamos el rango y (num2) para finalizar el rango; es decir hasta donde queremos encontrar los numeros gemelos, En este paso solo colocamos el rango.

Lo segundo es inicializar una variable dependiente de rango y hacerle su respectiva operación i=1, si los primos gemelos tienen una diferencia de 2 entonces asigamos i++2
 
Lo tercero que podriamos hacer es meter toda esta operacion en un for para iniciar la variable, agregarle el paso con que va a correr y seguido le asignamos hasta donde finaliza el rango

por ultimo pedimos que nos imprima los resultados

