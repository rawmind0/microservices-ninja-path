# Getting started with microservices

El tutorial ira progresivamente mostrando como ocurre la evolución desde una pequeña aplicación monolítica hasta una arquitectura de microservicios.

Es un tutorial práctico. La práctica será una guiada.

La duración del mismo es de tres días.

# Público objetivo

Cualquier persona que tenga intención de introducirse en el mundo de los microservicios.

# Requisitos previos

* Conocimientos del sistema de control de versiones git.
* Conocimientos del lenguaje de programación java.
* Tener una cuenta de github para subir el código.
* Tener una cuenta de dockerhub para subir los contenedores.

# Nivel de curso

Básico, consiste en visión general de como se desarrolla y despliega en el mundo de los microservicios.

# Aforo

Entre 40 y 64 personas máximo. Se formarán grupos de 4 personas entre los asistentes para poder realizar las actividades prácticas. Si no hay 20 personas apuntadas una semana antés de la celebración del curso este se cancelara.

# Planificación

Esta es la planificación de contenido tentativa. Pensamos que la duración ideal son 5 días, entre 2 y 3 horas cada día.

## Lección 1.

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

## Día 2. Contenedores

El objetivo del día 2 será conseguir empaquetar en un contenedor uno de los microservicios para su posterior despliegue en producción.

* ¿Qué es un contenedor?
* ¿Qué es docker?
  * Registry.
  * Redes y almacenamiento.
  * Tareas básicas: crear, arrancar, parar, borrar...
* Ejercicio práctico: A partir de la plantilla, crear un contenedor para el servicio. 

### Materiales 

* Usuario github y dockerhub.
* Plantilla de docker para poder incluir el código del microservicio.

## Day 3. Plataforma de contenedores

El objetivo del día 3 será entender que es una plataforma de contenedores y sus componentes.

* Qué es una plataforma de contenedores?
  * Container scheduler.
  * system discovery.
  * Load balancer.
* Qué es Rancher? 
* Ejercicio práctico. 
  * Lanzar un servicio en la plataforma de contenedores.
  * Escalar el servicio.
  * Accediendo al servicio a través de un lb.
* Qué es el catálogo de Rancher?
* Ejercicio práctico. Desplegar una herramiento de Continuous Delivery desde el catálogo de rancher.
* Conclusiones

### Materiales 

* Sistema Rancher

## Día 4. Continuous delivery

El objetivo del día 4 será poner el servicio en producción usando despliegue automatizado.

* ¿Que es Continuous Delivery?
* Presentación de la herramienta de CD.
* Anatomía de un pipeline.
* Ejercicio práctico. El servicio en producción.
 * Clonar el pipeline.
 * Cambiar el sistema de control de versiones.
 * Añadir un nuevo stage para despliegue en producción.
* Conclusiones

### Materiales 

* Pipeline base que despliegue uno de las microservicios de la app
* Entorno con la herramienta de continuous delivery preparada para poder trabajar
* Rancher instalado en open stack con dos entornos uno de pre y otro de pro para poder desplegar el contenedor.

## Día 5. Practicas and preguntas

El objetivo del día 5 será hacer practicas y dedicarlo a las dudas y cuestiones de los asistentes.

* Ejercicio práctico.
* Dudas y preguntas.
* Conclusiones

