# README
Historias de usuario:
● Debo tener a mi disposición un formulario para crear proyectos. (2 Puntos)

● El proyecto debe tener un nombre, una descripción, una fecha de comienzo, una de
término y un estado. (1 Punto)

<code>rails g scaffold project name:string description:string begin_at:date final_at:date estate:string</code>

● El campo estado(state) refleja el estado actual(propuesta, en progreso, terminado).
Este estado por defecto debe ser propuesta. (1 Punto)

● Debo tener un vista donde pueda ver todos los proyectos.(2 Puntos)

● En esa vista debe poder filtrar por proyecto terminado, en progreso o agendado. (2
Puntos)

● Se debe validar la presencia de los campos nombre, descripción y estado. (1 Punto)

● El proyecto debe ser subido a heroku y se debe ingresar el link para la evaluación. (1
Punto)

Nota: se recomienda usar un tag select para las funcionalidades relacionadas
con el campo estado.

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
