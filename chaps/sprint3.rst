.. raw:: PDF

    PageBreak

Sprint 3
--------

Planeación del Sprint
#####################

En esta instancia los entornos de desarrollo se encuentran configurados y la capa
de autenticación está completa, por lo tanto el equipo se enfocará al desarrollo de
features sobre este sprint. Los puntos fuertes sobre este sprint serán los siguientes:

1. Administración completa de torneos.
2. Administración completa de equipos.
3. De parte del frontend, se hace necesario arquitecturar notificaciones y routing.

El backend no tiene dependencias bloqueadoras para proceder con sus tareas, por lo que 
el equipo se enfocará en el desarrollo de los servicios para procesar datos referidos a 
torneos y equipos.

Debido a que el frontend conllevará un esfuerzo y complejidad más alto durante este sprint,
Javier se encargará de la finalización de algunas tareas en la capa mencionada; mientras tanto 
revisará el código de Daniel sobre el backend. Por lo tanto Facundo se encargará al principio de preparar 
la arquitectura para notificaciones y routing con manejo de autenticación.

El sprint anterior logró completar 26 SP en total, pero el equipo se siente capaz de entregar al menos 
5 SP demás por cada miembro, por lo que el budget para historias de usuario pasaría a 41 SP, y además teniendo en cuenta,
QA y code reviews, el budget quedaría en:

**Historias de usuario:** 46 SP 
**QA:** 12 SP 
**Code Reviews:** 12 SP
**Total:** 65 SP


Por último el resultado para el segundo sprint será el siguiente:

.. figure:: pictures/sprint3/planned.png
  :scale: 250%
  :alt: Sprint Planning

Daily meeting 1
***************

+---------+---------------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer?      | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+---------------------------+-----------------------+--------------------------+
| Daniel  | Ayudar a testear login    | Lista de torneos      |                          |
+---------+---------------------------+-----------------------+--------------------------+
| Facundo | Conectar login al backend | Modificar torneos     |                          |
+---------+---------------------------+-----------------------+--------------------------+
| Javier  | Ayudar a testear login    | Notificaciones        |             -            |
+---------+---------------------------+-----------------------+--------------------------+

Daily meeting 2
***************

+---------+----------------------+-----------------------+-------------------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy? | Tengo algún impedimento?            |
+---------+----------------------+-----------------------+-------------------------------------+
| Daniel  | Lista de torneos     | Eliminar torneo       |                                     |
+---------+----------------------+-----------------------+-------------------------------------+
| Facundo | Modificar torneos    | Registro torneo       | Routing no esta listo para frontend |
+---------+----------------------+-----------------------+-------------------------------------+
| Javier  | Notificaciones       | Routing               |                  -                  |
+---------+----------------------+-----------------------+-------------------------------------+

Daily meeting 3
***************

+---------+----------------------+---------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?     | Tengo algún impedimento? |
+---------+----------------------+---------------------------+--------------------------+
| Daniel  | Eliminar torneo      | Registro equipos          |  Atraso en code reviews  |
+---------+----------------------+---------------------------+--------------------------+
| Facundo | Registro torneo      | Frontend registro torneos |                          |
|         |                      | Code review backend       |                          |
+---------+----------------------+---------------------------+--------------------------+
| Javier  | Routing              | Frontend lista de torneos |             -            |
+---------+----------------------+---------------------------+--------------------------+

Daily meeting 4
***************

+---------+---------------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer?      | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+---------------------------+-----------------------+--------------------------+
| Daniel  | Registro equipos          | Registro equipos      |                          |
+---------+---------------------------+-----------------------+--------------------------+
| Facundo | Frontend registro torneos | Frontend eliminar     |                          |
|         |                           | Code review backend   |                          |
|         | Code review backend       |                       |                          |
+---------+---------------------------+-----------------------+--------------------------+
| Javier  | Frontend lista de torneos | Frontend modificar    |             -            |
|         |                           | Code review FrontEnd  |                          |
+---------+---------------------------+-----------------------+--------------------------+

Daily meeting 5
***************

+---------+---------------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer?      | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+---------------------------+-----------------------+--------------------------+
| Daniel  | Registro equipos          | Registro equipos      |                          |
+---------+---------------------------+-----------------------+--------------------------+
| Facundo | Frontend registro torneos | Frontend eliminar     |                          |
|         |                           | Code review backend   |                          |
|         | Code review backend       |                       |                          |
+---------+---------------------------+-----------------------+--------------------------+
| Javier  | Frontend lista de torneos | Frontend modificar    |             -            |
|         |                           | Code review FrontEnd  |                          |
+---------+---------------------------+-----------------------+--------------------------+

Daily meeting 6
***************

+---------+----------------------+--------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?    | Tengo algún impedimento? |
+---------+----------------------+--------------------------+--------------------------+
| Daniel  | Registro equipos     | Modificar un equipo      |                          |
+---------+----------------------+--------------------------+--------------------------+
| Facundo | Frontend eliminar    | Lista de equipos FE y BE |                          |
|         |                      |                          |                          |
|         | Code review backend  |                          |                          |
+---------+----------------------+--------------------------+--------------------------+
| Javier  | Frontend modificar   | Registro de equipo       |             -            |
|         |                      |                          |                          |
|         | Code review FrontEnd |                          |                          |
+---------+----------------------+--------------------------+--------------------------+

Daily meeting 7
***************

+---------+--------------------------+---------------------------+--------------------------+
| Miembro | En qué trabajé ayer?     | En qué trabajaré hoy?     | Tengo algún impedimento? |
+---------+--------------------------+---------------------------+--------------------------+
| Daniel  | Modificar un equipo      | Eliminar un equipo        |                          |
+---------+--------------------------+---------------------------+--------------------------+
| Facundo | Lista de equipos FE y BE | Modificar equipo frontend |                          |
+---------+--------------------------+---------------------------+--------------------------+
| Javier  | Registro de equipo       | Registro de equipo        |             -            |
+---------+--------------------------+---------------------------+--------------------------+

Daily meeting 8
***************

+---------+---------------------------+------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?      | En qué trabajaré hoy?                    | Tengo algún impedimento? |
+---------+---------------------------+------------------------------------------+--------------------------+
| Daniel  | Eliminar un equipo        | Resolución issues - ELiminar un equipo   |                          |
+---------+---------------------------+------------------------------------------+--------------------------+
| Facundo | Modificar equipo frontend | Resolución issues encontrados en routing |                          |
+---------+---------------------------+------------------------------------------+--------------------------+
| Javier  | Registro de equipo        | Eliminar un equipo frontend              |             -            |
+---------+---------------------------+------------------------------------------+--------------------------+

Daily meeting 9
***************

+---------+------------------------------------------+-------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                     | En qué trabajaré hoy?                           | Tengo algún impedimento? |
+---------+------------------------------------------+-------------------------------------------------+--------------------------+
| Daniel  | Resolución issues - ELiminar un equipo   | Ayudar a javier a resolver issues               |                          |
|         |                                          | Aumentar coverage del backend                   |                          |
+---------+------------------------------------------+-------------------------------------------------+--------------------------+
| Facundo | Resolución issues encontrados en routing | Resolución issues encontrados en notificaciones |                          |
|         |                                          | Resolución issues UI                            |                          |
+---------+------------------------------------------+-------------------------------------------------+--------------------------+
| Javier  | Eliminar un equipo frontend              | Resolución issues                               |             -            |
+---------+------------------------------------------+-------------------------------------------------+--------------------------+

Daily meeting 10
****************

+---------+------------------------------------------+-------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                     | En qué trabajaré hoy?                     | Tengo algún impedimento? |
+---------+------------------------------------------+-------------------------------------------+--------------------------+
| Daniel  | Ayudar a javier a resolver issues        | Ayudar a javier a resolver issues         |                          |
|         |                                          | Aumentar coverage del backend             |                          |
|         | Aumentar coverage del backend            |                                           |                          |
+---------+------------------------------------------+-------------------------------------------+--------------------------+
| Facundo | Resolución issues encontrados en routing | Aumento de coverage frontend              |                          |
+---------+------------------------------------------+-------------------------------------------+--------------------------+
| Javier  | Resolución issues                        | Resolución issues encontrados en frontend |             -            |
+---------+------------------------------------------+-------------------------------------------+--------------------------+


Product backlog refinement
##########################

En esta reunión se refinaron las siguientes tareas:

1. Historias relacionadas a administración de jugadores.
2. Generación de fixture
3. Creación de partidos
4. Estadísticas

.. raw:: PDF

    PageBreak

Sprint Review
#############

.. figure:: pictures/sprint3/burndown-chart.png
  :scale: 100%
  :alt: Burndown chart

Con la presencia de Matías se procedió con el siguiente calendario de actividades:

1. Explicar a Matias (Stakeholder) lo que se ha realizado y lo que quedó por hacer.
    - Resultado: Ningún inconveniente, todo pareciera ir de acuerdo a lo planeado.
2. Discusión de los escenarios positivos y negativos durante el transcurso del sprint.
    - Demasiados issues encontrados cada vez que se liberaba código a producción. 
    - Una opción para resolver el punto anterior podría ser una prueba piloto utilizando programación extrema.
    - Además como siguiente plan será incrementar el porcentaje de cobertura de tests.
    - Plantear la posibilidad de introducir la cultura TDD al equipo.
3. Debate sobre lo que deberá ser entregado para el siguiente sprint.
    - Para el siguiente sprint se deberá presentar el módulo completo de jugadores y generación de fixture.


**Análisis del burndown chart**

Durante este sprint se puede observar que el equipo está enfocado en la entrega de historias de usuario. Sin embargo, nuevamente contamos con
días en que no se resuelven tareas, esto, como ya se ha mencionado anteriormente se debe a la rotación de funciones entre los miembros del equipo. 
Tal vez, para tener un mejor seguimiento de las tareas y su finalización, convenga dividir las historias de usuario, entre tareas específicas de
frontend y backend.

Sprint Retrospective
####################

+---------+-------------------------------------------------------------------------------------------+-----------------------------------------------------------------------+----------------------------------------------------------------------------+--------------+
| Miembro |                                           Bueno                                           |                                  Malo                                 |                                  A mejorar                                 | Impedimentos |
+---------+-------------------------------------------------------------------------------------------+-----------------------------------------------------------------------+----------------------------------------------------------------------------+--------------+
|  Daniel |                       Se finalizaron todas las historias de usuario.                      |                         Rotación de funciones.                        |                                                                            |              |
+---------+-------------------------------------------------------------------------------------------+-----------------------------------------------------------------------+----------------------------------------------------------------------------+--------------+
| Facundo |      Dos de los módulos más grandes de nuestro sistema han sido entregados con éxito.     | El hecho de cambiar de contexto constantemente retrasa el desarrollo. |                                                                            |              |
+---------+-------------------------------------------------------------------------------------------+-----------------------------------------------------------------------+----------------------------------------------------------------------------+--------------+
|  Javier | Hemos logrado finalizaron dos grandes módulos, y la base de nuestro sistema exitosamente. |                                                                       |                Comunicación entre los miembros del equipo.                 |              |
|         |                                                                                           |                                                                       |         Debido a que estamos trabajando asíncronamente deberíamos          |              |
|         |                                                                                           |                                                                       |     tratar de planificar las tareas con mayor anticipación, y cada vez     |              |
|         |                                                                                           |                                                                       | que exista una duda escribir los comentarios sobre la historia de usuario. |              |
+---------+-------------------------------------------------------------------------------------------+-----------------------------------------------------------------------+----------------------------------------------------------------------------+--------------+


.. raw:: PDF
    PageBreak
    
Repaso del backlog actual

.. figure:: pictures/sprint3/backlog.png
  :scale: 200%
  :alt: Backlog actualizado


**Conclusiones al finalizar la reunión:**

1. Sprint sano, pero se deberá mejorar la comunicación entre miembros, ¿cómo? agregando comentarios sobre dudas o mejoras en las historias de usuario.
2. En el futuro si el proyecto es exitoso, se debería poder incorporar al menos una persona encargada de QA.

**Lista de issues**

.. figure:: pictures/sprint3/issues.png
  :scale: 200%
  :alt: Backlog actualizado


.. raw:: PDF

    PageBreak