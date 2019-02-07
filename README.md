# Laboratorio3 
***Concurrent programming concepts***
======

*Laboratorio 3 ARSW*

  Integrantes:
  -------
  * Alejandro Rodriguez del Toro
  * Jonathan Cuesta Sanchez
  

  Profesor:
  -------
  ##### SAAVEDRA ORJUELA DAVID ARMANDO

*** Reporte Git Basic Concepts ***

*_Introduction to threads in JAVA:_*
------- 
Cuando cambiamos el comando, se puede ver como uno es sequencial y el otro concurrente.
La diferencia entre start() y run() se da puesto que start es un metodo que crea un nuevo hilo, y llama su metodo run, si se llama directamente al run, este se ejcutara en el hilo actual.

Run

![alt text][1]

[1]:https://github.com/JonathanCuestaSanchez/Laboratorio3/blob/master/src/images/run.PNG


Start

![alt text][2]

[2]:https://github.com/JonathanCuestaSanchez/Laboratorio3/blob/master/src/images/start.PNG



*_Part III - Discussion:_*
-------
Una buena manera de poder parar la ejecucion de los hilos, es usando metodos de syncronizacion, lo cual nos permitiria detener los hilos al momento de encontrar los valores, para ello el codigo nesecitaria implementar herramientas como  synchronized, metodos como wait() y notify(), y un variable de estado que se encargaria de respresenta si la ejecucion debe seguir.


*_Part IV - Performance Evaluation:_*
-------





