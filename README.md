# HOOP FURY '88 🏀

Un duelo de baloncesto arcade 8-bit de 60 segundos, hecho con Canvas 2D y Web Audio. Sin dependencias, CDN ni instalación.

**Jugar:** [Abrir HOOP FURY '88 en GitHub Pages](https://ray86-dev.github.io/8-bit-instinct/)

## Controles

- **← / →** o **A / D**: correr.
- **↑** o **W**: saltar.
- **Mantener ESPACIO**: cargar el tiro; **soltar**: lanzar. Cerca del aro, salta y suelta para hacer un dunk.
- En móvil: botones de dirección, SALTO y TIRAR. Mantén TIRAR para cargar y suéltalo para lanzar.
- **ENTER / tocar la pantalla**: empezar o reiniciar en el menú o al terminar. Botón de sonido para silenciar.

Ganas si consigues más puntos que la IA al acabarse el tiempo. Los tiros desde más allá de la línea de triple valen 3; los demás, 2. Las canastas seguidas encienden una racha. El balón suelto se puede recuperar.

## Estilo

Cancha de madera, público animado, sprites pixelados, paleta violeta/naranja arcade, red y tablero, trails, confeti y destellos al anotar. Canvas interno de 320 × 240 píxeles, escalado sin suavizado. Sonidos y música sintetizados en el navegador.

## Ejecutar localmente

Abre `index.html` en cualquier navegador moderno. También puedes servir la carpeta con `python3 -m http.server 8000` y abrir `http://localhost:8000`. El audio comienza después de una interacción por las restricciones del navegador.

## Publicación

GitHub Pages: rama `main`, carpeta `/ (root)`. El sitio solo contiene archivos estáticos.
