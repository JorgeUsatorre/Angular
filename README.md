# PracticaAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


# Galería Épica

Este es un proyecto simple que muestra una galería de imágenes épicas y un contador que cuenta el número de imagenes que se han enviado.

## Que es angular?

Angular es un framework de desarrollo de aplicaciones web desarrollado y mantenido por Google. Se utiliza para construir aplicaciones web de una sola página (SPA) y aplicaciones web progresivas (PWA). Angular se basa en el lenguaje de programación TypeScript y sigue el patrón de diseño Modelo-Vista-Controlador (MVC).
## Descripción

La Galería Épica es una página web que muestra dos imágeness. Las imágenes tienen efectos de transición cuando pasas el cursor sobre ellas, lo que proporciona una experiencia interactiva al usuario. Además, hay dos contadores que cuenta el número de veces que se han enviado imagenes o fotografias a la página desde que se cargó por primera vez. Estas imagenes cambian cada vez que recargamos la pagina.
![cap.png](C:\Users\usato\OneDrive\Escritorio\PracticaAngular\src\assets\cap1.png)
![cap2.png](C:\Users\usato\OneDrive\Escritorio\PracticaAngular\src\assets\cap2.png)


## Contenido

El proyecto consta de los siguientes archivos:

- `index.html`: Este es el archivo HTML principal que contiene la estructura de la página.
- `style.css`: Este archivo CSS contiene los estilos para personalizar la apariencia de la página.
- `script.js`: Este archivo JavaScript controla el contador que se muestra en la página.

## Instrucciones de uso

Para utilizar la Galería Épica, simplemente abre el archivo `index.html` en tu navegador web. Verás las imágenes y el contador en la página. El contador se incrementará automáticamente cada segundo.

## Tecnologías utilizadas

Este proyecto utiliza HTML, CSS y JavaScript para crear una experiencia interactiva en el navegador web.

## Codigo HTML:
El código HTML se divide en las siguientes secciones:

Encabezado 'head': Define la configuración del documento, incluyendo metadatos como el conjunto de caracteres, la vista móvil y el título de la página.

Estilos 'styles': Contiene las reglas de estilo CSS para personalizar la apariencia de la página. Se utiliza una fuente específica, un fondo de imagen de circuito de Fórmula 1 y varios estilos para los contenedores, elementos y animaciones.

Cuerpo 'body': Contiene el contenido principal de la página, incluyendo el título principal, la galería de imágenes dentro de un contenedor flexible y el contador.

Script 'script': Define un script de JavaScript que incrementa el contador cada segundo y actualiza el valor mostrado en la página.

## Codigo ts
El código del componente principal de Angular se divide en las siguientes secciones:

Importaciones (import): Importa las clases necesarias de Angular, incluyendo Component y OnInit, así como el router y el componente BodyComponent.

Decorador @Component: Define el componente AppComponent con su selector, plantilla, estilos y otras configuraciones. También implementa la interfaz OnInit para realizar acciones de inicialización cuando el componente se carga.

Propiedades y Métodos: Define propiedades como title y contadorVinilos, así como el método ngOnInit() que inicializa el contador y lo incrementa cada segundo mediante un intervalo de tiempo.


