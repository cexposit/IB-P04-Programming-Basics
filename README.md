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

1. Implemente su primer código en C++. Para ello, cree un archivo `helloworld.cpp` en su máquina. El contenido del archivo es el siguiente:
```
#include <iostream>

int main() {
    std::cout << "Hello World!";
    return 0;
}
```
Una vez creado el archivo debe compilarlo para obtener un archivo ejecutable:
```
g++ helloworld.cpp -o app
```
Esto da lugar a un ejecutable denominado `app`.

Por último, puede ejecutar este programa `app` tal como sigue:
```
./app
```

2. Visualice también [este otro](http://www.upv.es/visor/media/26c336b0-19d1-2648-be94-f0d72d9af755/c) que
introduce los conceptos de Algoritmo y Programa.

3. Estudie detenidamente el contenido de las 3 páginas [“Designing an algorithm”](https://www.bbc.co.uk/bitesize/guides/z3bq7ty/revision/1)
y estudie en ellas los conceptos de Algoritmo, Pseudocódigo, Datos de Entrada, Datos de Salida, Instrucciones y Diagramas de Flujo.

4. Para la realización de los ejercicios que aquí se proponen se utilizarán un par de lenguajes de programación visual: [Blockly](https://developers.google.com/blockly)
y [Scratch](https://scratch.mit.edu/). 
En ambos casos los algoritmos se codifican utilizando “bloques” que representan los diferentes tipos de instrucciones disponibles en cualquier lenguaje de programación: 
asignaciones, instrucciones de repetición, instrucciones condicionales, funciones, ...
En los lenguajes de programación a estas instrucciones se les denomina sentencias (*statements*).

En Blockly, una vez programado un algoritmo en el lenguaje de bloques de Blockly, es posible obtener el programa correspondiente a dicho algoritmo en 
otros lenguajes de programación: Python, JavaScript, Lua, ...
La sintaxis de JavaScript es muy similar a la de C++, el lenguaje que se utilizará en esta asignatura.
Un primer programa en [Blockly](https://developers.google.com/blockly) que imprima los cuadrados de los N primeros números naturales 
podría ser el que se muestra en [esta figura](https://raw.githubusercontent.com/fsande/IB-P03-Algorithms-Programs/master/blockly1.png).

Escriba este programa en Blockly y ejecútelo. 
Vea cómo el programa es “traducido” a diferentes lenguajes (panel de la derecha). 
Realice diferentes cambios en el programa para familiarizarse con el entorno de programación de Blockly.

5. En el caso de Blockly los programas que realice no se pueden guardar, mientras que en [Scratch](https://scratch.mit.edu/) sí es posible hacerlo. 
Comience por [crear una cuenta en Scratch](https://scratch.mit.edu/join) para poder almacenar sus proyectos. 
En cuanto tenga su cuenta, desarrolle en Scratch un programa que imprima en pantalla el doble de los N primeros números naturales. 
[Esta podría ser una solución](https://scratch.mit.edu/projects/406186813/editor/) al problema propuesto. 
Igual que en el caso anterior, realice cambios en el programa para que aprenda los fundamentos de Scratch.

6. Estudie [este documento](https://www.futurelearn.com/courses/block-to-text-based-programming/0/steps/39492). 
En él se insiste en la idea de pseudocódigo y se muestra la solución al famoso problema [FizzBuzz](https://en.wikipedia.org/wiki/Fizz_buzz)
tanto en Scratch como en pseudocódigo.

### Ejercicios 

El alumno/a escribirá programas independientes que atiendan a los siguientes enunciados:

1. Escribir un programa en C++ que calcule y muestre el coste de una carretera en función de (i) su longitud y (ii) el coste por metro. El programa solicitará al usuario únicamente la cantidad de metros de longitud que tiene la carretera, mientras que el coste por metro es un valor conocido de 1624 euros.

2. Escribir un programa en C++ que permita determinar el número de [yenes](https://en.wikipedia.org/wiki/Japanese_yen) equivalente a una cierta cantidad de euros. Para ello, el programa solicitará al usuario que indique de cuántos euros dispone. Una vez introducido la cantidad de euros, mostrará los yuanes equivalentes sabiendo que, a 16 de octubre de 2020, un yen es equivalente a 0.0081 euros de acuerdo a [Morningstar for Currency and Coinbase for Cryptocurrency](https://www.google.com/intl/en/googlefinance/disclaimer/). 

3. Escribir un programa en C++ que solicite al usuario la cantidad de monedas 1, 5, 20 y 20 céntimos así como los billetes de 5, 10, 20, 50, 100, 200 y 500 que tiene y calcule y muestre la cantidad de dinero de la que dispone. 

4. Escribir un programa en C++ que calcule y muestre la media de 3 calificaciones de alumnos de la asignatura Informática Básica. El programa solicitará al usuario la calificación de cada uno de los 3 alumnos donde cada calificación será un valor numérico entre `0.0` y `10.0`.

5. Escribir un programa en C++ que calcule el área y el perímetro de un cuadrado. El programa solicitará la longitud del lado del cuadrado y luego mostrará en pantalla un mensaje con el perímetro y el área.

### Referencias

[Initiation to Algorithmics with
Scratch](https://drive.google.com/file/d/1DIU-bqgAurT-F9Ltnlam9QYWaZVeLlRJ/view?usp=sharing) Benoit Gaudou.



