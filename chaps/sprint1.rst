.. raw:: PDF

    PageBreak

Sprint 1
--------

En esta primera instancia la daily meeting y planeación del sprint se realizará en conjunto,
ya que será la primera de las reuniones del proyecto.

Se procederá a la presentación de los participantes, discusión de los roles y sus responsabilidades, así como también,
el objetivo será dejar en claro el objetivo del proyecto y su visión en términos generales.

Planeación del Sprint
#####################

El objetivo principal en este primer sprint será trabajar sobre lo siguiente:

1. Planeación de proyecto
2. Investigación de tecnologías
3. Configuración entornos desarrollo

Para el primer item se desarrolló la presentación del proyecto, y se compartieron ideas entre los
miembros del equipo. Se dejó en claro cuál la visión del proyecto y los objetivos generales. Además,
se discutió sobre la arquitectura necesaria tanto para el backend como para el frontend.

En cuanto al segundo item, se discutieron varias posibilidades tecnológicas según las experiencias
obtenidas durante los últimos años en distntos trabajos. En resumen los miembros del equipos analizaron
las siguientes propuestas:

Backend:

* Php
* C#
* Go
* Python
* Javascript

Frontend:

* Angular
* Vue
* ReactJs

Luego de un tiempo se llegó a la conclusión de que Javascript es el lenguaje más viable debido a su versatibilidad
y facilidad de aprendizaje; así como también, ReactJs fue la librería escogida para trabajar sobre el Frontend, ya 
que está completamente orietada a Javascript, y permite establecer las mejores prácticas de reusabiildad de código.

Para los entornos de desarrollo se acordó configurar docker, una plataform para desarrolladores que permite construir, 
distribuir y correr aplicaciones sobre distintos entornos, obteniendo así la ventaja de poder desplegar el mismo código
local hacia producción sin diferencias, además de faciiltar la comunicación entre los distintos servicios
ofrecidos por el backend hacia el frontend.

Como último punto destacable de esta reunión, es que se optó por configurar CI (Continous Integration) y CD (Continous Delivery)
sobre CircleCI, y utilizar la plataforma de prueba Heroku para desplegar código en la nube.

Además se definieron los siguientes roles:

1. Javier Ocampo: Backend y Devops
2. Daniel Esquinazi: Backend y Product Owner
3. Facundo Flores: FrontEnd y Scrum Master
4. Matias Novoa: Stakeholder

Por último el resultado para el primer sprint será el siguiente:


.. figure:: pictures/sprint1/planned.png
  :scale: 250%
  :alt: Sprint Planning

.. raw:: PDF

    PageBreak
    
**Daily meeting 1**

.. class:: meeting

+---------+----------------------+------------------------------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?                                                              | Tengo algún impedimento? |
+---------+----------------------+------------------------------------------------------------------------------------+--------------------------+
| Daniel  |           -          | Investigación posibilidades de frameworks ágiles para desarrollo sobre javascript. |             -            |
|         |                      |                                                                                    |                          |
+---------+----------------------+------------------------------------------------------------------------------------+--------------------------+
| Facundo |           -          | Investigación de librerías UI compatibles para React.                              |             -            |
+---------+----------------------+------------------------------------------------------------------------------------+--------------------------+
| Javier  |           -          | Investigación de base de datos.                                                    |             -            |
|         |                      | Investigación implementación de aplicaciones javascript en docker.                 |                          |
+---------+----------------------+------------------------------------------------------------------------------------+--------------------------+



**Daily meeting 2**

.. class:: meeting

+---------+------------------------------------------------------------------------------------+--------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                                               | En qué trabajaré hoy?                            | Tengo algún impedimento? |
+---------+------------------------------------------------------------------------------------+--------------------------------------------------+--------------------------+
| Daniel  | Investigación posibilidades de frameworks ágiles para desarrollo sobre javascript. | Prueba de concepto utilizando framework express. |             -            |
+---------+------------------------------------------------------------------------------------+--------------------------------------------------+--------------------------+
| Facundo | Investigación de librerías UI compatibles para React.                              | Prueba de concepto utilizando Material UI        |             -            |
+---------+------------------------------------------------------------------------------------+--------------------------------------------------+--------------------------+
| Javier  | Investigación de base de datos.                                                    | Configuración postgresql en docker.              |             -            |
|         |                                                                                    |                                                  |                          |
|         | Investigación implementación de aplicaciones javascript en docker.                 | Configuración nodejs en docker.                  |                          |
+---------+------------------------------------------------------------------------------------+--------------------------------------------------+--------------------------+

**Daily meeting 3**

.. class:: meeting

+---------+--------------------------------------------------+----------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                             | En qué trabajaré hoy?                                    | Tengo algún impedimento? |
+---------+--------------------------------------------------+----------------------------------------------------------+--------------------------+
| Daniel  | Prueba de concepto utilizando framework express. | Prueba de concepto utilizando framework hapi.            |             -            |
+---------+--------------------------------------------------+----------------------------------------------------------+--------------------------+
| Facundo | Prueba de concepto utilizando Material UI        | Definición arquitectura FrontEnd usando redux y graphql. |   Docker para frontend   |
+---------+--------------------------------------------------+----------------------------------------------------------+--------------------------+
| Javier  | Configuración postgresql en docker.              | Configuración postgresql en docker.                      |             -            |
|         |                                                  |                                                          |                          |
|         |                                                  | Configuración nodejs en docker.                          |                          |
|         | Configuración nodejs en docker.                  |                                                          |                          |
+---------+--------------------------------------------------+----------------------------------------------------------+--------------------------+


**Daily meeting 4**

.. class:: meeting

+---------+----------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                     | En qué trabajaré hoy?                                        | Tengo algún impedimento? |
+---------+----------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Daniel  | Prueba de concepto utilizando framework hapi.            | Investigación y prueba de concepto usando Prisma y GraphCool |             -            |
+---------+----------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Facundo | Definición arquitectura FrontEnd usando redux y graphql. | Definición arquitectura FrontEnd usando redux y graphql.     |   Docker para frontend   |
+---------+----------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Javier  | Configuración postgresql en docker.                      | Investigación y prueba de concepto usando Graphile           |             -            |
|         |                                                          |                                                              |                          |
|         |                                                          | Configurar docker para frontend                              |                          |
|         | Configuración nodejs en docker.                          |                                                              |                          |
+---------+----------------------------------------------------------+--------------------------------------------------------------+--------------------------+

**Daily meeting 5**

.. class:: meeting

+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                         | En qué trabajaré hoy?                                        | Tengo algún impedimento? |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Daniel  | Investigación y prueba de concepto usando Prisma y GraphCool | Investigación y prueba de concepto usando Prisma y GraphCool |             -            |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Facundo | Definición arquitectura FrontEnd usando redux y graphql.     | Definición arquitectura FrontEnd usando redux y graphql.     |                          |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Javier  | Investigación y prueba de concepto usando Graphile           | Investigación y prueba de concepto usando Graphile           |             -            |
|         |                                                              |                                                              |                          |
|         |                                                              |                                                              |                          |
|         | Configurar docker para frontend                              |                                                              |                          |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+

**Daily meeting 6**

.. class:: meeting

+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                         | En qué trabajaré hoy?                                        | Tengo algún impedimento? |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Daniel  | Investigación y prueba de concepto usando Prisma y GraphCool | Investigación firebase para almacenamiento de estáticos.     |             -            |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Facundo | Definición arquitectura FrontEnd usando redux y graphql.     | Investigación técnicas de autenticación usando graphql y jwt |                          |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Javier  | Investigación y prueb de concepto usando Graphile            | Investigación firebase para almacenamiento de estáticos.     |             -            |
|         |                                                              |                                                              |                          |
|         |                                                              |                                                              |                          |
|         | Configurar docker para frontend                              |                                                              |                          |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+

**Daily meeting 7**

.. class:: meeting

+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                         | En qué trabajaré hoy?                                        | Tengo algún impedimento? |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Daniel  | Investigación firebase para almacenamiento de estáticos.     | Investigación autenticación desde backend con graphql.       |             -            |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Facundo | Investigación técnicas de autenticación usando graphql y jwt | Investigación técnicas de autenticación usando graphql y jwt |             -            |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+
| Javier  | Investigación firebase para almacenamiento de estáticos.     | Investigación Auth0 para graphcool.                          |             -            |
+---------+--------------------------------------------------------------+--------------------------------------------------------------+--------------------------+

**Daily meeting 8**

.. class:: meeting

+---------+--------------------------------------------------------------+--------------------------------------------------------+---------------------------------+
| Miembro | En qué trabajé ayer?                                         | En qué trabajaré hoy?                                  | Tengo algún impedimento?        |
+---------+--------------------------------------------------------------+--------------------------------------------------------+---------------------------------+
| Daniel  | Investigación autenticación desde backend con graphql.       | Investigación autenticación desde backend con graphql. | Github no está configurado aún. |
+---------+--------------------------------------------------------------+--------------------------------------------------------+---------------------------------+
| Facundo | Investigación técnicas de autenticación usando graphql y jwt | Investigación generación de código para frontend.      | Github no está configurado aún. |
|         |                                                              |                                                        |                                 |
|         |                                                              | Preparación documentos para retrospectiva.             |                                 |
|         |                                                              |                                                        |                                 |
|         |                                                              | Preparación artefactos para su revisión.               |                                 |
+---------+--------------------------------------------------------------+--------------------------------------------------------+---------------------------------+
| Javier  | Investigación Auth0 para graphcool.                          | Configuración CircleCI y Github.                       |                -                |
+---------+--------------------------------------------------------------+--------------------------------------------------------+---------------------------------+

**Daily meeting 9**

.. class:: meeting

+---------+--------------------------------------------------------------+---------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                         | En qué trabajaré hoy?                             | Tengo algún impedimento? |
+---------+--------------------------------------------------------------+---------------------------------------------------+--------------------------+
| Daniel  | Investigación autenticación desde backend con graphql.       | Implementación express y prisma.                  |                          |
|         |                                                              |                                                   |                          |
|         |                                                              | Preparación de historias de usuario.              |                          |
+---------+--------------------------------------------------------------+---------------------------------------------------+--------------------------+
| Facundo | Investigación técnicas de autenticación usando graphql y jwt | Investigación generación de código para frontend. |                          |
|         |                                                              |                                                   |                          |
|         |                                                              | Preparación documentos para retrospectiva.        |                          |
|         |                                                              |                                                   |                          |
|         |                                                              | Preparación artefactos para su revisión.          |                          |
+---------+--------------------------------------------------------------+---------------------------------------------------+--------------------------+
| Javier  | Configuración CircleCI y Github.                             | Configuración CircleCI y Github.                  |             -            |
+---------+--------------------------------------------------------------+---------------------------------------------------+--------------------------+

**Daily meeting 10**

.. class:: meeting

+---------+---------------------------------------------------+-----------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                              | En qué trabajaré hoy?                         | Tengo algún impedimento? |
+---------+---------------------------------------------------+-----------------------------------------------+--------------------------+
| Daniel  | Implementación express y prisma.                  | Implementación express y prisma.              |                          |
|         |                                                   |                                               |                          |
|         |                                                   | Preparación de historias de usuario.          |                          |
|         | Preparación de historias de usuario.              |                                               |                          |
+---------+---------------------------------------------------+-----------------------------------------------+--------------------------+
| Facundo | Investigación generación de código para frontend. | Preparación documentos para retrospectiva.    |                          |
|         |                                                   |                                               |                          |
|         |                                                   | Preparación artefactos para su revisión.      |                          |
|         | Preparación documentos para retrospectiva.        |                                               |                          |
|         |                                                   | Chequeo del sprint y preparación de reportes. |                          |
|         |                                                   |                                               |                          |
|         | Preparación artefactos para su revisión.          |                                               |                          |
+---------+---------------------------------------------------+-----------------------------------------------+--------------------------+
| Javier  | Configuración CircleCI y Github.                  | Configuración CircleCI y Github.              |             -            |
+---------+---------------------------------------------------+-----------------------------------------------+--------------------------+

Product backlog refinement
##########################

En esta reunión se refinaron las siguientes tareas:

1. Registrar usuario
    a. No estaban claros los campos obligatorios.
    b. No se sabía a dónde redirigir el usuario.

2. Ingreso al sistema
    a. Método de autenticación no estaba definido.
    b. Redirección y validación de campos fueron redefinidos.

.. raw:: PDF

    PageBreak

Sprint Review
#############

.. figure:: pictures/sprint1/burndown-chart.png
  :scale: 100%
  :alt: Burndown chart

.. figure:: pictures/sprint1/velocity.png
  :scale: 150%
  :alt: Velocity chart

Con la presencia de Matías se procedió con el siguiente calendario de actividades:

1. Explicar a Matias (Stakeholder) lo que se ha realizado y lo que quedó por hacer.
    - Resultado: Ningún inconveniente, todo pareciera ir de acuerdo a lo planeado, pero para el siguiente sprint sería bueno presentar algo que se pueda visualizar por los usuarios.
2. Discusión de los escenarios positivos y negativos durante el transcurso del sprint.
    - Resultado: En general demasiada investigación y pruebas de concepto.
3. Debate sobre lo que deberá ser entregado para el siguiente sprint.
    - Para el siguiente sprint se deberá presentar una prototipo que demuestre las bases de la interfaz de usuario, por lo tanto las Ingreso y Registro de usuario deberán ser implementadas.

**Análisis del burndown chart**

El equipo finalizó con las tareas rápidamente, tal vez esto se debió a que la mayoría de las tareas requerían esfuerzo de sólo investigación,
por lo tanto etapas como code review y quality assurance no fueron necesarias para determinar que una historia de usuario se finalizó. En teoría, 
si el equipo es capaz de continuar de esta manera indicaría que se están planeando bien las historias para cada sprint, así como también la estimación
de story points se realiza correctamente. Sin embargo, se deberá permanecer atento a los siguientes sprints, ya que los mismos traerán consigo tareas más complejas 
las cuales van a requerir de mayor esfuerzo y cooperación entre los miembros del equipo.

Sprint Retrospective
####################

.. class: retro

+---------+------------------------+----------------------------------+--------------------------------------------------------------------------------------------+--------------+
| Miembro |          Bueno         |               Malo               |                                          A mejorar                                         | Impedimentos |
+---------+------------------------+----------------------------------+--------------------------------------------------------------------------------------------+--------------+
|  Daniel | En general buen sprint |                                  |                                                                                            |              |
+---------+------------------------+----------------------------------+--------------------------------------------------------------------------------------------+--------------+
| Facundo |       Sprint sano      | Ninguna UI para el usuario final | Comunicación entre los miebros del equipo durante el refinamiento de historias de usuario. |              |
+---------+------------------------+----------------------------------+--------------------------------------------------------------------------------------------+--------------+
|  Javier |   Docker configurado   |                                  |                                                                                            |              |
+---------+------------------------+----------------------------------+--------------------------------------------------------------------------------------------+--------------+

.. raw:: PDF

    PageBreak
    
Repaso del backlog actual

.. figure:: pictures/sprint1/backlog.png
  :scale: 200%
  :alt: Backlog actualizado


**Conclusiones al finalizar la reunión:**

1. Sprint sano, una buena velocity en términos generales recordando que si bien cumplir con el 100% de lo planeado es lo ideal, es una tarea demasiado difícil que se mejora con el tiempo y transcurso del proyecto. 
2. Mejorar la comunicación entre miembros del equipo a través de revisión periódica de historias de usuario para facilitar el refinamiento, ya que llegado el día, el consumo de tiempo para aclarar dudas de implementación es demasiado grande.

.. raw:: PDF

    PageBreak