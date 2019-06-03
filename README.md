### SENKU!
---

1. **REQUISITOS**
    + ***Compilador:*** Herramienta necesaria para traducir el lenguaje de programación en un programa. [compilador c++](https://www.onlinegdb.com/online_c++_compiler)

    + ***Bibliotecas o librerías:*** Son los archivos que podemos importar e incluir a nuestro programa, ya que estos archivos contienen las especificaciones de diferentes estructuras de código ya construidas y que podemos utilizar en nuestro programa.
      - <*iostream*> : *Es la librería más utilizada e importante, ya que contiene los algoritmos estándard y forma parte de las STL(Librerías Estandárd de Plantillas).*
      - <*string.h*> : *Es  una librería que contiene especificaciones y estructuras de funciones, tipos, macros, constantes y algunas operaciones de manipulado de memoria.*
    + ***Funciones:***  Herramienta del programador la cual permite automatizar tareas repetitivas y encapsular el código que utilizamos, pueden estar o no estar bajo parámetros. Estas utilizan valores para efectuar operaciones y posteriormente retornar un valor.
      - *Función ' **void** ' : Función que ejecuta las instrucciones ingresadas, pero no retorna ningún valor. Aunque, se puede utilizar la sentencia ' return; ' para finalizar la ejecución de la función.*
    + ***Condicionales:*** Son las llamadas estructuras de control, con las que definimos una serie de condiciones/circunstancias en nuestro programa para determinar las acciones que se llevarán a cabo.
      - *' **if** (condición){} : Es una estructura de control en la que podemos ingresar distintas instrucciones a ejecutar si es que se cumple la condición definida.* 
      - *' **else** : Esta estructura de control ejecuta las instrucciones ingresadas en caso de que la condición dada en if no se cumpla.*
    + ***Bucles:*** Son estructuras de control que nos permiten que permiten repetir instrucciones las veces que lo necesitemos, es muy útil porque permite realizar la misma tarea en una cantidad de líneas muy pequeña y de forma automática.
      - *' **for** : Es una estructura de control que permite ejecutar de manera repetitiva una serie de instrucciones, conociendo previamente un valor de inicio, un valor final y un tamaño de paso.*
    + ***Estructuras de datos:*** Son una herramienta que nos permite almacenar de manera ordenada una serie de valores dados dentro de una variable.
      - *' **matrices** : Es una estructura de datos conformada por filas y columnas.*
---
2. **REGLAS DEL JUEGO**
- Una vez elegido el escenario/tablero en el que jugar, se iniciará la partida moviendo estrategicamente una de las fichas al espacio que se encuentre vacío. *De manera obligada para realizar este movimiento se debe comer una ficha.*
- Para comer una ficha se debe saltar sobre ella a un espacio vacío. La ficha comida se retira del escenario/tablero.
- Solo se puede saltar sobre una ficha.
- Los saltos se realizan de forma horizontal o vertical. Por ello, no pueden realizarse saltos en diagonal.
- Para ganar la partida se debe dejar sólo una ficha en el tablero.
- Por lo tanto, se pierde la partida si nos queda más de una ficha y no se tienen más movimientos posibles.
---
3. **INSTRUCCIONES**
- Ejecutar el programa a través del compilador al que nos lleva el enlace que hay en los requisitos.
- Al ejecutarlo se mostrará el menú del juego con tres opciones a elegir, cada opción es un escenario/tablero diferente. También, hay incluida una cuarta opción por si lo que se desea es salir del programa. 
- Una vez elegido el escenario/tablero el programa solicitará la posición (fila y columna) de la ficha que deseamos mover.
- Después, nos solicitará la posción (fila y columna) a la cual queremos mover la ficha seleccionada.
- Para realizar los movimientos se deben conocer las reglas del juego, ya que si ingresamos un movimiento prohibido el programa nos indicará mediante un mensaje que volvamos a ingresar la posición.
- El objetivo es que quedé una sola ficha en el escenario/tablero.
---
~~~
4. INTEGRANTES
    - Renato
    - Renato
    - Mauricio
    - Rodrigo
