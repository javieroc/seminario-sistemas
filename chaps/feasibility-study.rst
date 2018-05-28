Estudio de factibilidad
-----------------------
El Estudio de Factibilidad busca determinar la viabilidad de un proyecto de desarrollo
de Software, teniendo en cuenta si el mismo ayuda a la organización a lograr sus objetivos
y si es posible su realización con los recursos actuales de la misma.

El estudio de factibilidad se hace a 4 niveles.

- Técnica,
- Económica,
- Operativo,
- Legal.

Factibilidad técnica
####################

Las herramientas de desarrollo de sofware que se utilizarán (editores de texto, lenguajes de programación, librerías y frameworks) son open source y gratuitos.

El proyecto cuenta con desarrolladores con experiencia en desarrollo web y mobile.

Para el deployment se utilizará un cloud económico y de facil uso.

Por estas razones consideramos que el proyecto es factible desde el punto de vista técnico.

Factibilidad económica
######################

Es importante realizar este estudio de factibilidad ya que consiste en una evaluación del costo de desarrollo frente al beneficio final producido por el sistema implementado que determinará si el sistema es “conveniente” desde el punto de vista económico. Define además, si la organización cuenta con los recursos económicos para encarar el proyecto.

El tiempo de desarrollo para el proyecto se estima en 4 meses trabajando 6 hrs diarias.
El gasto y la inverión requerida para el proyecto a desarrollar se detallan a continuación,
algunos valores son aproximados debido a que son conversión de su precio real en dolares.
Para el valor de la hora de trabajo de un analista programador se tuvo como referencia la tabla de honorarios del Copaipa [10].


**Mes 1:**

-   3 Analista programador: $72.000 ($200 por hr).
-   Subtotal: $72.000

**Mes 2:**

-   3 Analista programador: $72.000 ($200 por hr).
-   Cloud digital ocean para integración continua: $320.
-   Subtotal: $72.320

**Mes 3:**

-   3 Analista programador: $72.000 ($200 por hr).
-   Cloud digital ocean para integración continua: $320.
-   Subtotal: $72.320

**Mes 4:**

-   3 Analista programador: $72.000 ($200 por hr).
-   Cloud digital ocean para integración continua: $320.
-   Registro en playstore para subir la app mobile: $400.
-   Subtotal: $72.720

**Mes 5:**

A partir del mes 5, el servicio esta ya en producción, empieza una etapa de mantenimiento. Cada programador solo le dedicará 2 horas por día.

-   3 Analista programador: $24.000 ($200 por hr).
-   Cloud digital ocean para integración continua: $320.
-   Subtotal: $24.320


A partir del sexto mes se mantiene como costo fijo este monto de $24.320

El modelo de negocio es obtener ingresos por usuarios que adquieran planes pagos para obtener más beneficios en la plataforma.
Los planes que tendremos son los siguientes:

+------------------------+---------+--------+
| Planes                 | Mensual | Anual  |
+========================+=========+========+
| Free (1 Torneo)        | $0      | $0     |
+------------------------+---------+--------+
| Gold (5 Torneos)       | $72     | $800   |
+------------------------+---------+--------+
| Platinum (Sin límites) | $120    | $1200  |
+------------------------+---------+--------+

Los usuarios anónimos podrán navegar por las páginas de los torneos y consultar las estadísticas pero no podrá crear ninguna entidad Dentro
del sistema.

Los beneficios esperados se detallan a continuación, para ello se harán algunos supuestos teniendo en cuenta un crecimiento lineal.

**Mes 1:**

El primer Mes después del lanzamiento del servicio se esperan al menos 200 usuarios. De los cuales 50 adquieren algún tipo de plan, supongamos:

-   20 subscripciones Gold mensuales: $1440
-   10 subscripciones Gold anuales: $8000
-   15 subscripciones Platinum mensuales: $1800
-   5 subscripciones Platinum mensuales: $6000
-   Subtotal: $17240

**Mes 2:**

El segundo Mes esperamos obtener usuarios de otras disciplinas deportivas no solamente futbol, y además como la aplicación estará en español e ingles, se esperán usuarios de todas partes del mundo.
Se estiman un registro aproximado de 300 usuarios. De los cuales 100 acceden a un plan:

-   40 subscripciones Gold mensuales: $2880
-   20 subscripciones Gold anuales: $16000
-   30 subscripciones Platinum mensuales: $3600
-   10 subscripciones Platinum anuales: $12000
-   Subtotal: $34480

**Mes 3:**

Se espera seguir creciendo en usuarios activos, aproximadamente 400. De los cuales 150 acceden a un plan:

-   60 subscripciones Gold mensuales: $4320
-   30 subscripciones Gold anuales: $24000
-   45 subscripciones Platinum mensuales: $5400
-   15 subscripciones Platinum anuales: $18000

Total después del tercer Mes: $51720

+--------+---------+----------+----------+-----------------+
| Meses  | Costos  | Ingresos | Flujo    | Flujo acumulado |
+========+=========+==========+==========+=================+
| Mes 1  | $72000  | $17240   | $−54760  | $−54760         |
+--------+---------+----------+----------+-----------------+
| Mes 2  | $72320  | $34480   | $−37840  | $−92600         |
+--------+---------+----------+----------+-----------------+
| Mes 3  | $72320  | $51720   | $−20600  | $−113200        |
+--------+---------+----------+----------+-----------------+
| Mes 4  | $72720  | $68960   | $−3760   | $−116960        |
+--------+---------+----------+----------+-----------------+
| Mes 5  | $24320  | $86200   | $61880   | $−55080         |
+--------+---------+----------+----------+-----------------+
| Mes 6  | $24320  | $103440  | $79120   | $24040          |
+--------+---------+----------+----------+-----------------+
| Mes 7  | $24320  | $120680  | $96360   | $120400         |
+--------+---------+----------+----------+-----------------+
| Mes 8  | $24320  | $137920  | $113600  | $234000         |
+--------+---------+----------+----------+-----------------+
Figura 5. Análisis de recuperación de inversión.

El análisis de recuperación nos muestra que recuperamos nuestra inversión en el mes 6.

Por los beneficios obtenidos que se lograrán por este desarrollo, el proyecto es factible desde el punto de vista económico.


Factibilidad legal
##################

Las herramientas de desarrollo, lenguajes de programación, librerías, frameworks, sistemas gestores de base de datos,
sistemas operativos y servicios en la nube, fueron adquiridos legalmente y de acuerdo a las resoluciones impositivas vigentes.
Por lo tanto, de acuerdo a lo anteriormente mencionado, el proyecto es posible desde el punto de vista legal.

Factibilidad Operativa
######################

Gran parte de la factibilidad operativa depende de las interfaces de usuario elegidas. Se utilizaran patrones de diseños conocidos y probados.
Los potenciales usuarios tanto de la aplicación mobile como web, están familiarizados con este tipo de aplicaciones.
De cualquier manera, en la web estará la documentación necesaria para el uso de la aplicación, formas de pago, instalación e información de contacto.
