# Práctica 04. Fundamentos de Programación Básica

### Objetivos

Los objetivos de esta práctica son que el alumnado:

* Se familiarice con las herramientas de escitura y compilación de programas de ordenador sencillos.
* Sea capaz de desarrollar programas simples en C++.
* Conozca el ciclo de desarrollo de un programa de ordenador.

### Rúbrica de evaluacion de esta práctica

Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva) que se tendrán en cuenta a la hora de evaluar esta práctica:

* El alumnado ha de acreditar que es capaz de realizar programas simples en C++ similares a los que se proponen en este documento.
* El alumnado ha de acreditar conocer los conceptos expuestos en el material de referencia de esta práctica.

**Avise al profesor** al finalizar la realización de cada uno de los pasos que se indican a continuación. No inicie una nueva tarea sin haber revisado la anterior.

### Introducción

La única manera de aprender a programar es programando. Por ello, tanto en esta como en gran parte de las prácticas siguientes se persigue que el estudiante ponga en práctica los conocimientos de programación adquiridos mediante programas de complejidad incremental y que requieren de los conocimientos previos para poder ser resueltos de manera adecuada. En este sentido, se proponen ejercicios que el alumno debe desarrollar de forma individual y donde la generación de código para resolver los problemas propuestos le servirá para formularse nuevas preguntas y consolidar los conceptos adquiridos.

### Trabajo previo

1. Implemente su primer código en C++. Para ello, cree un archivo `hello_world.cc` en su máquina. El contenido del archivo es el siguiente:
```cpp
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
```
Una vez creado el archivo debe compilarlo para obtener un archivo ejecutable:
```
g++ -std=c++14 -g -Wall -o hello_world hello_world.cc
```
Esto da lugar a un ejecutable denominado `hello_world`.

Por último, puede ejecutar este programa `hello_world` tal como sigue:
```
./hello_world
```
La salida será la siguiente:
```
Hello World!
```
2. Estudie todo el material (vídeos, documentos y ejercicios) del tema [Primeros Programas](http://www.minidosis.org/#/temas/Cpp.PrimerosProgramas) del curso "Introducción a la programación en C++".
3. Lea con detenimiento el [artículo](http://www.cplusplus.com/doc/tutorial/basic_io/) sobre entrada y salida en C++.
4. Lea con detenimiento el [artículo](https://www.tutorialspoint.com/cplusplus/cpp_data_types.htm) tipos básicos en C++.


### Ejercicios 

El alumno/a escribirá programas independientes que atiendan a los siguientes enunciados:

1. Escribir un programa en C++ que calcule y muestre el coste de una carretera en función de (i) su longitud y (ii) el coste por metro. El programa solicitará al usuario únicamente la cantidad de metros de longitud que tiene la carretera, mientras que el coste por metro es un valor conocido de 1624 euros.

2. Escribir un programa en C++ que permita determinar el número de [yenes](https://en.wikipedia.org/wiki/Japanese_yen) equivalente a una cierta cantidad de euros. Para ello, el programa solicitará al usuario que indique de cuántos euros dispone. Una vez introducido la cantidad de euros, mostrará los yuanes equivalentes sabiendo que, a 16 de octubre de 2020, un yen es equivalente a 0.0081 euros de acuerdo a [Morningstar for Currency and Coinbase for Cryptocurrency](https://www.google.com/intl/en/googlefinance/disclaimer/). 

3. Escribir un programa en C++ que solicite al usuario la cantidad de monedas 1, 5, 20 y 20 céntimos así como los billetes de 5, 10, 20, 50, 100, 200 y 500 que tiene y calcule y muestre la cantidad de dinero de la que dispone. 

4. Escribir un programa en C++ que calcule y muestre la media de 3 calificaciones de alumnos de la asignatura Informática Básica. El programa solicitará al usuario la calificación de cada uno de los 3 alumnos donde cada calificación será un valor numérico entre `0.0` y `10.0`.

5. Escribir un programa en C++ que calcule el área y el perímetro de un cuadrado. El programa solicitará la longitud del lado del cuadrado y luego mostrará en pantalla un mensaje con el perímetro y el área.

La respuesta a los ejercicios planteados debe encontrarse ubicado en el repositorio personal de prácticas del alumno para su consulta por parte del profesorado de la asignatura antes de comenzar la sesión de prácticas.
