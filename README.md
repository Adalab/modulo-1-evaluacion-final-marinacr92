![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)

# Módulo 1. Evaluación final

¿Qué tal? Este es el proyecto de evaluación final del módulo 1 del Bootcamp de **Programación Web** impartido por Adalab (Promo Salas). Consiste en una página web maquetada a partir de un archivo proporcionado con anterioridad en Zeplin. Su diseño es **Responsive**, es decir, enfocado a que la web pueda verse correctamente en distintos dispositivos y pantallas. Para ello se ha hecho uso de _mediaqueries_ y de unidades “flexibles” como porcentajes (`%`) o _viewport width_ (`vw`). De esta forma es posible su visualización tanto en versión _Mobile_ (320px), versión _Tablet_ (768px) y versión _Desktop_ (1024px).

Como base para el proyecto se ha utilizado el _Adalab Web Starter Kit_ (WSK), una plantilla de proyectos con funcionalidades preinstaladas y preconfiguradas. Éste ha sido creado en **Node** y **Gulp** e incluye un motor de plantillas **HTML**, el preprocesador **SASS** y un servidor local, que han permitido la automatización de tareas.

En el proyecto hay 3 tipos de ficheros y carpetas:

- Ficheros que se encuentran en la raíz del repositorio y constituyen la configuración del WSK.
- La carpeta `src/` con los ficheros de la página web como **HTML**, **CSS** e imágenes.
- Las carpetas `public/` y `docs/`, generadas de forma automática por el kit al arrancar el proyecto y leer los ficheros contenidos en la carpeta `src/`.

Gracias al kit ha sido posible, además, dividir el proyecto en varios _partials_, incluidos en la carpeta `src/`. Al procesar dicha carpeta, como se ha comentado anteriormente, se genera un solo archivo `index.html` y `main.css` en la carpeta `public/`. Los _partials_ son:

- _Header_
- _Hero_
- _Main_
- _Footer_

La versión _Mobile_ de cada _partial_ (HTML y CSS) se ha desarrollado en una rama diferente de **Git**, cuyo nombre coincide con el de cada uno de los _partials_.

En resumen, para la realización de la página web se ha utilizado:

- **HTML** y **CSS** para la maquetación
- **SASS** como preprocesador de CSS
- **NPM** como gestor de paquetes y dependencias (WSK)
- **Gulp**, herramienta de automatización de tareas (WSK)

¡Muchas gracias!
