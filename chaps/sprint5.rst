.. raw:: PDF

    PageBreak

Sprint 5
--------

Planeación del Sprint
#####################

En nuestro último sprint no pudimos llegar a completar todas las tareas. Las estadísticas desde el lado de backend conlleva cierto grado 
de esfuerzo que no se logró estimar correctamente. Sin embargo estas tareas se movieron al sprint actual y es aquí donde se finalizarán.

El principal objetivo de este sprint será:

1. Completar el muestreo de estadísticas
2. Comenzar a construir las páginas para perfil de usuario y torneos públicos

El sprint anterior logró completar 35 SP en total. En este sprint reduciremos los story points para así dar lugar a algunos posibles _refactors_
en el código ya que nuestro código ha crecido considerablemente.

**Historias de usuario:** 35 SP 

Por último el resultado para el segundo sprint será el siguiente:

.. figure:: pictures/sprint5/planned.png
  :scale: 250%
  :alt: Sprint Planning

  Figura 38: Sprint planning.

**Daily meeting 1**

.. class:: meeting

+---------+-----------------------------+-----------------------------+--------------------------+
| Miembro | En qué trabajé ayer?        | En qué trabajaré hoy?       | Tengo algún impedimento? |
+---------+-----------------------------+-----------------------------+--------------------------+
| Daniel  | Ver estadisticas jugador BE | Ver estadisticas jugador BE |                          |
+---------+-----------------------------+-----------------------------+--------------------------+
| Facundo | Ver estadísticas jugador FE | Ver estadísticas jugador FE |                          |
+---------+-----------------------------+-----------------------------+--------------------------+
| Javier  | XP con Facundo              | XP con Facundo              |                          |
+---------+-----------------------------+-----------------------------+--------------------------+

**Daily meeting 2**

.. class:: meeting

+---------+-----------------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer?        | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+-----------------------------+-----------------------+--------------------------+
| Daniel  | Ver estadisticas jugador BE | Torneos publicos      |                          |
+---------+-----------------------------+-----------------------+--------------------------+
| Facundo | Ver estadísticas jugador FE | Ver resultado torneo  |                          |
+---------+-----------------------------+-----------------------+--------------------------+
| Javier  | XP con Facundo              | Endpoint usuario      |                          |
+---------+-----------------------------+-----------------------+--------------------------+

**Daily meeting 3**

.. class:: meeting

+---------+----------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+----------------------+-----------------------+--------------------------+
| Daniel  | Torneos publicos     | Torneos publicos      |                          |
+---------+----------------------+-----------------------+--------------------------+
| Facundo | Ver resultado torneo | Ver resultado torneo  |                          |
+---------+----------------------+-----------------------+--------------------------+
| Javier  | Endpoint usuario     | Endpoint usuario      |                          |
+---------+----------------------+-----------------------+--------------------------+

**Daily meeting 4**

.. class:: meeting

+---------+----------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+----------------------+-----------------------+--------------------------+
| Daniel  | Torneos publicos     | Torneos publicos      |                          |
+---------+----------------------+-----------------------+--------------------------+
| Facundo | Ver resultado torneo | Ver resultado torneo  |                          |
+---------+----------------------+-----------------------+--------------------------+
| Javier  | Endpoint usuario     | XP con Daniel         |                          |
+---------+----------------------+-----------------------+--------------------------+

**Daily meeting 5**

.. class:: meeting

+---------+----------------------+-------------------------------+---------------------------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?         | Tengo algún impedimento?                    |
+---------+----------------------+-------------------------------+---------------------------------------------+
| Daniel  | Torneos publicos     | Torneos publicos              | Se necesita realizar un refactor de torneos |
+---------+----------------------+-------------------------------+---------------------------------------------+
| Facundo | Ver resultado torneo | Pagina torneos - Estadisticas |                                             |
+---------+----------------------+-------------------------------+---------------------------------------------+
| Javier  | XP con Daniel        | XP con Daniel                 |                                             |
+---------+----------------------+-------------------------------+---------------------------------------------+

**Daily meeting 6**

.. class:: meeting

+---------+----------------------+-------------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?         | Tengo algún impedimento? |
+---------+----------------------+-------------------------------+--------------------------+
| Daniel  | Torneos publicos     | Torneos publicos              |                          |
+---------+----------------------+-------------------------------+--------------------------+
| Facundo | Ver resultado torneo | Pagina torneos - Estadisticas |                          |
+---------+----------------------+-------------------------------+--------------------------+
| Javier  | Torneos publicos     | Resultados fecha              |                          |
+---------+----------------------+-------------------------------+--------------------------+

**Daily meeting 7**

.. class:: meeting

+---------+----------------------+-------------------------------+--------------------------+
| Miembro | En qué trabajé ayer? | En qué trabajaré hoy?         | Tengo algún impedimento? |
+---------+----------------------+-------------------------------+--------------------------+
| Daniel  | Torneos publicos     | Torneos publicos              |                          |
+---------+----------------------+-------------------------------+--------------------------+
| Facundo | Ver resultado torneo | Pagina torneos - Equipos      |                          |
+---------+----------------------+-------------------------------+--------------------------+
| Javier  | Resultados fecha     | Resultados fecha              |                          |
+---------+----------------------+-------------------------------+--------------------------+

**Daily meeting 8**

.. class:: meeting

+---------+-------------------------------+----------------------------+--------------------------+
| Miembro | En qué trabajé ayer?          | En qué trabajaré hoy?      | Tengo algún impedimento? |
+---------+-------------------------------+----------------------------+--------------------------+
| Daniel  | Torneos publicos              | XP con Javier              |                          |
+---------+-------------------------------+----------------------------+--------------------------+
| Facundo | Pagina torneos - Equipos      | Pagina Perfil - FE         |                          |
+---------+-------------------------------+----------------------------+--------------------------+
| Javier  | Resultados ultima fecha BE    | Resultados ultima fecha FE |                          |
+---------+-------------------------------+----------------------------+--------------------------+

**Daily meeting 9**

.. class:: meeting

+---------+----------------------------+----------------------------+--------------------------+
| Miembro | En qué trabajé ayer?       | En qué trabajaré hoy?      | Tengo algún impedimento? |
+---------+----------------------------+----------------------------+--------------------------+
| Daniel  | XP con Javier              | XP con Javier              |                          |
+---------+----------------------------+----------------------------+--------------------------+
| Facundo | Pagina Perfil - FE         | Pagina Perfil - FE         |                          |
+---------+----------------------------+----------------------------+--------------------------+
| Javier  | Resultados ultima fecha FE | Resultados ultima fecha FE |                          |
+---------+----------------------------+----------------------------+--------------------------+

**Daily meeting 10**

.. class:: meeting

+---------+----------------------------+-----------------------+--------------------------+
| Miembro | En qué trabajé ayer?       | En qué trabajaré hoy? | Tengo algún impedimento? |
+---------+----------------------------+-----------------------+--------------------------+
| Daniel  | XP con Javier              | Refactor & QA         |                          |
+---------+----------------------------+-----------------------+--------------------------+
| Facundo | Pagina Perfil - FE         | Refactor & QA         |                          |
+---------+----------------------------+-----------------------+--------------------------+
| Javier  | Resultados ultima fecha FE | Refactor & QA         |                          |
+---------+----------------------------+-----------------------+--------------------------+


Product backlog refinement
##########################

En esta reunión se refinaron las siguientes tareas:

1. Generacion de archivos pdf y excel
2. Implementación de noticias 
3. Comentarios

.. raw:: PDF

    PageBreak

Sprint Review
#############

.. figure:: pictures/sprint5/burndown-chart.png
  :scale: 100%
  :alt: Burndown chart

  Figura 39: Burndown chart.

.. figure:: pictures/sprint5/velocity.png
  :scale: 150%
  :alt: Velocity chart

  Figura 40: Velocity chart.

Con la presencia de Matías se procedió con el siguiente calendario de actividades:

1. Explicar a Matias (Stakeholder) lo que se ha realizado y lo que quedó por hacer.
    - Resultado: Algunas dudas sobre por qué se ocupó un día completo para los refactors necesarios.
2. Discusión de los escenarios positivos y negativos durante el transcurso del sprint.
    - Notoria mejora en la calidad del software entregado.
    - El pairing entre compañeros de trabajo ayuda a entregar software de mejor calidad y entender las features que se construyen.
3. Debate sobre lo que deberá ser entregado para el siguiente sprint.
    - El módulo de noticias tendrá prioridad.
    - La lista de torneos públicas será conveniente.
    - Implementación de arquitectura para hosting de archivos estáticos.


**Análisis del burndown chart**

- Se puede observar una gran mejora debido a la división de tareas entre backend y frontend
- Todas las tareas fueron entregadas.

Sprint Retrospective
####################

.. class:: retro

+---------+-----------------------------------------------------------------+-------------------------------------------+-----------+
| Miembro | Bueno                                                           | Malo                                      | A mejorar |
+---------+-----------------------------------------------------------------+-------------------------------------------+-----------+
| Daniel  | Creo que el pairing entre compañeros beneficia mucho al equipo. |                                           |           |
+---------+-----------------------------------------------------------------+-------------------------------------------+-----------+
| Facundo | Pagina Perfil - FE                                              | Complicaciones por tech debt en el código |           |
+---------+-----------------------------------------------------------------+-------------------------------------------+-----------+
| Javier  | Todo marcha bien                                                |                                           |           |
+---------+-----------------------------------------------------------------+-------------------------------------------+-----------+

.. raw:: PDF

    PageBreak
    
Repaso del backlog actual

.. figure:: pictures/sprint5/backlog.png
  :scale: 200%
  :alt: Backlog actualizado

  Figura 41: Backlog actualizado.

**Conclusiones al finalizar la reunión:**

1. La próxima semana Javier y Daniel planearan la arquitectura para el manejo de archivos estáticos.

**Lista de issues**

No se encontraron.

.. raw:: PDF

    PageBreak