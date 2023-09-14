BASE DE DATOS

 TABLA PREGUNTAS
 - id
 - description , string(255)
 - respuestas, string(255): Las IDS de las respuestas
 - respuesta_correcta, tinyInt(10) 

 TABLA RESPUESTAS
 - ID
 - description, string(255)

 LOGICA

 1. Traigo los datos de la DB a PHP mediante queries
 2. Proceso los datos de tal manera que me quede esto:
   $pregunta: descripción de pregunta
   $respuestas: Las IDS y Descripcion de las dos respuestas incorrectas
   $respuesta_correcta: La ID y descripcion de la respuesta correcta
 3. Muestro los datos en PHP

 SEGUNDA PARTE DE LOGICA
 1. 

MEJORAS BACK

 - La pregunta actual va a tener solamente un correcto, hacer
    que tenga dos respuestas posibles si es necesario
    ...........


Planificacion Sprint (SCRUM)
 - Sprint: 5 dias habiles
 - Hito 1:
Sprint 1: 
    - Back: Cracion de Base de Datos
            Queries MySQL
    - Front: Creacion de codigo HTML

Sprint 2: 
    - Back: Logica de la trivia
    - Front: Creacion de codigo CSS y JS


