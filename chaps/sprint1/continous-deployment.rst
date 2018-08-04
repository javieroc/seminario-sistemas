Despliegue Continuo
###################

Para describir esta práctica, tomaremos un enfoque top-down.
En primera instancia necesitamos comparar Despliegue Continuo y Entregas Continuas
(Continous Deployment vs Continous Delivery).

Continous Delivery, hace referencia a una serie de prácticas diseñadas
para asegurar que el código pueeda ser desplegado a producción de manera segura y rápida,
de tal manera que la aplicación y servicios funcionen como se espera, a través de rigurosos tests automatizados.
Debido a que cada cambio es entregado a un entorno de espera usando completa automatización, se puede tener la seguridad
de que la aplicación pueda ser desplegada a producción con sólo apretar un boton cuando el negocio está listo.

Continous Deployment, es la siguiente etapa de Continous Delivery. Cada cambio que pase por los tests automatizados 
es desplegado a producción automáticamente. Este proceso debe ser el objetivo de todas las compañías que no están reguladas con otros requerimientos.

Para llegar a estas últimas etapas, es necesario contar con Integración Continua (Continous Integration), la cual es una práctica
donde los desarrolladores chequean el código de manera continua. Es recomendado que los cambios sean combinados al menos una vez al día. Estos
cambios son automáticamente validados por la creación de tests unitarios y de integración sobre el código.

¿Qué son los tests unitarios?

Es un método por el cuál unidades individuales o conjuntos de código fuente, son evaluados a través de ciertos casos de prueba.

¿Qué son los tests de integración?

Hace referencia a la fase de testeo de software donde los módulos individuales son combinados y testeados en grupos. Este proceso ocurre luego de que los tests unitarios fueron validados.

La implementación de estas prácticas requiere un enfoque bottom-up:

1. En primera instancia se debe configurar Continous Integration

Requisitos:

* Un cierto porcentaje de Code Coverage a partir de tests unitarios y de integración.
* Un sistema de construcción (build) de no más de 10-15 minutos permitiendo a los desarrolladores chequear esto frecuentemente.

Beneficios:

* Evitar integración mientras se combinan grandes porciones de código a lo largo del desarrollo.

.. figure:: pictures/sprint1/ci.png
  :scale: 100%
  :alt: integration

  Figura X: Continous Integration

2. Configuración de Entregas Continuas

Requisitos:

* Test unitarios
* Test integración
* Un entorno de pruebas (stage)
* Un pipeline configurado para usar CI/CD

Beneficios:

* Permite tener iteraciones listas para ser desplegadas a producción.
* En teoría se puede desplegar a producción una vez al día.

.. figure:: pictures/sprint1/delivery.png
  :scale: 100%
  :alt: delivery

  Figura X: Continous Delivery


3. Configuración de Despliegue Continuo

Requisitos:

* CI / CD como base
* Extensa cantidad de tests automatizados
* Control de versiones sano y adecuado para poder revertir cambios de manera simple en caso de errores.

Beneficios:

* Asegura que todos los cambios llegan al usuario casi inmediatamente (unas cuantas horas máximo).

.. figure:: pictures/sprint1/despliegue.png
  :scale: 100%
  :alt: deployment

  Figura X: Continous Deployment
  