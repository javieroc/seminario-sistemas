.. raw:: PDF

    PageBreak

Sprint 2
--------

En esta instancia se procederá con la ejecución normal del sprint.

Planeación del Sprint
#####################

Teniendo en cuenta la retrospectiva del Sprint 1, el objetivo principal para el presente sprint será:

1. Generación de UI para el usuario.
2. Desarrollar una manera para que el usuario pueda registrarse en el sistema.
3. Desarrollo de una interfaz sencilla para logeo en el sistema.
4. Finalización de las tareas para CI y CD.

Para el primer item se procedió a la discusión sobre utilización de un framework UI que permita
un prototipado rápido de interfaz. No es un requerimiento que la elección sea la final, ya que 
la UI será refinada por el usuario. Por lo tanto el framework a utilizar tendrá que ser lo suficientemente
flexible como para ser rápidamente reemplazado.

En cuanto al resto de los items, las historias de usuario ya se encuentran creadas y refinadas.

Los miembros del equipo discutieron que para la planeación de este sprint se deberá tener en cuenta
que la mayoría de las historias serán de desarrollo, y que si bien, frontend y backend pueden ser
desarrollados independientemente, en el sentido que no tienen por qué bloquearse, la estimación de los
story points se verá impactada debido a que el sprint pasado, las historias, en su mayoría eran de investigación.

Otro de los puntos a tener en cuenta, será el hecho de que la parte de QA será realizada entre los miembros del equipo,
así como también los code reviews requiren un esfuerzo. Por lo tanto si el sprint pasado tuvo una velocity de 49, se podría planificar 
el siguiente budget:

**Historias de usuario:** 25 SP 
**QA:** 12 SP 
**Code Reviews:** 12 SP
**Total:** 49 SP


Por último el resultado para el segundo sprint será el siguiente:


.. figure:: pictures/sprint2/planned.png
  :scale: 250%
  :alt: Sprint Planning

Daily meeting 1
***************

+---------+-----------------------------------------------+------------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                          | En qué trabajaré hoy?                                            | Tengo algún impedimento? |
+---------+-----------------------------------------------+------------------------------------------------------------------+--------------------------+
| Daniel  | Implementación express y prisma.              | Implementación express y prisma.                                 |                          |
|         |                                               |                                                                  |                          |
|         | Preparación de historias de usuario.          | Preparación de historias de usuario.                             |                          |
+---------+-----------------------------------------------+------------------------------------------------------------------+--------------------------+
| Facundo | Preparación documentos para retrospectiva.    | Ayudar a Javier a terminar la configuración de CircleCI y Github |                          |
|         |                                               |                                                                  |                          |
|         |                                               |                                                                  |                          |
|         | Preparación artefactos para su revisión.      |                                                                  |                          |
|         |                                               |                                                                  |                          |
|         |                                               |                                                                  |                          |
|         | Chequeo del sprint y preparación de reportes. |                                                                  |                          |
+---------+-----------------------------------------------+------------------------------------------------------------------+--------------------------+
| Javier  | Configuración CircleCI y Github.              | Configuración CircleCI y Github.                                 |             -            |
+---------+-----------------------------------------------+------------------------------------------------------------------+--------------------------+

Daily meeting 2
***************

+---------+------------------------------------------------------------------+--------------------------------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                             | En qué trabajaré hoy?                                                    | Tengo algún impedimento? |
+---------+------------------------------------------------------------------+--------------------------------------------------------------------------+--------------------------+
| Daniel  | Implementación express y prisma.                                 | Testear la implementación de CircleCi y Github                           |                          |
|         |                                                                  |                                                                          |                          |
|         | Preparación de historias de usuario.                             | Subir backend a Github y preparar PR.                                    |                          |
+---------+------------------------------------------------------------------+--------------------------------------------------------------------------+--------------------------+
| Facundo | Ayudar a Javier a terminar la configuración de CircleCI y Github | Generar la interfaz para registro de usuario.                            |                          |
+---------+------------------------------------------------------------------+--------------------------------------------------------------------------+--------------------------+
| Javier  | Configuración CircleCI y Github.                                 | Code review y pruebas sobre la implementación de express y prisma.       |             -            |
+---------+------------------------------------------------------------------+--------------------------------------------------------------------------+--------------------------+

Daily meeting 3
***************

+---------+--------------------------------------------------------------------+-----------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                                               | En qué trabajaré hoy?                         | Tengo algún impedimento? |
+---------+--------------------------------------------------------------------+-----------------------------------------------+--------------------------+
| Daniel  | Testear la implementación de CircleCi y Github                     | Implementación JWT en backend.                |                          |
|         |                                                                    |                                               |                          |
|         |                                                                    |                                               |                          |
|         | Subir backend a Github y preparar PR.                              |                                               |                          |
+---------+--------------------------------------------------------------------+-----------------------------------------------+--------------------------+
| Facundo | Generar la interfaz para registro de usuario.                      | Generar la interfaz para registro de usuario. |          Backend         |
+---------+--------------------------------------------------------------------+-----------------------------------------------+--------------------------+
| Javier  | Code review y pruebas sobre la implementación de express y prisma. | Registro de usuario                           |             -            |
+---------+--------------------------------------------------------------------+-----------------------------------------------+--------------------------+

Daily meeting 4
***************

+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                          | En qué trabajaré hoy?                  | Tengo algún impedimento? |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Daniel  | Implementación JWT en backend.                | Implementación JWT en backend.         |                          |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Facundo | Generar la interfaz para registro de usuario. | Generar interfaz login                 |          Backend         |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Javier  | Registro de usuario                           | Ayudar a Daniel con implementación JWT |             -            |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+

Daily meeting 5
***************

+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                          | En qué trabajaré hoy?                  | Tengo algún impedimento? |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Daniel  | Implementación JWT en backend.                | Code review sobre Registro de usuario. |                          |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Facundo | Generar la interfaz para registro de usuario. | Generar interfaz login                 |                          |
|         |                                               | Code review sobre JWT en backend.      |                          |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+
| Javier  | Registro de usuario                           | Code review sobre Registro de usuario. |             -            |
+---------+-----------------------------------------------+----------------------------------------+--------------------------+

Daily meeting 6
***************

+---------+----------------------------------------+--------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                   | En qué trabajaré hoy?          | Tengo algún impedimento? |
+---------+----------------------------------------+--------------------------------+--------------------------+
| Daniel  | Code review sobre Registro de usuario. | QA sobre registro de usuario   |                          |
+---------+----------------------------------------+--------------------------------+--------------------------+
| Facundo | Generar interfaz login                 | Implementación JWT en frontend |                          |
|         |                                        |                                |                          |
|         | Code review sobre JWT en backend.      |                                |                          |
+---------+----------------------------------------+--------------------------------+--------------------------+
| Javier  | Code review sobre Registro de usuario. | QA sobre registro de usuario   |             -            |
+---------+----------------------------------------+--------------------------------+--------------------------+

Daily meeting 7
***************

+---------+----------------------------------------+--------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                   | En qué trabajaré hoy?          | Tengo algún impedimento? |
+---------+----------------------------------------+--------------------------------+--------------------------+
| Daniel  | Code review sobre Registro de usuario. | Ayudar a Javier con login.     |                          |
+---------+----------------------------------------+--------------------------------+--------------------------+
| Facundo | Generar interfaz login                 | Implementación JWT en frontend |                          |
|         |                                        |                                |                          |
|         | Code review sobre JWT en backend.      | Resolución issues reportados.  |                          |
+---------+----------------------------------------+--------------------------------+--------------------------+
| Javier  | Code review sobre Registro de usuario. | Generar endpoint para login.   |             -            |
+---------+----------------------------------------+--------------------------------+--------------------------+

Daily meeting 8
***************

+---------+--------------------------------+----------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?           | En qué trabajaré hoy?                  | Tengo algún impedimento? |
+---------+--------------------------------+----------------------------------------+--------------------------+
| Daniel  | Ayudar a Javier con login.     | Code review y QA sobre JWT en FrontEnd |                          |
+---------+--------------------------------+----------------------------------------+--------------------------+
| Facundo | Implementación JWT en frontend | Resolución issues reportados.          |                          |
|         |                                |                                        |                          |
|         |                                |                                        |                          |
|         | Resolución issues reportados.  |                                        |                          |
+---------+--------------------------------+----------------------------------------+--------------------------+
| Javier  | Generar endpoint para login.   | Code review y QA sobre JWT en FrontEnd |             -            |
+---------+--------------------------------+----------------------------------------+--------------------------+

Daily meeting 9
***************

+---------+----------------------------------------+------------------------------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                   | En qué trabajaré hoy?                          | Tengo algún impedimento? |
+---------+----------------------------------------+------------------------------------------------+--------------------------+
| Daniel  | Code review y QA sobre JWT en FrontEnd | Preparar nuevas historias de usuario           |                          |
+---------+----------------------------------------+------------------------------------------------+--------------------------+
| Facundo | Resolución issues reportados.          | Code review y QA sobre endpoint login          |                          |
+---------+----------------------------------------+------------------------------------------------+--------------------------+
| Javier  | Code review y QA sobre JWT en FrontEnd | Ayudar a preparar nuevas historias de usuario. |             -            |
+---------+----------------------------------------+------------------------------------------------+--------------------------+

Daily meeting 10
****************

+---------+------------------------------------------------+---------------------------+--------------------------+
| Miembro | En qué trabajé ayer?                           | En qué trabajaré hoy?     | Tengo algún impedimento? |
+---------+------------------------------------------------+---------------------------+--------------------------+
| Daniel  | Preparar nuevas historias de usuario           | Ayudar a testear login    |                          |
+---------+------------------------------------------------+---------------------------+--------------------------+
| Facundo | Code review y QA sobre endpoint login          | Conectar login al backend |                          |
+---------+------------------------------------------------+---------------------------+--------------------------+
| Javier  | Ayudar a preparar nuevas historias de usuario. | Ayudar a testear login    |             -            |
+---------+------------------------------------------------+---------------------------+--------------------------+




Product backlog refinement
##########################

En esta reunión se refinaron las siguientes tareas:

1. Registrar / Modificar de torneo
    a. No estaban claros los campos obligatorios.
    b. No se sabía a dónde redirigir el usuario.

2. Lista de torneos
    a. No estaban claro el tipo de paginado.
    b. No se especificaron los filtros especifficamente.

.. raw:: PDF

    PageBreak

Sprint Review
#############

.. figure:: pictures/sprint2/burndown-chart.png
  :scale: 100%
  :alt: Burndown chart

Con la presencia de Matías se procedió con el siguiente calendario de actividades:

1. Explicar a Matias (Stakeholder) lo que se ha realizado y lo que quedó por hacer.
    - Resultado: Ningún inconveniente, todo pareciera ir de acuerdo a lo planeado, aunque se podrían agregar más story points.
2. Discusión de los escenarios positivos y negativos durante el transcurso del sprint.
    - Resultado: En general muchas tareas dependientes, pero con mucha programación entre pares y ayuda en la mejora de la calidad de código.
3. Debate sobre lo que deberá ser entregado para el siguiente sprint.
    - Para el siguiente sprint se deberá presentar la página de torneos y un vistazo de lo que sería el manejo de equipos.

Sprint Retrospective
####################

+---------+-----------------------------------------------+----------------+-----------+--------------+
| Miembro |                     Bueno                     |      Malo      | A mejorar | Impedimentos |
+---------+-----------------------------------------------+----------------+-----------+--------------+
|  Daniel |                  Buen sprint                  | Algunos issues |           |              |
|         |             Ayuda entre compañeros            |                |           |              |
+---------+-----------------------------------------------+----------------+-----------+--------------+
| Facundo |      Buen sprint completando lo planeado      | Algunos issues |           |              |
+---------+-----------------------------------------------+----------------+-----------+--------------+
|  Javier | Todas las tareas fueron completadas a tiempo. | Algunos issues |           |              |
+---------+-----------------------------------------------+----------------+-----------+--------------+

.. raw:: PDF

    PageBreak
    
Repaso del backlog actual

.. figure:: pictures/sprint2/backlog.png
  :scale: 200%
  :alt: Backlog actualizado


**Conclusiones al finalizar la reunión:**

1. Sprint sano, una buena velocity en términos generales aunque se podria planificar y entregar más story points.
2. Los issues reportados se encontraron y resolvieron a tiempo.

**Lista de issues**

.. figure:: pictures/sprint2/issues.png
  :scale: 200%
  :alt: Backlog actualizado


.. raw:: PDF

    PageBreak