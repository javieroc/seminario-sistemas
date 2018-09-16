Backlog
--------

+------------------------------------------------------------------------------+
| #1 Registro de Usuario.                                                      |
+------------------------------------------------------------------------------+
| **Descripción:** como usuario quiero poder registrarme en el sistema.        |
+------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                 |
| 1. Ingresar nombre y apellido.                                               |
| 2. Ingresar fecha de nacimiento.                                             |
| 3. Ingrear Email.                                                            |
| 4. Ingresar password.                                                        |
| 5. Ingresar password confirmation.                                           |
| 6. Validación de todos los campos anteriores.                                |
+------------------------------------------------------------------------------+
| Tareas:                                                                      |
| 1. Crear componente en react para la registración (UI).                      |
| 2. Crear endpoint que reciba los datos y los guarde en la base de datos.     |
+------------------------------------------------------------------------------+
| Story points: 5                                                              |
+------------------------------------------------------------------------------+

.. figure:: pictures/backlog/1/exito.png
  :scale: 80%

  Registro exitoso.

.. figure:: pictures/backlog/1/step-1.png
  :scale: 80%

  Formulario de registro.

.. figure:: pictures/backlog/1/step-2.png
  :scale: 80%

  Billing: elegir plan.

.. raw:: PDF

  PageBreak

+----------------------------------------------------------------------------+
| #2 Ingreso al sistema.                                                     |
+----------------------------------------------------------------------------+
| **Descripción:** Como usuario registrado deseo poder ingresar al sistema.  |
+----------------------------------------------------------------------------+
| **Criterios de aceptación:**                                               |
| 1. Ingresar email y password.                                              |
| 2. Validar email y password.                                               |
| 3. Luego de ingresar se redirecciona al usuario a la página principal.     |
| 4. Mantener la sesión por 1 semana aunque la aplicación se cierre.         |
+----------------------------------------------------------------------------+
| Tareas:                                                                    |
| 1. Crear componente en react para el inicio de sesión (UI).                |
| 2. Crear endpoint para manejar el inicio de sesión.                        |
+----------------------------------------------------------------------------+
| Story points: 5                                                            |
+----------------------------------------------------------------------------+

.. figure:: pictures/backlog/2/login.png
  :scale: 80%

  Formulario de ingreso al sistema.

.. raw:: PDF

  PageBreak

+-----------------------------------------------------------------------------------------------------------------------+
| #3 Registo de torneos.                                                                                                |
+-----------------------------------------------------------------------------------------------------------------------+
| **Descripción:** Como usuario registrado deseo poder crear un torneo.                                                 |
+-----------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                          |
| 1. Se deben ingresar los campos: nombre de torneo, descripción, fecha de inicio, cantidad de equipos                  |
| 2. Los campos nombre, cantidad de equipos y fecha de inicio son obligatorios.                                         |
| 3. La cantidad mínima de equipos es de 2                                                                              |
| 4. Luego de registrar el torneo exitosamente se redirecciona al usuario a la lista de torneos                         |
| 5. El torneo deberá tener un estado inicial: "creado". Más adelante se definiran los posibles cambios de estados.     |
+-----------------------------------------------------------------------------------------------------------------------+
| Tareas:                                                                                                               |
| 1. Crear componente para ingresar un torneo (UI).                                                                     |
| 2. Crear endpoint que reciba los datos ingresados y los guarde en la base de datos.                                   |
+-----------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                       |
+-----------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/3/agregar.png
  :scale: 80%

  Formulario para crear un nuevo torneo.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------------+
| #4 Lista de Torneos                                                                             |
+-------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder visualizar mi lista de torneos             |
| de tal manera que pueda acceder fácilmente a la información de un torneo enparticular.          |
+-------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                    |
| 1. Mostrar una tabla con nombre fecha de inicio, descripción, cantidad de equipos, y su estado. |
| 2. Se desea poder utilizar paginado.                                                            |
| 3. Se desea poder ordenar por nombre y por fecha.                                               |
| 4. Se desea poder buscar un torneo a traves de un campo de texto1.                              |
+-------------------------------------------------------------------------------------------------+
| Tareas:                                                                                         |
| 1. Crear componente para listar los torneos (UI).                                               |
| 2. Crear endpoint para obtener los torneos que permita paginar y filtrar.                       |
+-------------------------------------------------------------------------------------------------+
| Story points: 5                                                                                 |
+-------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/4/lista.png
  :scale: 80%

  Lista de torneos.

.. figure:: pictures/backlog/4/datos-ok.png
  :scale: 80%

  Se agrego exitosamente un nuevo torneo.

.. figure:: pictures/backlog/4/datos-error.png
  :scale: 80%

  No se pudo agregar un nuevo torneo

.. raw:: PDF

  PageBreak

+--------------------------------------------------------------------------------------------------------------+
| #5 Modificar Torneo                                                                                          |
+--------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder modificar/editar un torneo particular.                  |
+--------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                 |
| 1. Desde la tabla de mis torneos deseo poder seleccionar uno para editarlo.                                  |
| 2. Se desea poder modificar nombre, descripción, fecha de inicio, cantidad de equipos y su estado.           |
| 3. Validar los campos modificados                                                                            |
| 4. Si el torneo se encuentra en progreso, los campos fecha de inicio y cantidad de equipos se dehabilitarán. |
+--------------------------------------------------------------------------------------------------------------+
| Tareas:                                                                                                      |
| 1. Crear o reutilizar componente de formulario para torneo (UI).                                             |
| 2. Crear endpoint que me permita actualizar el torneo en la base de datos.                                   |
+--------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                              |
+--------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/5/editar.png
  :scale: 80%

  Formulario para editar torneo

.. raw:: PDF

  PageBreak

+----------------------------------------------------------------------------------------+
| #6 Eliminación de Torneo                                                               |
+----------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder eliminar uno de mis torneos, pero |
| dejando la posibilidad de poder recuperar la información en el futuro.                 |
+----------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                           |
| 1. Desde la tabla de mis torneos deseo poder seleccionar alguno para eliminarlo        |
| 2. Deberá mostrarse una notificación para confirmar dicha eliminación                  |
+----------------------------------------------------------------------------------------+
| Tareas:                                                                                |
| 1. Crear endpoint que me permita borrar el torneo de manera que pueda recuperarse      |
| los datos de ser necesario.                                                            |
+----------------------------------------------------------------------------------------+
| Story points: 2                                                                        |
+----------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/6/eliminar.png
  :scale: 80%

  Dialogo de confirmación para eliminar un torneo.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------+
| #7 Lista de equipos por torneo.                                                           |
+-------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario deseo poder observar la lista de mis equipos para un torneo |
|  en particular, de tal manera que me permita visualizar y  obtener                        |
| información básica de un equipo.                                                          |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
| 1. Se deberá poder paginar una lista de equipos                                           |
| 2. Se deberá poder ordenar y buscar con filtros                                           |
+-------------------------------------------------------------------------------------------+
| Tareas:                                                                                   |
| 1. Crear componente para listar los equipos de un torneo (UI).                            |
| 1. Crear endpoint para obtener los equipos de un torneo en particular, debe aceptar       |
| paginación y filtros.                                                                     |
+-------------------------------------------------------------------------------------------+
| Story points: 5                                                                           |
+-------------------------------------------------------------------------------------------+


.. figure:: pictures/backlog/7/lista-equipos.png
  :scale: 80%

  Lista de equipos para un torneo.

.. figure:: pictures/backlog/7/datos-ok.png
  :scale: 80%

  Equipo agregado exitosamente.

.. figure:: pictures/backlog/7/datos-error.png
  :scale: 80%

  Error al agregar un nuevo equipo.

.. raw:: PDF

  PageBreak

+---------------------------------------------------------------------------------------------------------------------+
| #8 Registro de Equipo                                                                                               |
+---------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder crear un equipo.                                               |
+---------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                        |
| 1. Luego de elegir un torneo se deberá poder clickear un botón para crear un equipo ubicado en la lista de equipos. |
| 2. Se deberá ingresar la siguiente información: nombre de equipo, nombre del capitán o encargado.                   |
| 3. El campo nombre de equipo y del capitán son obligatorios.                                                        |
+---------------------------------------------------------------------------------------------------------------------+
| Tareas:                                                                                                             |
| 1. Crear componente para agregar un nuevo equipo (UI).                                                              |
| 1. Crear endpoint para salvar los datos del nuevo equipo.                                                           |
+---------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                     |
+---------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/8/agregar.png
  :scale: 80%

  Error al agregar un nuevo equipo.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------------------+
| #9 Modificar un Equipo                                                                                |
+-------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado quiero poder modificar la información de uno de mis equipos. |
+-------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                          |
| 1. Se deberá validar cada campo modificado.                                                           |
+-------------------------------------------------------------------------------------------------------+
| Tareas:                                                                                               |
| 1. Crear componente o reutilizar formulario para modificar un equipo (UI).                            |
| 2. Crear endpoint para actualizar los datos de un equipo.                                             |
+-------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                       |
+-------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/9/editar.png
  :scale: 80%

  Formulario para editar un equipo.

.. raw:: PDF

  PageBreak

+------------------------------------------------------------------------------------+
| #10 Eliminar Equipo                                                                |
+------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado quiero poder eliminar uno de mis equipos. |
+------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                       |
| 1. Se deberá validar cada campo modificado.                                        |
+------------------------------------------------------------------------------------+
| Tareas:                                                                            |
| 1. Se deberá confirmar la eliminación con posibilidad de cancelación.              |
| 2. Se deberá enviar una notificación al capitán.                                   |
+------------------------------------------------------------------------------------+
| Story points: 2                                                                    |
+------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/10/eliminar.png
  :scale: 80%

  Dialogo para confirmar la eliminación de un equipo.

.. raw:: PDF

  PageBreak
