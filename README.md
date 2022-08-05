# Multiplos-de-19-en-un-intervalo

Tarea Funciones: Contar Múltiplos de 19 en Intervalo
Límite de entrega: lunes, 25 de julio de 2022, 17:00
Ficheros requeridos: multiplo19.c (Descargar)
Tipo de trabajo: Individual
Planteamiento

Escribir un programa que obtenga la cantidad de múltiplos de 19 en un intervalo dado.
El usuario ingresará los límites inferior y superior del intervalo, que se asume serán enteros. Por ejemplo si los límites que el usuario ingresa son 5 y 40, la cantidad de múltiplos de 19 en ese intervalo es 2 (19 y 38).
El programa debe verificar  si estos límites son números positivos.
Si los límites ingresados no son ambos positivos, el programa debe volver a pedir que se ingresen los límites.

Use las siguientes firmas (prototipos) de funciones para programarlas e implementar su programa:

int leerNumero(); //Para leer los limites inferior y superior del intervalo
int sonPositivos(int x, int y); //Para verificar si los limites ingresados (argumentos) son ambos positivos
int esMultiplode19(int n); //Para verificar si un número (argumento) es múltiplo de 19
void mostrarResultado(int n); //Para mostrar el mensaje con el resultado encontrado (cantidad de multiplos)
A continuación se incluyen unos ejemplos de salida del programa:

Ejemplo 1 de salida del programa

Ingrese limite inferior: 2
Ingrese limite superior: 60
Existen 3 multiplos de 19 en el intervalo
Ejemplo 2 de salida del programa

Ingrese limite inferior: 206
Ingrese limite superior: 1020
Existen 43 multiplos de 19 en el intervalo

Ejemplo 3 de salida del programa

Ingrese limite inferior: -50
Ingrese limite superior: 3520
Ingrese limite inferior: 25
Ingrese limite superior: -1200
Ingrese limite inferior: 5000
Ingrese limite superior: 10000
Existen 263 multiplos de 19 en el intervalo
