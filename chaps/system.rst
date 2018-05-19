Sistema Objeto
--------------

En terminos generales, la aplicación gestionará los datos de torneos, equipos y jugadores, para a partir de esta, generar información
relevante sobre dichos datos. La mejor manera de encarar este proyecto es con una arquitectura de microservicios, dicha arquitectura se
detallará más en profundidad luego, pero es importante destacar que las features descritas a continuación serán en implementadas por uno o más
de los pequeños servicios que conforman la aplicación.


**Gestión de usuarios**

Se gestionarán dos tipos de usuario, registrados y no registrados ó anónimos. Dentro de los usuarios registrados tendremos distintas
categorías según el tipo de plan que contraten. Todos los usuarios registrados tendrán acceso a todas las features de la aplicación, pero
con distinas restricciones dependiendo de su plan. Disponderemos de dos tipos planes para esta versión gold y platinum.

Planes:

* Free: podrá gestionar 1 torneo.
* Gold: podrá gestionar 5 torneos.
* Platinum: podrá gestionar torneos de manera ilimitada.

Los usuarios anónimos podrán navegar por las páginas de los torneos y consultar las estadísticas pero no podrá crear ninguna entidad Dentro
del sistema.

Para la autenticación de usuarios se utilizará JWT un estándar abierto basado en JSON para crear un token que sirva para asegurar
el envío de datos entre aplicaciones o servicios [4].

**Gestión de torneos**

En cuanto a esta sección dispondremos de lo siguiente:

* Alta baja y modificación de torneos: Se podrán crear distintos tipos de torneos, tipo todos contra todos (liga), tipo eliminación directa,  tipo todos contra todos por grupo y tipo round robin.
* Mostrar los torneos según la zona geográfica en que se encuentre el usuario.
* Fixture automático: Realizará el sorteo de cruces de forma automática.
* Importación a partir de planillas excel: Se podrá importar un fixture activo a nuestra competición, procesando los datos, adjudicando puntos correspondientes a los equipos que jugaron previamente algún partido.
* Administrador de clasificaciones: Realizarán el cálculo y reparto de puntos, permitiendo la edición manual de los resultados.
* Modalidades: Se implementarán diferentes modalidades según la disciplina para la cual se ha creado el torneo.
* Deportes: Soporte para múltiples tipos de deportes o disciplinas.
* Compartir: El torneo podrá ser compartido sobre diferentes redes sociales o a través de un link.
* Perfil público. Los usuarios Gold o Platinum tendrán disponible una frontpage de su organización y torneos.

**Gestión de equipos**

* Gestión de altas y bajas: Permitirá la administración de los integrantes del equipos.
* Tipos de equipos: Individual o grupal.
* Perfil público.
* Inscripción: Se presentarán formularios de inscripción para equipos. Se permiten dos modalidades: creación de equipo a través de torneo, o bien crear un equipo y luego ligarlo a un torneo.
* Gestión de pagos: Se incluirán modalidades de pago, por paypal, transferencia bancaria o bien en mano.

**Gestión de jugadores**

* Alta o baja de jugadores.
* Enlace con el / los equipos.
* Impresión de fichas: los jugadores de cada equipo contarán con fichas personalizadas conteniendo datos y foto de cada uno de ellos.
* Perfil público.

**Gestión de partidos**

Estadísticas: Se guardarán y calcularán las correspondientes estadísticas; así como también dejará disponible todos los datos para la generación de reportes.

**Notificaciones**

Los usuarios inscriptos en torneos recibirán push notifications con información de los torneos en los que está inscripto o es dueño.
Por ejemplo: horario, fecha, lugar, suspensión del partido, o bien vencimiento de cuotas.

**Fixture**

Registro de los partidos que se jugarán en determinada fecha. Consulta de resultados de partidos anteriores, así como también consulta de futuros eventos.

**Gestión de Equipos**

Posibilidad de gestionar equipos, dar de alta o baja jugadores, editando información personal, fotos y archivos adjuntos. Además se podrá visualizar el historial de cada equipo, estadísticas, etc.
Solicitud de inscripción a un torneo. El usuario dueño de un equipo podrá enviar solicitudes a diferentes torneos, luego el owner del torneo decidirá si aceptarlo o no.

**Incidencias**

Registro de incidencias en los partidos (goles, tarjetas, etc) realizadas por los jugadores.
