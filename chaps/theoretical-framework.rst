Marco Teórico
--------------

Metodologías ágiles
###################

El movimiento ágil busca alternativas al manejo de proyectos tradicional. Los enfoques ágiles ayudan a los equipos a responder a la impredecibilidad a través de un trabajo incremental e iterativo y un feedback empírico, es decir a través de corrección de fallos. Además, se proponen alternativas al desarrollo en cascada y secuencias tradicionales de desarrollo.

¿Por qué elegirlas? Proveen oportunidades para evaluar la dirección de un proyecto a través del desarrollo de su ciclo de vida. Esto se logra a través de un trabajo regular, conocido como iteración, donde al final, cada equipo, deberá presentar un producto potencialmente entregable. A través de repeticiones breves de ciclos de vida, así como tambien de productos funcionales, la metodología ágil se describe como iterativa e incremental. En los desarrollos en cascada, los equipos tienen una única chance de conseguir un aspecto de proyecto correcto, mientras que en el paradigma ágil, cada aspecto de desarrollo, requerimientos, diseño, etc., es contínuamente revisado a través del ciclo de vida. Cuando un equipo se para y re-evalúa la dirección de un proyecto cada dos semanas, siempre hay tiempo para encaminarse en otra dirección [2].

Scrum
#####

Es el camino más popular de introducción a la "Agilidad" debido a su simplicidad y flexibilidad. Debido a su popularidad, muchas organizaciones dicen "hacer Scrum" pero no están siquiera cerca a la definición actual de Scrum. Scrum hace énfasis en el feedback empírico, los equipos se autogestionan y esfuerzan para construir productos debidamente probados con pequeñas iteraciones.

Se considera a Scrum un framework para el desarrollo incremental de productos, utilizando equipos interfuncionales y auto-organizados. Provee una estructura de roles, meetings, reglas y artefactos, donde los equipos son los responsables de crear y adaptar sus procesos dentro de este framework.

Por otro lado, Scrum utiliza iteraciones de longitud fija: Sprints. Los Sprints no son mayores a 30 días, preferentemente menores. Los equipos de Scrum tratan de construir un incrementos de producto (apropiadamente probado) por cada Sprint [3].

Scrum vs Cascada
****************

El enfoque incremental e iterativo cambia las fases de desarrollo tradicional del modelo cascada por la habilidad de desarrollar un conjunto de características de alto valor incorporando feedback lo más pronto posible. (Scrum Reference Card - Michael James)

.. figure:: pictures/cascada.png
  :scale: 75%
  :alt: cascada

  Modelo en cascada tradicional.
  Depende de un entendimiento perfecto de los requerimientos del producto para minimizar el número de errores en cada fase.

.. figure:: pictures/scrumiteration.png
  :scale: 75%
  :alt: scrum

  Modelo de iteraciones en Scrum.
  Une todas las etapas de desarrollo en cada iteración, adaptandolas al descubrimiento de realidades en intervalos fijos. (Scrum Reference Card - Michael James)

Las principales desventajas del modelo en cascada son: la inflexibilidad del proyectos en las distintas etapas del mismo, tener que establecer compromisos con el cliente en una etapa temprana, y se dejan los problemas que surgen en la etapa de desarrollo para más adelante.
El beneficio más grande de Scrum es para trabajos complejos que conlleven creación de conocimiento y colaboración, tales como el desarrollo de un neuvo producto. Generalmente es asociado con el desarrollo de software orientado a objetos [3].

Características de un equipo Scrum
**********************************

* Interfuncional: existen miembros de distintas disciplinas: analista de negocios, diseñadores, expertos del dominio, etc.
* Auto-organizado / auto-gestionado.
* Se planea un Sprint a la vez con el Product Owner.
* Posee autonomía de acuerdo a cómo desarrollar cada incremento.
* Intensamente colaborativo.
* Muy exitoso cuando todo el equipo se encuentra en la misma sala, particularmente para los primeros Sprints.
* Muy exitoso a largo plazo cuando existe permanencia de los miembros a largo plazo.
* De 3 a 9 miembros.
* Tiene un rol de liderazgo [3].

Roles
#####

**Product Owner**

Es el responsable de hacer uso del "Product Backlog" para asegurar las características funcionales más valuables son producidas primero; esto se consigue priorizando el Product Backlog para encolar los requerimientos más valiosos para la siguiente iteración.

**Equipo**

Responsable de desarrollar la funcionalidad. Los equipos generalmente son auto-gestionados, auto-organizados, e interdisciplinarios, y además son responsables de darse cuenta de como tornar el Product Backlog en incrementos de funcionalidad dentro de una iteración y manejar su propio trabajo para llevarlo a cabo.

Los miembros del equipo colectivamente responsables del éxito de cada iteración y del proyecto como un todo.

**Scrum Master**

Es responsable de que el proceso Scrum se lleve a cabo con éxito, de enseñar Scrum a cada persona involucrada en el proyecto, e implementar Scrum de tal modo que encaje dentro de la cultura organizacional asegurando que todos sigan las reglas y prácticas de Scrum [1].

Artefactos
##########

**Product Backlog**

Los requerimientos para el sistema o el producto siendo desarrollados por el proyecto son listados en Product Backlog. El Product Owner es el responsable de los contenidos, priorización y disponibilidad del Product Backlog. Éste último nunca se completa, y es utilizado en el plan del proyecto como una estimación inicial de los requerimientos. El Product Backlog evoluciona con el producto y el entorno en el cual se desarrolla. Es dinámico, manejando constántemente los cambios identificando qué necesidades debe satisfacer el producto. Mientras el producto exista, el Product Backlog también lo hará.

**Product Backlog Item**

Describe el qué más que el cómo de un feature centrado en el cliente. Generalmente son escritos como Historias de Usuario, a veces poseyendo un item de criterio de aceptación.

**Sprint Backlog**

Define el trabajo, o tareas, que el Equipo debe desarrollar durante un Sprint en particular. El equipo compila una lista inicial de estas tareas en la segunda parte del Sprint Planning Meeting. Las tareas deben ser divididas de tal forma que puedan ser finalizadas entre 4 y 16 horas. Las tareas que duran más de 16 horas son consideradas como no apropiadamente bien definidas. Sólo el Equipo puede cambiar el Sprint Backlog, y el mismo debe estar ubicado de una manera altamente visible para todo el equipo. Una vez que la tarea es definida, el número de horas restante estimado para completar la tarea se ubica en la intersección de la tarea y el día del Sprint que la persona está trabajando.

**Incremento**

Comprende las funcionalidades completadas durante los sprints y liberados cada vez que el Product Owner lo desee. Luego, son inspeccionados durante los Sprint Review Meetings.

**Sprint Burndown Chart**

Se caracteriza por mostrar la suma total de trabajo realizado dentro de cada Sprint, el mismo debe ser actualizado diariamente. Su fin, es facilitar la auto-organización. El Scrum Master debería discontinuar su uso, si el mismo se vuelve un impedimento para la auto-organización del equipo.

**Product / Release Burndown Chart**

Realiza un "tracking" de las tareas faltantes en el Product Backlog para el siguiente Sprint [1].

Taiga
######

Una plataforma para administración de proyectos ágiles, libre y greatuita.

Características:

* Potente
* Simple e intuitiva
* Buen diseño
* Personalizable

Permite una buena integración con la metodología SCRUM, proponiendo una única experiencia para el Project Manager y los Desarrolladores.
La plataforma estará integrada con tareas que se relacionarán directamente con una plataforma de versionado de código Github.

.. figure:: pictures/taiga.jpg
  :scale: 100%
  :alt: taiga

Arquitectura N-Tier
###################

En ingeniería de software, una arquitectura multi-tier o n-tier, es una arquitectura tipo cliente-servidor en la cual, la capa de presentación, el procesamiento de la aplicación y el manejo de los datos son procesos lógicamente separados. Por ejemplo, una aplicación que utiliza un middleware sobre un servicio de datos entre un usuario y una base de datos, emplea una arquitectura n-tier.

* Capa de presentación: El nivel más alto de la aplicación es la interfaz de usuario. Su principal función es traducir las tareas y resultados en algo que el usuario pueda entender.
* Capa de lógica: Esta capa coordina la aplicación, procesa comandos, toma decisiones de lógica y evaluaciones, y realiza cálculos. Además mueve y procesa los datos entre las dos capas que la rodean.
* Capa de datos: Es aquí donde se almacena la información y es adquirida a partir de una base de datos o sistema de archivos. La información, luego, es enviada de vuelta a la capa lógica para su procesamiento, y eventualmente devuelta al usuario.

En este proyecto se desarrolla software para distintas plataformas, web y mobile, la mejor manera para llevar a cabo esto es utilizar una arquitectura
de microservicios. De esta forma las aplicaciones se conciben como un conjunto de pequeños servicios que se comunican entre sí mediante mecanismos
ligeros como HTTP. Siguiendo estos conceptos, construiremos una API que nos permita acceder a los recursos (elementos de información) utilizando el lenguaje de
consulta GraphQL y dos aplicaciones que consuman dicha API, un cliente web y otro mobile.

GraphQL como se mencionó antes, es un lenguaje de consulta para APIs, que nos provee una forma de acceder a los datos que da el poder a los clientes (Web, Mobile)
de requerir lo que necesitan y obtener exactamente los datos que solicitaron. A diferencia del enfoque REST, GraphQL se organiza en terminos de types y fields, no endpoints.

.. figure:: pictures/arquitectura.jpg
  :scale: 140%
  :alt: arquitectura

Para poder aplicar este tipo de arquitectura utilizaremos las tecnologías más conocidas y utilizadas en el mundo del desarrollo de software y sistemas web y mobile.
A continuación haremos referencia las herramientas que serán utilizadas en cada capa:

* Capa de presentación: En lo que corresponde a la aplicación web, Javascript + ReactJS + Redux + GraphQL. Por otro lado, en la parte mobile: Android + Java + GraphQL.
* Capa lógica: Node.JS + TypeORM + Apollo GraphQL.
* Capa de datos: PostgreSQL.

Seguidamente haremos una breve descripción de cada herramienta.

**Lenguajes**

* Typescript: Un lenguaje que compila a Javascript de manera simple y elegante, pudiendo correr en cualquier Navegador web, Node.js, y cualquier motor que soporte ECMAScript 3 en adelante. Nos ofrece además potentes herramientas para aplicaciones a gran escala, permitiéndonos un desarrollo productivo a través de chequeo estático y refactorización de código cuando nos basamos en entornos Javascript.
* Java: lenguaje orientado a objetos utilizado por defecto para el desarrollo en Android.

**Front End**

* React: Nos permite escribis código simple, rápido y de calidad, añadiendo soporte para tipos de datos aprovechando los ecosistemas de Javascript y OCaml.
* Redux: Es un contenedor de estados predecible para aplicaciones Javascript. Ayuda a escribir aplicaciones que se comporten de manera consistente, corriendo en distintos entornos (cliente, servidor y nativos).
* Apollo: Brinda una API para acceder a GraphQL de manera universal.

**Back End**

* Node.js: entorno de ejecución para Javascript construido sobre el motor v8 de Chrome. Es orientado a eventos y nos permitirá ejecutar Javascript en el servidor [6].
* TypeORM: es un ORM (Object Relational Mapping) que se integra bien con Node.js y usa Typescript. Nos ayudará a interactuar con nuestra base de datos [7].
* Apollo GraphQL: es una librería que nos ayuda a conectar los esquemas de GraphQL con un servidor HTTP Node [8].

**Datos**

* PostgreSQL: Un potente motor de bases de datos relacionales open source [9].
