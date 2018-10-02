.. raw:: PDF

    PageBreak

Sprint 4
--------

Planeación del Sprint
#####################

Debido a que en el último sprint se encontraron varios issues durante el transcurso del mismo, estos 
días se realizará una prueba piloto: realizar programación extrema entre los miembros del equipo. Debido 
a que Javier es uno de los desarrolladores más versátiles, será el quien preste ayuda a la realización
de las tareas del backend y frontend. 

Además cabe destacar, que durante esta planificación cada una de las historias de usuario se dividirán en 
dos tareas: backend y frontend, cada una con sus correspondientes story points.

El principal objetivo de este sprint será:

1. Administración completa de jugadores.
2. Generación de fixtures
3. Creación de enfrentamientos entre equipos.
4. Estadísticas de equipos y jugadores.

El backend no tiene dependencias bloqueadoras para proceder con sus tareas, por lo que 
el equipo se enfocará en el desarrollo de los servicios para procesar datos referidos a 
jugadores y generación de fixture.

El sprint anterior logró completar 46 SP en total, pero debido a que está vez se dará prueba a la programación extrema,
reduciremos la cantidad de story points, considerando que gracias a esto se entregará software de mayor calidad 
y con mayor porcentaje de cobertura de tests.

**Historias de usuario:** 35 SP 

Por último el resultado para el segundo sprint será el siguiente:

.. figure:: pictures/sprint4/planned.png
  :scale: 250%
  :alt: Sprint Planning

**Daily meeting 1**

.. class:: meeting

+---------+-------------------------------------------+---------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                      | En qué trabajaré hoy?                 | Tengo algún impedimento? |
+---------+-------------------------------------------+---------------------------------------+--------------------------+
| Daniel  | Ayudar a javier a resolver issues         | Registrar jugadores para un equipo BE |                          |
|         | Aumentar coverage del backend             |                                       |                          |
+---------+-------------------------------------------+---------------------------------------+--------------------------+
| Facundo | Aumento de coverage frontend              | Registrar jugadores para un equipo FE |                          |
+---------+-------------------------------------------+---------------------------------------+--------------------------+
| Javier  | Resolución issues encontrados en frontend | XP con Daniel                         |                          |
+---------+-------------------------------------------+---------------------------------------+--------------------------+

**Daily meeting 2**

.. class:: meeting

+---------+---------------------------------------+-----------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                  | En qué trabajaré hoy?                               | Tengo algún impedimento? |
+---------+---------------------------------------+-----------------------------------------------------+--------------------------+
| Daniel  | Registrar jugadores para un equipo BE | Modificar información de jugador BE                 |                          |
+---------+---------------------------------------+-----------------------------------------------------+--------------------------+
| Facundo | Registrar jugadores para un equipo FE | Registrar jugadores para un equipo FE y code review |                          |
+---------+---------------------------------------+-----------------------------------------------------+--------------------------+
| Javier  | XP con Daniel                         | XP con Facundo y Code reviews                       |                          |
+---------+---------------------------------------+-----------------------------------------------------+--------------------------+

**Daily meeting 3**

.. class:: meeting

+---------+-----------------------------------------------------+--------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                | En qué trabajaré hoy?                | Tengo algún impedimento? |
+---------+-----------------------------------------------------+--------------------------------------+--------------------------+
| Daniel  | Modificar información de jugador BE                 | Modificar información de jugador BE  |                          |
+---------+-----------------------------------------------------+--------------------------------------+--------------------------+
| Facundo | Registrar jugadores para un equipo FE y code review | Modificar información de jugador FE  |                          |
|         |                                                     | code reviews                         |                          |
+---------+-----------------------------------------------------+--------------------------------------+--------------------------+
| Javier  | XP con Facundo y Code reviews                       | XP con Daniel y Code reviews         |                          |
+---------+-----------------------------------------------------+--------------------------------------+--------------------------+

**Daily meeting 4**

.. class:: meeting

+---------+-----------------------------------------------------+-------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                | En qué trabajaré hoy?         | Tengo algún impedimento? |
+---------+-----------------------------------------------------+-------------------------------+--------------------------+
| Daniel  | Modificar información de jugador BE                 | Eliminar jugador BE           |                          |
+---------+-----------------------------------------------------+-------------------------------+--------------------------+
| Facundo | Registrar jugadores para un equipo FE y code review | Eliminar jugador FE           |                          |
|         |                                                     | code reviews                  |                          |
+---------+-----------------------------------------------------+-------------------------------+--------------------------+
| Javier  | XP con Facundo y Code reviews                       | XP con Facundo y Code reviews |                          |
+---------+-----------------------------------------------------+-------------------------------+--------------------------+

**Daily meeting 5**

.. class:: meeting

+---------+-------------------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer?          | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+-------------------------------+-----------------------+--------------------------+
| Daniel  | Eliminar jugador BE           | Generar fixture BE    |                          |
+---------+-------------------------------+-----------------------+--------------------------+
| Facundo | Eliminar jugador FE           | Generar fixture FE    |                          |
|         |                               |                       |                          |
|         | code reviews                  |                       |                          |
+---------+-------------------------------+-----------------------+--------------------------+
| Javier  | XP con Facundo y Code reviews | XP con Daniel         |                          |
+---------+-------------------------------+-----------------------+--------------------------+

**Daily meeting 6**

.. class:: meeting

+---------+----------------------+-----------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?       | Tengo algún impedimento? |
+---------+----------------------+-----------------------------+--------------------------+
| Daniel  | Generar fixture BE   | Generar fixture BE          |                          |
+---------+----------------------+-----------------------------+--------------------------+
| Facundo | Generar fixture FE   | Crear game/match/partido FE |                          |
+---------+----------------------+-----------------------------+--------------------------+
| Javier  | Generar fixture FE   | XP con Daniel               |                          |
+---------+----------------------+-----------------------------+--------------------------+

**Daily meeting 7**

.. class:: meeting

+---------+----------------------+----------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?      | Tengo algún impedimento? |
+---------+----------------------+----------------------------+--------------------------+
| Daniel  | Generar fixture BE   | Generar fixture BE         |                          |
+---------+----------------------+----------------------------+--------------------------+
| Facundo | Generar fixture FE   | Ver estadísticas equipo FE |                          |
+---------+----------------------+----------------------------+--------------------------+
| Javier  | Generar fixture FE   | XP con Daniel              |                          |
+---------+----------------------+----------------------------+--------------------------+

**Daily meeting 8**

.. class:: meeting

+---------+----------------------------+-----------------------------+--------------------------+
| Miembro | En qué trabajé ayer?       | En qué trabajaré hoy?       | Tengo algún impedimento? |
+---------+----------------------------+-----------------------------+--------------------------+
| Daniel  | Generar fixture BE         | Crear game/match/partido BE |                          |
+---------+----------------------------+-----------------------------+--------------------------+
| Facundo | Ver estadísticas equipo FE | Ver estadísticas equipo FE  |                          |
+---------+----------------------------+-----------------------------+--------------------------+
| Javier  | XP con Daniel              | Ver estadísticas equipo BE  |                          |
+---------+----------------------------+-----------------------------+--------------------------+

**Daily meeting 9**

.. class:: meeting

+---------+-----------------------------+-----------------------------+--------------------------+
| Miembro | En qué trabajé ayer?        | En qué trabajaré hoy?       | Tengo algún impedimento? |
+---------+-----------------------------+-----------------------------+--------------------------+
| Daniel  | Crear game/match/partido BE | Crear game/match/partido BE |                          |
+---------+-----------------------------+-----------------------------+--------------------------+
| Facundo | Ver estadísticas equipo FE  | Ver estadísticas equipo FE  |                          |
+---------+-----------------------------+-----------------------------+--------------------------+
| Javier  | Ver estadísticas equipo BE  | Ver estadísticas equipo BE  |                          |
+---------+-----------------------------+-----------------------------+--------------------------+

**Daily meeting 10**

.. class:: meeting

+---------+-----------------------------+-----------------------------+--------------------------+
| Miembro | En qué trabajé ayer?        | En qué trabajaré hoy?       | Tengo algún impedimento? |
+---------+-----------------------------+-----------------------------+--------------------------+
| Daniel  | Crear game/match/partido BE | Ver estadísticas jugador BE |                          |
+---------+-----------------------------+-----------------------------+--------------------------+
| Facundo | Ver estadísticas equipo FE  | Ver estadísticas jugador FE |                          |
+---------+-----------------------------+-----------------------------+--------------------------+
| Javier  | Ver estadísticas equipo BE  | XP con Facundo              |                          |
+---------+-----------------------------+-----------------------------+--------------------------+


Product backlog refinement
##########################

En esta reunión se refinaron las siguientes tareas:

1. Comentarios para un partido
2. Historias relacionadas a mensajería
3. Push notifications
4. Importación y Exportación de archivos
5. Historias relacionas a noticias.

.. raw:: PDF

    PageBreak

Sprint Review
#############

.. figure:: pictures/sprint4/burndown-chart.png
  :scale: 100%
  :alt: Burndown chart

.. figure:: pictures/sprint4/velocity.png
  :scale: 150%
  :alt: Velocity chart

Con la presencia de Matías se procedió con el siguiente calendario de actividades:

1. Explicar a Matias (Stakeholder) lo que se ha realizado y lo que quedó por hacer.
    - Resultado: Satisfecho con la cantidad de features liberadas y el aumento de porcentaje de cobertura de tests.
2. Discusión de los escenarios positivos y negativos durante el transcurso del sprint.
    - Notoria mejora en la calidad del software entregado.
    - Semana siguiente disctuir la implementación de utilizar TDD, es decir programación conducida por tests.
3. Debate sobre lo que deberá ser entregado para el siguiente sprint.
    - El módulo de noticias tendrá prioridad.
    - La lista de torneos públicas será conveniente.
    - Implementación de arquitectura para hosting de archivos estáticos.


**Análisis del burndown chart**

- Se puede observar una gran mejora debido a la división de tareas entre backend y frontend
- El sprint no fue perfecto, pero se podría seguir refinando el planeamiento y estimación.
- La programación extrema fue todo un éxito, la mayoría de las tareas se entregaron a tiempo.

Sprint Retrospective
####################

.. class:: retro

+---------+--------------------------------------------------------------------------------+------+------------------------------------------------------------+----------------------------------------------+
| Miembro | Bueno                                                                          | Malo | A mejorar                                                  | Impedimentos                                 |
+---------+--------------------------------------------------------------------------------+------+------------------------------------------------------------+----------------------------------------------+
| Daniel  | Gracias a la división de tareas entre backend                                  | -    | Cuando llegamos al sprint planning deberíamos tener        | -                                            |
|         | y frontend ahoro tenemos mejor visibilidad en                                  |      | una lista de historias refinadas con story points, al      |                                              |
|         | nuestro tablero.                                                               |      | menos con un puntaje similar a la velocity que actualmente |                                              |
|         |                                                                                |      | manejamos.                                                 |                                              |
+---------+--------------------------------------------------------------------------------+------+------------------------------------------------------------+----------------------------------------------+
| Facundo | Un buen sprint. Muchas features terminadas. Notoria mejora en la comunicación. | -    | -                                                          | La sección de hosting de archivos            |
|         |                                                                                |      |                                                            | no está planeada aún, de momento no podemos  |
|         |                                                                                |      |                                                            | mostrar imágenes relevantes para el usuario. |
+---------+--------------------------------------------------------------------------------+------+------------------------------------------------------------+----------------------------------------------+
| Javier  | Buena cooperación entre los miembros del equipo.                               | -    | -                                                          | -                                            |
+---------+--------------------------------------------------------------------------------+------+------------------------------------------------------------+----------------------------------------------+

.. raw:: PDF

    PageBreak
    
Repaso del backlog actual

.. figure:: pictures/sprint4/backlog.png
  :scale: 200%
  :alt: Backlog actualizado


**Conclusiones al finalizar la reunión:**

1. La próxima semana Javier y Daniel planearan la arquitectura para el manejo de archivos estáticos.
2. La siguiente semana cada día, cada miembro dedicará 15 minutos a la refinación de tareas.
3. Facundo se encargará de tener preparada la lista de "Upcoming stories" para el siguiente sprint review.

**Lista de issues**

No se encontraron.

.. raw:: PDF

    PageBreak