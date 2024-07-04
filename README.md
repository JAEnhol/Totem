# Totem Entrada
Colocar un widget en cabecera con valor de acciones en Bolsa con actualización automática
y un banner debajo con una noticia

## Como se crea la web
si ponemos la ruta a la imagen del banner no funciona en el Android (no se que ruta hay que poner)
Se comprime la imagen que envia MKT y se pone en BASE64

## URLs para imagen banner
https://www.base64-image.de/

https://www.iloveimg.com/resize-image

Para determinar el tamaño de la imagen que debe encajar en el 78% restante del alto de tu dispositivo, seguimos estos pasos:

1. **Determinar el alto total de la pantalla:**
   El dispositivo tiene una resolución de \(1271 \times 2259\) píxeles, donde \(2259\) píxeles es el alto total.

2. **Calcular el 22% del alto que está ocupado:**
   \[
   2259 \times 0.22 = 497 \text{ píxeles}
   \]

3. **Calcular el alto restante (78% del alto total):**
   \[
   2259 - 497 = 1762 \text{ píxeles}
   \]

Por lo tanto, el alto disponible para la imagen es \(1762\) píxeles. La imagen debe tener el mismo ancho que el dispositivo (1271 píxeles) para encajar perfectamente en el área disponible. Así, las dimensiones de la imagen deben ser:

\[
1271 \text{ píxeles} \times 1762 \text{ píxeles}
\]
