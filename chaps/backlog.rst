.. raw:: PDF

    PageBreak
    
Backlog
--------

El product owner junto con los stakeholders escribieron y priorizaron las siguientes historias de usuario.
Mientras avanzan los sprints el orden de prioridad de las historias puede ir cambiando.

.. class:: backlog

+---------------------------------------------------+
| Backlog                                           |
+=====+=============================================+
| #1  | Registro de Usuario                         |
+-----+---------------------------------------------+
| #2  | Ingreso al sistema                          |
+-----+---------------------------------------------+
| #3  | Registo de torneos                          |
+-----+---------------------------------------------+
| #4  | Lista de Torneos                            |
+-----+---------------------------------------------+
| #5  | Modificar Torneo                            |
+-----+---------------------------------------------+
| #6  | Eliminación de Torneo                       |
+-----+---------------------------------------------+
| #7  | Lista de equipos por torneo                 |
+-----+---------------------------------------------+
| #8  | Registro de Equipo                          |
+-----+---------------------------------------------+
| #9  | Modificar un Equipo                         |
+-----+---------------------------------------------+
| #10 | Eliminar Equipo                             |
+-----+---------------------------------------------+
| #11 | Registrar jugadores para un equipo          |
+-----+---------------------------------------------+
| #12 | Modificar información de jugador            |
+-----+---------------------------------------------+
| #13 | Eliminar jugador de un equipo               |
+-----+---------------------------------------------+
| #14 | Dockerizar aplicación                       |
+-----+---------------------------------------------+
| #15 | Crear estructura base de proyecto back-end  |
+-----+---------------------------------------------+
| #16 | Crear estructura base de proyecto front-end |
+-----+---------------------------------------------+
| #17 | Configuración integración contínua          |
+-----+---------------------------------------------+
| #18 | Generar Fixture                             |
+-----+---------------------------------------------+
| #19 | Crear game/match/partido                    |
+-----+---------------------------------------------+
| #20 | Ver estadísticas equipo                     |
+-----+---------------------------------------------+
| #21 | Ver Estadísticas del Jugador                |
+-----+---------------------------------------------+
| #22 | Agregar comentarios para un partido         |
+-----+---------------------------------------------+
| #23 | Habilitar mensajería entre usuarios         |
+-----+---------------------------------------------+
| #24 | Agregar notificaciones                      |
+-----+---------------------------------------------+
| #25 | Exportar fixture a excel                    |
+-----+---------------------------------------------+
| #26 | Generar pdf del fixture                     |
+-----+---------------------------------------------+
| #27 | Implementar sección de mis noticias         |
+-----+---------------------------------------------+
| #28 | Importar nuevo equipo desde excel           |
+-----+---------------------------------------------+
| #29 | Crear página resultados de la última fecha  |
+-----+---------------------------------------------+
| #30 | Agregar una nueva noticia                   |
+-----+---------------------------------------------+
| #31 | Calificar noticia                           |
+-----+---------------------------------------------+
| #32 | Crear página para lista de torneos públicos |
+-----+---------------------------------------------+
| #33 | Crear página para torneo                    |
+-----+---------------------------------------------+
| #34 | Administrar estado de torneo                |
+-----+---------------------------------------------+
| #35 | Ver una Noticia                             |
+-----+---------------------------------------------+
| #36 | Ocultar una noticia                         |
+-----+---------------------------------------------+
| #37 | Censurar comentarios                        |
+-----+---------------------------------------------+
| #38 | Pagina perfil de usuario                    |
+-----+---------------------------------------------+
| #39 | Ver un resultado de un juego                |
+-----+---------------------------------------------+

Tabla con todos los backlog items.


A continuación se detallan algunas historias de usuario, el resto de historias se encuntran en el anexo.

.. class:: user-story

+------------------------------------------------------------------------------+
| #1 Registro de Usuario                                                       |
+==============================================================================+
| **Descripción:** como usuario quiero poder registrarme en el sistema.        |
+------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                 |
|                                                                              |
|- Ingresar nombre y apellido.                                                 |
|- Ingresar fecha de nacimiento.                                               |
|- Ingrear Email.                                                              |
|- Ingresar password.                                                          |
|- Ingresar password confirmation.                                             |
|- Validación de todos los campos anteriores.                                  |
+------------------------------------------------------------------------------+
| Story points: 5                                                              |
+------------------------------------------------------------------------------+

.. figure:: pictures/backlog/1/exito.png
  :scale: 120%

  Figura 17: Registro exitoso.

.. figure:: pictures/backlog/1/step-1.png
  :scale: 120%

  Figura 18: Billing, elegir plan.

.. figure:: pictures/backlog/1/step-2.png
  :scale: 120%

  Figura 19: Formulario de registro.

.. raw:: PDF

  PageBreak

.. class:: user-story

+----------------------------------------------------------------------------+
| #2 Ingreso al sistema                                                      |
+============================================================================+
| **Descripción:** Como usuario registrado deseo poder ingresar al sistema.  |
+----------------------------------------------------------------------------+
| **Criterios de aceptación:**                                               |
|                                                                            |
|- Ingresar email y password.                                                |
|- Validar email y password.                                                 |
|- Luego de ingresar se redirecciona al usuario a la página principal.       |
|- Mantener la sesión por 1 semana aunque la aplicación se cierre.           |
+----------------------------------------------------------------------------+
| Story points: 5                                                            |
+----------------------------------------------------------------------------+

.. figure:: pictures/backlog/2/login.png
  :scale: 120%

  Figura 20: Formulario de ingreso al sistema.

.. raw:: PDF

  PageBreak

.. class:: user-story

+-----------------------------------------------------------------------------------------------------------------------+
| #3 Registo de torneos                                                                                                 |
+=======================================================================================================================+
| **Descripción:** Como usuario registrado deseo poder crear un torneo.                                                 |
+-----------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                          |
|                                                                                                                       |
|- Se deben ingresar los campos: nombre de torneo, descripción, fecha de inicio, cantidad de equipos                    |
|- Los campos nombre, cantidad de equipos y fecha de inicio son obligatorios.                                           |
|- La cantidad mínima de equipos es de 2                                                                                |
|- Luego de registrar el torneo exitosamente se redirecciona al usuario a la lista de torneos                           |
|- El torneo deberá tener un estado inicial: "creado". Más adelante se definiran los posibles cambios de estados.       |
+-----------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                       |
+-----------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/3/agregar.png
  :scale: 120%

  Figura 21: Formulario para crear un nuevo torneo.

.. raw:: PDF

  PageBreak

.. class:: user-story

+-------------------------------------------------------------------------------------------------+
| #4 Lista de Torneos                                                                             |
+=================================================================================================+
| **Descripción**: Como usuario registrado deseo poder visualizar mi lista de torneos             |
| de tal manera que pueda acceder fácilmente a la información de un torneo enparticular.          |
+-------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                    |
|                                                                                                 |
|- Mostrar una tabla con nombre fecha de inicio, descripción, cantidad de equipos, y su estado.   |
|- Se desea poder utilizar paginado.                                                              |
|- Se desea poder ordenar por nombre y por fecha.                                                 |
|- Se desea poder buscar un torneo a traves de un campo de texto1.                                |
+-------------------------------------------------------------------------------------------------+
| Story points: 5                                                                                 |
+-------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/4/lista.png
  :scale: 120%

  Figura 22: Lista de torneos.

.. figure:: pictures/backlog/4/datos-ok.png
  :scale: 120%

  Figura 23: Se agrego exitosamente un nuevo torneo.

.. figure:: pictures/backlog/4/datos-error.png
  :scale: 120%

  Figura 24: No se pudo agregar un nuevo torneo

.. raw:: PDF

  PageBreak

