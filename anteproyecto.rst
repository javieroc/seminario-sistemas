============
Anteproyecto
============

.. raw:: PDF

    PageBreak

.. contents:: Tabla de contenidos
    :depth: 3

.. raw:: PDF

    PageBreak

Introducción
------------

El presente proyecto titulado *Sistemas de administración de torneos* surge como respuesta
a la necesidad de los organizadores de eventos deportivos, para agilizar la gestión de torneos y equipos. Además la presente propuesta ayudará a la difusión de torneos por redes sociales, inscripción de los equipos

Objetivos
---------

Objetivos generales
###################

* Implementar un servicio utilizando la metodología de desarrollo de software ágil SCRUM.
* Ganar experiencia en la administración y desarrollo de proyectos informáticos.
* Fomentar el aprendizaje de las tecnologías más utilizadas en el mercado actual para enriquecer las habilidades profesionales de cada integrante del equipo.
* Desarrollar un software de calidad.
* Iniciar un emprendimiento local con la posibilidad de expandirnos dentro de la industria del software.

Objetivos Específicos
#####################
* Permitir el acceso a una aplicación disponible sobre plataformas web y mobile.
* Diseñar una interfaz cómoda y accesible para los distintos usuarios.
* Utilizar los métodos de autenticación más populares del mercado, para así abarcar mayor rango de usuarios.
* Facilitar la inscripción y seguimiento de los equipos que participan en los torneos.
* Dejar en disposición la personalización de distintos tipos de sistemas de eliminatorias para cada torneo.
* Permitir la visualiación de información estadística desde distintos dispositivos.
* Posibilitar el cobro de inscripciones de equipos a torneos.

Sistema Objeto
--------------

El sistema consistirá de dos interfaces, de una mobile y otra web. Se permitirá a los usuarios gestionar torneos, equipos y jugadores;
además se contemplará la generación y presentación de estadísticas y reportes. Por otro lado, y no por ello menos importante, se considera
la administración de fixtures. A continuación se describirá las características principales de cada módulo:

Gestión de usuarios
###################

Nuestro sistema incluirá los siguientes tipos (roles) de usuarios:

* Organizador: Posee los más altos privilegios sobre el sistema, pudiendo acceder a todas las secciones con la posibilidad de editar cualquier información. Serán los encargados de gestionar torneos, registrar equipos y jugadores.
* Delegado: Podrá cargar datos pertenecientes al equipo, logo o escudo del mismo y los jugadores.
* Árbitro: Se encargará de introducir el acta completa del partido o evento.

Gestión de torneos
##################

En cuanto a esta sección dispondremos de lo siguiente:

* Fixture automático: Realizará el sorteo de cruces de forma automática.
* Importación a partir de planillas excel: Se podrá importar un fixture activo a nuestra competición, procesando los datos, adjudicando puntos correspondientes a los equipos que jugaron previamente algún partido.
* Administrador de clasificaciones: Realizarán el cálculo y reparto de puntos, permitiendo la edición manual de los resultados.
* Modalidades: Se implementarán diferentes modalidades según la disciplina para la cual se ha creado el torneo.
* Deportes: Soporte para múltiples tipos de deportes o disciplinas.
* Compartir: El torneo podrá ser compartido sobre diferentes redes sociales o a través de un link.
* Perfil público.

Gestión de equipos
##################

* Gestión de altas y bajas: Permitirá la administración de los integrantes del equipos.
* Tipos de equipos: Individual o grupal.
* Perfil público.
* Inscripción: Se presentarán formularios de inscripción para equipos. Se permiten dos modalidades: creación de equipo a través de torneo, o bien crear un equipo y luego ligarlo a un torneo.
* Gestión de pagos: Se incluirán modalidades de pago, por paypal, transferencia bancaria o bien en mano.

Gestión de jugadores
####################
* Alta o baja de jugadores.
* Enlace con el / los equipos.
* Impresión de fichas: los jugadores de cada equipo contarán con fichas personalizadas conteniendo datos y foto de cada uno de ellos.
* Perfil público.

Gestión de partidos
###################

* Cabeceras de actas: Se llenarán automáticamente para poder realizar el arbitraje correspondiente dejándola a disponibilidad de los árbitros en el inicio del partido.
* Estadísticas: Se guardarán y calcularán las correspondientes estadísticas para su futuro muestreo; así como también dejará disponible todos los datos para la generación de reportes.

Gestión de imagen
#################

Administración de la imagen perteneciente al torneo, pudiendo así publicitarla a través de diferentes redes sociales.

Notificaciones
##############

Recepción de notificación a través de distintos usuarios, por ejemplo: horario, fecha, lugar, suspensión, del partido, o bien vencimiento de cuotas.

Fixture
#######

Consulta de resultados de partidos anteriores, así como también consulta de futuros eventos.

Gestión de Equipos
##################

Posibilidad de gestionar equipos, dar de alta o baja jugadores, editando información personal, fotos y archivos adjuntos. Además se podrá visualizar el historial de cada equipo, estadísticas, etc.

Incidencias
###########

Visualización de estadísticas individuales de cada jugador: goles, tarjetas, tiempos, puntos, etc.

Marco Teórico
--------------

Metodologías ágiles
###################

El movimiento ágil busca alternativas al manejo de proyectos tradicional. Los enfoques ágiles ayudan a los equipos a responder a la impredecibilidad a través de un trabajo incremental e iterativo y un feedback empírico, es decir a través de corrección de fallos. Además, se proponen alternativas al desarrollo en cascada y secuencias tradicionales de desarrollo.

¿Por qué elegirlas? Proveen oportunidades para evaluar la dirección de un proyecto a través del desarrollo de su ciclo de vida. Esto se logra a través de un trabajo regular, conocido como iteración, donde al final, cada equipo, deberá presentar un producto potencialmente entregable. A través de repeticiones breves de ciclos de vida, así como tambien de productos funcionales, la metodología ágil se describe como iterativa e incremental. En los desarrollos en cascada, los equipos tienen una única chance de conseguir un aspecto de proyecto correcto, mientras que en el paradigma ágil, cada aspecto de desarrollo, requerimientos, diseño, etc., es contínuamente revisado a través del ciclo de vida. Cuando un equipo se para y re-evalúa la dirección de un proyecto cada dos semanas, siempre hay tiempo para encaminarse en otra dirección.

Scrum
#####

Es el camino más popular de introducción a la "Agilidad" debido a su simplicidad y flexibilidad. Debido a su popularidad, muchas organizaciones dicen "hacer Scrum" pero no están siquiera cerca a la definición actual de Scrum. Scrum hace énfasis en el feedback empírico, los equipos se autogestionan y esfuerzan para construir productos debidamente probados con pequeñas iteraciones.

Se considera a Scrum un framework para el desarrollo incremental de productos, utilizando equipos interfuncionales y auto-organizados. Provee una estructura de roles, meetings, reglas y artefactos, donde los equipos son los responsables de crear y adaptar sus procesos dentro de este framework.

Por otro lado, Scrum utiliza iteraciones de longitud fija: Sprints. Los Sprints no son mayores a 30 días, preferentemente menores. Los equipos de Scrum tratan de construir un incrementos de producto (apropiadamente probado) por cada Sprint.

Scrum vs Cascada
################

El enfoque incremental e iterativo cambia las fases de desarrollo tradicional del modelo cascada por la habilidad de desarrollar un conjunto de características de alto valor incorporando feedback lo más pronto posible.

.. figure:: pictures/cascada.png
  :scale: 75%
  :alt: cascada

  Modelo en cascada tradicional.
  Depende de un entendimiento perfecto de los requerimientos del producto para minimizar el número de errores en cada fase.

.. figure:: pictures/scrumiteration.png
  :scale: 75%
  :alt: scrum

  Modelo de iteraciones en Scrum.
  Une todas las etapas de desarrollo en cada iteración, adaptandolas al descubrimiento de realidades en intervalos fijos.

El beneficio más grande de Scrum es para trabajos complejos que conlleven creación de conocimiento y colaboración, tales como el desarrollo de un neuvo producto. Generalmente es asociado con el desarrollo de software orientado a objetos.

Características de un equipo Scrum
##################################

* Interfuncional: existen miembros de distintas disciplinas: analista de negocios, diseñadores, expertos del dominio, etc.
* Auto-organizado / auto-gestionado.
* Se planea un Sprint a la vez con el Product Owner.
* Posee autonomía de acuerdo a cómo desarrollar cada incremento.
* Intensamente colaborativo.
* Muy exitoso cuando todo el equipo se encuentra en la misma sala, particularmente para los primeros Sprints.
* Muy exitoso a largo plazo cuando existe permanencia de los miembros a largo plazo.
* De 3 a 9 miembros.
* Tiene un rol de liderazgo.
