# animacion-vuelta-obligado

Experiencia 360° de la batalla de la Vuelta de Obligado (20 de noviembre de 1845), pensada para abrir desde el celular con un código QR en los afiches del Día de la Soberanía Nacional.

## Qué incluye

- `index.html`: la experiencia completa en un solo archivo. No necesita instalación ni compilación.
- `src/scene.js`: el código de la escena 3D tal como va dentro de `index.html`, separado para poder leerlo y editarlo.

## Cómo se usa

Al abrir la página se ve la portada; el botón **Empezar** inicia un recorrido de seis puntos:

1. Las baterías de cañones
2. Lucio N. Mansilla
3. Las cadenas
4. La flota anglo-francesa
5. El convoy mercante
6. ¿Cómo termina?

En cada punto se puede arrastrar el dedo para mirar alrededor.

## Publicarla

La página carga la librería three.js desde `cdn.jsdelivr.net`, así que necesita conexión a internet.

Sirve cualquier alojamiento de archivos estáticos (GitHub Pages, Netlify). Alojada en una dirección propia y abierta con HTTPS, además funcionan:

- el giroscopio (mover el celular para mirar), y
- la realidad aumentada: WebXR en Android con Chrome y AR Quick Look en iPhone con Safari (iOS 16.4 o más nuevo).

## Fuentes históricas

- Presidencia de la Nación, Instituto Argentino de Historia Militar: <https://www.argentina.gob.ar/node/229051> y <https://www.argentina.gob.ar/node/288911>
- Billiken, infografía de la batalla: <https://billiken.lat/wp-content/uploads/2021/11/INFOGRAFIA-Vuelta-de-Obligado-BILLIKEN.pdf>
- Wikipedia, *Battle of Vuelta de Obligado*: <https://en.wikipedia.org/wiki/Battle_of_Vuelta_de_Obligado>

Las distancias a lo largo de la costa están comprimidas para que la escena entre en cuadro; el ancho del río (unos 700 m) está a escala.
