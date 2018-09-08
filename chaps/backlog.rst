Backlog
--------

+--------------------------------------------------------------------------+
| #1 Registro de Usuario.                                                  |
+--------------------------------------------------------------------------+
| Descripción: como usuario quiero poder registrarme en el sistema.        |
+--------------------------------------------------------------------------+
| Criterios de aceptación:                                                 |
| 1. Ingresar nombre y apellido.                                           |
| 2. Ingresar fecha de nacimiento.                                         |
| 3. Ingrear Email.                                                        |
| 4. Ingresar password.                                                    |
| 5. Ingresar password confirmation.                                       |
| 6. Validación de todos los campos anteriores.                            |
+--------------------------------------------------------------------------+
| Tareas:                                                                  |
| 1. Crear componente en react para la registración (UI).                  |
| 2. Crear endpoint que reciba los datos y los guarde en la base de datos. |
+--------------------------------------------------------------------------+
| Story points: 5                                                          |
+--------------------------------------------------------------------------+

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

+------------------------------------------------------------------------+
| #2 Ingreso al sistema.                                                 |
+------------------------------------------------------------------------+
| Descripción: Como usuario registrado deseo poder ingresar al sistema.  |
+------------------------------------------------------------------------+
| Criterios de aceptación:                                               |
| 1. Ingresar email y password.                                          |
| 2. Validar email y password.                                           |
| 3. Luego de ingresar se redirecciona al usuario a la página principal. |
| 4. Mantener la sesión por 1 semana aunque la aplicación se cierre.     |
+------------------------------------------------------------------------+
| Tareas:                                                                |
| 1. Crear componente en react para el inicio de sesión (UI).            |
| 2. Crear endpoint para manejar el inicio de sesión.                    |
+------------------------------------------------------------------------+
| Story points: 5                                                        |
+------------------------------------------------------------------------+

.. figure:: pictures/backlog/2/login.png
  :scale: 80%

  Formulario de ingreso al sistema.

.. raw:: PDF

  PageBreak

+------------------------------------------------------------------------------------------------------+
| #2 Registo de torneos.                                                                               |
+------------------------------------------------------------------------------------------------------+
| Descripción: Como usuario registrado deseo poder crear un torneo.                                    |
+------------------------------------------------------------------------------------------------------+
| Criterios de aceptación:                                                                             |
| 1. Se deben ingresar los campos: nombre de torneo, descripción, fecha de inicio, cantidad de equipos |
| 2. Los campos nombre, cantidad de equipos y fecha de inicio son obligatorios.                        |
| 3. La cantidad mínima de equipos es de 2                                                             |
| 4. Luego de registrar el torneo exitosamente se redirecciona al usuario a la lista de torneos        |
+------------------------------------------------------------------------------------------------------+
| Tareas:                                                                                              |
| 1. Crear componente para ingresar un torneo (UI).                                                    |
| 2. Crear endpoint que reciba los datos ingresados y los guarde en la base de datos.                  |
+------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                      |
+------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/3/agregar.png
  :scale: 80%

  Formulario para crear un nuevo torneo.

.. raw:: PDF

  PageBreak
