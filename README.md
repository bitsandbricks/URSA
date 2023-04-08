# URSA

**U**rban **R**eporting based on **S**atellite **A**nalysis

## **¿Qué es?**

URSA es un sistema de apoyo para la planificación urbana. Permite acceder de forma sencilla a la enorme cantidad de información capturada por sensores satelitales, encargándose de recopilar, procesar y presentar información clave acerca de la evolución de ciudades en Latinoamérica y el Caribe (LAC).

URSA es una herramienta gratuita, de código abierto.


## ¿Por qué fue desarrollada?

El sistema fue desarrollado en colaboración entre la División de Vivienda y Desarrollo Urbano (HUD) del BID y el Centro para el Futuro de las Ciudades del Tecnológico de Monterrey. La misión fue la de diseñar una plataforma que permita a los gobiernos municipales adquirir de forma fácil información cartográfica actualizada, en el formato apropiado y en la resolución geográfica adecuada. 


## ¿Por qué la estamos compartiendo?

URSA está a disposición del público general, y sobre todo de equipos de gobierno, para apoyar los procesos de toma de decisiones, planificación y gestión en ciudades y regiones metropolitanas.


## Instalación

(estos pasos son requeridos sólo una vez)

1. Clonar o descargar el contenido de este repositorio.

2. Instalar
[Docker](https://docs.docker.com/engine/install/)

3. Iniciar la imagen de docker con el código y dependencias. Desde el directorio
donde se ha descargado la aplicación, ejecutar:

        docker build -t bid-urban-growth .

El proceso tomará un buen rato la primera vez, ya que necesitará descargar y
configurar varios componentes de software. Una vez completada la primera
puesta en marcha, las subsiguientes serán casi instantáneas.

## Uso

Para cargar y correr un contenedor con la imagen de docker, se debe ejecutar el siguiente comando:

    python3 launcher.py

Se abrirá una ventana con la dirección http://localhost:8050/ que después de 10 segundos se deberá recargar en caso de que permanezca sin conexión.
