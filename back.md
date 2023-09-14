# BACK-END

## BASE DE DATOS (Sin utilizar)

 TABLA PREGUNTAS
 - id
 - description , string(255)
 - respuestas, string(255): Las IDS de las respuestas
 - respuesta_correcta, tinyInt(10) 

 TABLA RESPUESTAS
 - ID
 - description, string(255)

## LOGICA CON BASE DE DATOS

 1. Traigo los datos de la DB a PHP mediante queries
 2. Proceso los datos de tal manera que me quede esto:
    - pregunta: descripción de pregunta
    - respuestas: Las IDS y Descripcion de las dos respuestas incorrectas
    - respuesta_correcta: La ID y descripcion de la respuesta correcta
 3. Muestro los datos en PHP

## SEGUNDA PARTE DE LOGICA CON BASE DE DATOS

    A desarrollar...

## MEJORAS BACK

 - La pregunta actual va a tener solamente un correcto, hacer
    que tenga dos respuestas posibles si es necesario


## PLANIFICACION DE SPRINT (SCRUM)
    La duración del sprint es de 5 dias habiles (1 semana)

### Hito 1

 - Sprint 1: 
    - Back: Creación de Base de Datos,
            queries MySQL, lógica inicial
    - Front: Creación de código HTML

### Hito 2

 - Sprint 2: 
    - Back: Lógica adicional
    - Front: Creación de código CSS y JS, siendo estos los estilos
            y dinamismo de la página. 


