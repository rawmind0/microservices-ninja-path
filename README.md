# microservices-ninja-path

El tutorial ira progresivamente mostrando como ocurre la evolución desde una aplicación desde un monolito hasta una arquitectura de microservicios. Es un tutorial práctico. La duración del mismo es de cinco días.

# Requisitos previos

* Conocimientos del sistema de control de versiones git
* Conocimientos del lenguaje de programación java

# Planificación

Esta es la planificación de contenido tentativa. Pensamos que la duración ideal son 5 días, entre 2 y 3 horas cada día.

## Día 1. Bounded contexts

El objetivo de este primer día es generar una propuesta de como se puede dividir el sistema en microservicios y una estrategía para hacerlo.

*  Presentación. En que consiste el tutorial, objetivos, etc.
*  Nuestro monolito, funcionalidad principales de la aplicación con la que vamos a trabajar.
*  Charla teórica. Estrategias para partir un monolito.
*  Trabajo en grupo. Propuesta de partición en microservicios.
*  Presentación de las diferentes opciones por parte de los grupos.
*  Charla teórica. Arquitectura evolutiva.
*  Trabajo en grupo. Generación de una estrategía.
*  Conclusiones.

### Materiales 

* Repositorio git con el código fuente del monolito
* Máquina virtual, con todo lo necesario para ejecutar la aplicación.

## Día 2. Docker

El objetivo del día 2 será conseguir empaquetar en un contenedor uno de los microservicios para su posterior despliegue en producción.

* ¿Que es DevOps?
* ¿Cómo operar un contenedor docker?
* Ejercicio práctico: A partir de la plantilla poder crear un servicio en local. 

### Materiales 

* Plantilla de docker para poder incluir el código del microservicio.

## Día 3. Continuous delivery

El objetivo del día 3 será poner el servicio en producción usando despliegue automatizado.

* ¿Que es Continuous Delivery?
* Presentación de la herramienta de CD.
* Anatomía de un pipeline.
* Ejercicio práctico. El servicio en producción.
 * Clonar el pipeline.
 * Cambiar el sistema de control de versiones.
 * Añadir un nuevo stage para despliegue en producción.

### Materiales 

* Pipeline base que despliegue uno de las microservicios de la app
* Entorno con la herramienta de continuous delivery preparada para poder trabajar
* Rancher instalado en open stack con dos entornos uno de pre y otro de pro para poder desplegar el contenedor.


## Día 4. 

El objetivo del día 4 es demostrar como se opera un servicio en producción

### Materiales 

* 

## Día 5. Kubernetes

*  Conclusiones del tutorial

### Materiales 

* 

