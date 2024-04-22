
# Curso de IBKR: Python TWS API
|[Atrás](./leccion2.3.md "Atrás")|[Siguiente](./leccion4.md "Siguiente")|
|---|---:|

## Lección 3: Accediendo al código fuente de la API TWS Python


* ### En qué consiste el código fuente y qué hace vista de alto nivel de la arquitectura API entornos diferentes en los que se ejecutan los programas API de Python.


El código fuente de la API sirve para definir los mensajes disponibles que se pueden intercambiar entre TWS y una aplicación API externa. 

![Captura de Pantalla 2024-04-19 a las 21 56 29](https://github.com/clitwiniuk/course-python-tws-api/assets/45191775/2db593e9-0331-48a4-ad64-250cfb9ba982)


Los mensajes se intercambian a través de una conexión de socket TCP utilizan un patrón de suscripción y publicación " pub/sub " se envía un mensaje desde un cliente API para suscribirse a un tipo particular de datos, después de lo cual TWS publica actualizaciones sobre ese tipo de datos a medida que ocurren en tiempo real. 

El código fuente de la API ayuda a traducir mensajes de nivel inferior a superior, que sea más conveniente para los programadores.

La API es de código abierto y se mantiene mediante el sistema de control de versiones Git y está alojada en el repositorio en línea GitHub (GitHub.com).

Todas las actualizaciones realizadas en la fuente de la API a lo largo del tiempo se rastrean mediante Git, y para realizar actualizaciones en la fuente de la API es necesario utilizar el programa Git.

* ### Cómo obtener acceso al repositorio de código fuente abierto de la API Python de TWS en GitHub

Las descargas y guías de la API de TWS se pueden encontrar en el menú Trading > API . Esto lo llevará a una página de descripción general de la API que le muestra las diferentes tecnologías en las que se ofrece la API.

Después de desplazarse hacia abajo hasta "API Trader Worksation (TWS)", aquí es donde verá el botón Descargas y recursos. Esta sección se expande para descargas, guías de usuario y notas de la versión tanto para TWS API como para IB Gateway.

El enlace directo al sitio de descarga de la API es [interactivebrokers.GitHub.io](https://interactivebrokers.GitHub.io/).

Dentro de la guía del usuario hay fragmentos de código de muestra tomados de los proyectos de muestra descargados, distribuidos con la API e instalados en la carpeta de muestras.

**Nuestra ubicación de instalación predeterminada para estos archivos será:**

**'C:\TWS API\samples'** para usuarios de Windows

**'{HOME}/IBJTS/sample'** para Linux o MacOS.

![Captura de Pantalla 2024-04-20 a las 7 29 38](https://github.com/clitwiniuk/course-python-tws-api/assets/45191775/d3c3c3b2-bebb-4c25-90d7-efddc298f07d)


Después de elegir una sección a la izquierda en la guía de referencia para mostrar la descripción de un tipo particular de funcionalidad, elija 'Python' en el menú en la parte superior para mostrar el código de muestra asociado en el lenguaje Python.

Desde la sección de recursos de API de nuestra página de API hay un enlace a las Notas de la versión de API que detallan las actualizaciones y las características nuevas. Estas notas de la versión suelen actualizarse varias veces al año.

![Captura de Pantalla 2024-04-20 a las 7 34 49](https://github.com/clitwiniuk/course-python-tws-api/assets/45191775/afc54fcc-8b82-439d-9017-b9a5e5327595)


Al hacer clic en el botón "Software: TWS API", accederá a un acuerdo de licencia para la fuente API. El acuerdo predeterminado no es comercial, lo que significa que la API no se puede proporcionar con software comercial; sin embargo, también está disponible un acuerdo de licencia comercial previa solicitud.

Para utilizar la API TWS Python, deberá descargar al menos la versión 9.81 o superior de la API.

Notarás que hay descargas separadas a izquierda y derecha para Windows y Mac/Unix. Para Python, el código fuente de la API es idéntico en las distribuciones de Windows y Mac/Linux. El uso de la API de Python no requiere ningún cambio en el registro de Windows, por lo que en Windows, la fuente de Python se puede obtener utilizando el instalador MSI o el archivo zip si no tiene acceso de administrador.

* ### Diferencias entre el sitio de descarga público y el repositorio privado de GitHub que tiene un código fuente de última generación

Es importante tener en cuenta que el sitio [interactivebrokers.GitHub.io](https://interactivebrokers.GitHub.io/) es el sitio público de descarga de API; sin embargo, también es posible solicitar acceso al repositorio privado de GitHub si tiene una cuenta de GitHub, que se puede abrir de forma gratuita, siguiendo las instrucciones bajo el enlace 'Beta' en la página de descarga. La fuente disponible en el repositorio privado de GitHub se conoce como versión Beta de la API. Una vez que tenga acceso al repositorio privado de GitHub

Si está familiarizado con el control de versiones de Git, es posible realizar solicitudes de extracción directamente a las fuentes de la API y plantear nuevos problemas para los desarrolladores en el sitio del repositorio de GitHub.

En Windows, después de ejecutar el instalador de API, debería haber una carpeta llamada **C:TWS API** donde está instalada la API y una carpeta para el código fuente de Python en: **C:TWS APIsourcepythonclient**.


|[Atrás](./leccion2.3.md "Atrás")|[Siguiente](./leccion4.md "Siguiente")|
|---|---:|
