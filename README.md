# Expositor Monitor AOC

Landing de una sola página para el monitor gaming AOC 24G42E (23,8″, Fast IPS, Full HD, 180 Hz). El monitor está modelado en 3D por código, se puede girar 360° arrastrándolo y, al hacer scroll, se abre por capas para enseñar cada especificación: panel, filtro de color, retroiluminación, placa, conexiones, inclinación y anclaje VESA.

**Demo:** https://titohalo3-cpu.github.io/AppWeb-Expositor-Monitor-AOC/

## Qué incluye

- Monitor 3D construido con Three.js (sin modelos externos) que gira hacia el cursor y se puede girar 360° arrastrándolo, con inercia al soltar.
- Despiece ligado al scroll con GSAP ScrollTrigger y etiquetas ancladas a cada pieza.
- Dos modos (Competitivo y Color) con una transición animada de fondo, pantalla y textos.
- Fondo animado sutil distinto para cada especificación.
- Diseño responsive y respeto de `prefers-reduced-motion`.

## Tecnologías

HTML, CSS y JavaScript en un único `index.html`, sin build. Librerías por CDN: GSAP 3.12.2 (con ScrollTrigger) y Three.js r128.

## Datos

Las especificaciones salen de la ficha oficial de AOC (aoc.com), consultada en octubre de 2026.

> Proyecto personal no oficial, sin relación con AOC. AOC es una marca de su titular. El despiece es ilustrativo y no representa la construcción interna real del monitor.
