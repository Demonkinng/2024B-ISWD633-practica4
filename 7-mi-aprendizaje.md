# Mi Aprendizaje

La presenta práctica fue útil para aprender a restringir recursos del sistema que un contenedor puede utilizar, ya que por defecto un contenedor tendrá acceso a todos los recursos del sistema, lo cual no es óptimo en algunos escenarios, sobre todo en producción. También, aprendí a configurar un healtcheck para comprobar que los contenedores se ejecuten correctamente.

La parte más importante fue la de crear imágenes a partir de un Dockerfile, ya que usar un Dockerfile mejora la eficiencia, consistencia y control de los contenedores en proyectos de desarrollo y despliegue. Además, de configurar las políticas de reinicio para los contenedores y así tener un entorno óptimo.

## Problema

El problema estaba en el Dockerfile al utilizar la imagen de CentOS, la cual ya está discontinuada de Docker hub, razón por la cual se optó por levantar el servidor apache utilizando directamente la imagen que se proporciona en Docker Hub.
