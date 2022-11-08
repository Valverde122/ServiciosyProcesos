# ServiciosyProcesos
Hito de servicios y procesos, gestor de exámenes con salida automática y aleatoria 



Desarrollada una aplicación Java que simula un gestor de exámenes tipo test multihilo. 

Una clase con capacidad de multitarea hará de generador de exámenes asignando a cada examen un código. Cada código de examen generado se añadirá a una colección tipo cola.

Otra clase con capacidad de multitarea hará de consumidor de exámenes extrayendo un examen de la cola para que un alumno pueda examinarse.

El consumidor y el generador de exámenes compartirán un recurso (la cola de exámenes).

Desde el programa principal se crearán varias instancias de las clases consumidor y generadora de exámenes para simular el gestor de exámenes donde muchos alumnos podrán examinarse simultáneamente.

Y despues una segunda parte en la que las respuestas saldran por consola.
