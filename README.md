
![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)


# Módulo 1. Evaluación final

¿Qué tal? Este es el proyecto de evaluación final del módulo 1 del Bootcamp de **Programación Web** impartido por Adalab (Promo Salas). Consiste en una página web maquetada a partir de un archivo proporcionado con anterioridad en Zeplin. Su diseño es **Responsive**, es decir, enfocado a que la web pueda verse correctamente en distintos dispositivos y pantallas. Para ello se ha hecho uso de *mediaqueries* y de unidades “flexibles” como porcentajes (`%`) o *viewport width* (`vw`). De esta forma es posible su visualización tanto en versión *Mobile* (320px), versión *Tablet* (768px) y versión *Desktop* (1200px).

Como base para el proyecto se ha utilizado el *Adalab Web Starter Kit* (WSK), una plantilla de proyectos con funcionalidades preinstaladas y preconfiguradas. Éste ha sido creado en **Node** y **Gulp** e incluye un motor de plantillas **HTML**, el preprocesador **SASS** y un servidor local, que han permitido la automatización de tareas.

En el proyecto hay 3 tipos de ficheros y carpetas:
-	Ficheros que se encuentran en la raíz del repositorio y constituyen la configuración del WSK.
-	La carpeta `src/` con los ficheros de la página web como **HTML**, **CSS** e imágenes.
-	Las carpetas `public/` y `docs/`, generadas de forma automática por el kit al arrancar el proyecto y leer los ficheros contenidos en la carpeta `src/`.

Gracias al kit ha sido posible, además, dividir el proyecto en varios *partials*, incluidos en la carpeta `src/`. Al procesar dicha carpeta, como se ha comentado anteriormente, se genera un solo archivo `index.html` y `main.css` en la carpeta `public/`. Los *partials* son:
-	*Header*
-	*Hero*
-	*Main*
-	*Footer*

La versión *Mobile* de cada *partial* (HTML y CSS) se ha desarrollado en una rama diferente de **Git**, cuyo nombre coincide con el de cada uno de los *partials*.

En resumen, para la realización de la página web se ha utilizado:
-	**HTML** y **CSS** para la maquetación
-	**SASS** como preprocesador de CSS
-	**NPM** como gestor de paquetes y dependencias (WSK)
-	**Gulp**, herramienta de automatización de tareas (WSK)


¡Muchas gracias!
