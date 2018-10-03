.. raw:: PDF

    PageBreak

Conclusiones
------------

Scrum es una metodología de desarrollo bastante flexible, nos ha permitido tener visibilidad 
en las tareas entre todos  los  miembros del equipo. Además la flexbilidad ofrecida por el entorno
de trabajo para ser resiliente a los cambios es bastante alta. Algunas de las ventajas que 
hermos podido observar acerca de esta metodología son:

1- Las entregas regulares permiten una gestión temprana sobre las expectativas del cliente. Esto se debe a que cada uno de los incrementos son tangibles tanto para el equipo como para el cliente.

2- Flexibilidad para la adaptación de cambios en el mercado.

3- Existe mitigación de riesgos en cada uno de los sprints de manera sistemática.

4- El equipo es más productivo al ver los resultados tempranamente.

5- Un gran alineamiento entre cliente y equipo de desarollo.

Sin embargo, el principal inconveniente que se tuvo durante la ejecución de la metodología
fue el hecho que, al utilizar una herramienta libre y no tan madura como Taiga, los reportes
y/o artefactos por parte de Scrum, son difíciles de visualizar, por tanto se tuvo que recurrir
a herramientas externas como ser hojas de cálculo para el trazado de gráficas. Además, algunos
inconvenientes encontrados para un correcto seguimiento de las tareas:

1- Dificultad para establecer dependencias entre tareas.

2- No se cuenta con vinculación o manera de incorporar issues dentro del sprint.

3- No existe la posibilidad de crear épicas, las cuales son interesantes cuando una feature o bien una "deuda técnica" son demasiado grandes y necesitan varias historias para poder completar el objetivo deseado.

4- No existe una manera de definir prioridades.

5- Una opción importante como el siguimiento de quién es la persona haciendo QA sobre una tarea, está ausente.

6- Sería conveniente poder vincular las historias entregadas a una versión de Release.

Otros de los puntos a tener en cuenta es el hecho de que el equipo trabajó distribuidamente.
Muchas empresas están en contra de este tipo de cultura debido a que conlleva mayor esfuerzo
de comunicación. Desde nuestro punto de vista, el trabajo remoto es completamente viable utilizando
una framework como Scrum, debido a que cada miembro del equipo tiene asignada una tarea a realizar 
en todo momento, y en el caso que se haya subestimado la cantidad de story points para el sprint,
el miembro que no tenga tarea asignada puede tomar nuevas tareas desde el backlog, que normalmente 
gracias a las sesiones de refinamiento, se encuentran listas para ser ejecutadas. Como punto a tener 
en cuenta y que se considera importante para el éxito del proyecto, es que para facilitar la puesta 
en marcha, el equipo debería reunirse en las primeras etapas de planificación de proyecto, debido a que
aún  el mercado IT no cuenta con herramientas apropiadas para el manejo de pizarras (aunque hay algunas 
pero con costo elevado).

Creemos que Scrum es un perfecto entorno que promueve el trabajo y colaboración entre miembros/equipos 
remotos para la ejecución desde medianos a grandes proyectos.

.. raw:: PDF

    PageBreak

Propuestas a futuro
-------------------

Como se ha mencionado anteriormente, la utilización de las herramientas apropiadas para la ejecución
de Scrum es muy necesario. Una propuesta a través de la experiencia laboral entre los miembros del 
equipo es la utilización de Jira, una herramienta para la administración de proyectos ofrecida por 
Atlassian. A continuación se enumerarán una serie de ventajas encontradas:

1. Solución a todos los puntos débiles encontrados sobre Taiga, y mencionados en la sección anterior.
2. Los reportes son más variados, se cuenta con acceso a los siguientes diagramas:

a. Burndown chart: Para el seguimiento del trabajo restante sobre el proyecto para
cumplir con los objetivos del sprint.

.. figure:: pictures/conclusiones/burndown.png
  :scale: 200%
  :alt: Burndown chart

  Figura 42: Burndown chart.

b. Sprint report: Para el entendimiento del trabajo completado y no completado, como así también
posibles cambios en los story points, y algo muy interesante: tareas que se completaron y no fueron
planificadas al inicio del sprint.

.. figure:: pictures/conclusiones/sprint-report.png
  :scale: 200%
  :alt: Sprint Report

  Figura 43: Sprint Report.

c. Velocity chart: Un gráfico para la visualización del trabajo completado entre sprints, lo que se 
planeó vs lo que se completó, lo cual es muy valioso para poder planificar y estimar los siguientes
sprints.

.. figure:: pictures/conclusiones/velocity.png
  :scale: 200%
  :alt: Velocity Chart

  Figura 44: Velocity chart.

d. Control chart: Muestra el ciclo de vida para el producto, versión o sprint. Utilizado normalmente
para incrementar la performance del equipo.

.. figure:: pictures/conclusiones/control-chart.png
  :scale: 200%
  :alt: Control Chart

  Figura 45: Control chart.

Además Jira cuenta con ayuda y soporte para el uso adecuado de las herramientas mencionadas anteriormente. 

Uno de los puntos en contra de esta solución, es que es paga y no libre, pero algo a tener en cuenta 
cuando el proyecto y/o equipo comiencen a escalar.

.. figure:: pictures/conclusiones/precios.png
  :scale: 80%
  :alt: Precios en jira

  Figura 46: Precios en Jira.

El equipo comenzó a pensar en la contratación de QA, tanto para la realización de tests manuales,
como para la mejora e implementación de tests automatizados. Esto, significará un costo significativo
para el proyecto, pero a su vez significará una mejora considerable en la liberación de features,
incrementando el rendimiento del equipo, debido a que los integrantes podrán liberar features con 
mayor confiabilidad. 
