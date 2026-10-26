# Equilibrio

Juego de apilar objetos con una grúa. Soltá cada pieza, hacé crecer la torre y sobreviví al viento y a los temblores. Si algo se cae, se terminó.

**Jugar:** abrí `index.html` en el navegador, o publicalo con GitHub Pages (ver abajo).

## Controles
- **Tocar la pantalla / Espacio:** soltar la pieza
- **R:** rotar · **C:** cambiar por la siguiente · **G:** pegamento (se compran en la tienda)
- **Esc o P:** pausa

## Qué incluye
- Menú con música generada en el navegador, ajustes de volumen y pausa
- Monedas por partida y tienda de mejoras y habilidades
- Fondo que cambia con la altura, hasta el espacio
- Vibración en celular y cámara lenta al caer

El récord, las monedas y las compras se guardan en el navegador de cada persona.

## Publicar en GitHub Pages
1. Creá un repositorio nuevo en GitHub (por ejemplo `equilibrio`).
2. Subí estos archivos a la raíz del repositorio.
3. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Esperá un minuto. El juego queda en `https://TU-USUARIO.github.io/equilibrio/`.

## Sin conexión
El juego carga la física ([Matter.js 0.19.0](https://brm.io/matter-js/)) y las tipografías desde internet. Para que la física funcione sin conexión, bajá `matter.min.js` de esa versión y ponelo junto a `index.html`: el juego lo usa solo si la descarga desde internet falla.
