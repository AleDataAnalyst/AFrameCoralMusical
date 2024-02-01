# Experiencia Inmersiva Coral Musical con A-Frame, Howler.js y Sonic Pi

## Descripción

Este proyecto es una experiencia inmersiva y de realidad virtual (VR) que utiliza A-Frame para la creación de la escena 3D, Howler.js para la gestión del sonido y Sonic Pi para la generación de música.

La escena consiste en un entorno submarino con diferentes tipos de corales, algas y un caballito de mar. Cada uno de estos elementos representa un instrumento musical diferente (violín, viola, violoncello, tuba, flauta). La cámara está fija pero puede rotar para explorar la escena.

## Cómo usar

1. Abre el archivo `index.html` en tu navegador.
2. Utiliza el ratón para rotar la cámara y explorar la escena.
3. Haz clic en los diferentes elementos de la escena para reproducir los sonidos correspondientes.

## Dependencias

- [A-Frame](https://aframe.io/): A-Frame es una biblioteca web para la construcción de experiencias de realidad virtual.
- [Howler.js](https://howlerjs.com/): Howler.js es una biblioteca de audio moderna que ayuda a trabajar con sonido en la web.
- [Sonic Pi](https://sonic-pi.net/): Sonic Pi es un entorno de codificación de música en vivo, que permite crear sonidos con código en tiempo real.

## Detalles del paquete

```json
{
    "name": "aframe-musical-reef",
    "description": "Corales Musicales con A-Frame. Proyecto WebVR.",
    "version": "0.3.0",
    "license": "MIT",
    "scripts": {
        "start": "budo --live --verbose --port 3000 --open",
        "deploy": "ghpages",
        "ghpages": "ghpages"
    },
    "devDependencies": {
        "budo": "^7.0.0",
        "ghpages": "0.0.3"
    },
    "keywords": [
        "aframe",
        "aframe-example",
        "aframe-boilerplate",
        "aframe-scene",
        "webvr",
        "vr"
    ],
    "dependencies": {
        "aframe-physics-system": "^4.0.2",
        "aframe-teleport-controls": "^0.3.1",
        "howler": "^2.2.4"
    }
}
```

## Contribuir

Las contribuciones son bienvenidas. Por favor, abre un problema o realiza un pull request con tus cambios.

## Contacto

Si tienes alguna pregunta o comentario, por favor, ponte en contacto con el autor del proyecto.

## Reconocimientos

Gracias a todos los que han contribuido a este proyecto y a los creadores de A-Frame, Howler.js y Sonic Pi por hacer posible este tipo de experiencias inmersivas.
