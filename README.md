<p align="center"><img src="logo.webp" alt="SpeedScribe" width="520"></p>

# SpeedScribe

*De la voz al texto y a los subtítulos, en español e inglés.*

Página web para **transcribir audio a texto**, **traducir entre español e inglés** y **crear subtítulos (.srt) para videos**. Funciona desde el navegador, sin instalar nada.

## Qué hace

- **Grabar en vivo:** dicta y el texto aparece mientras hablas (requiere Google Chrome e internet).
- **Cargar un audio grabado:** entrevistas, notas de voz de WhatsApp, mp3, m4a, wav, etc.
- **Subtítulos para video:** saca el audio del video, crea los subtítulos con sus tiempos, los muestra encima del video para revisarlos y permite descargarlos en .srt para CapCut, YouTube o Facebook.
- **Traducir:** español ↔ inglés, tanto el texto como los subtítulos (con los mismos tiempos).
- **Copiar, compartir y descargar** el resultado como .txt o .srt.

## Privacidad y costo

Por defecto, la transcripción de archivos y videos usa **Whisper dentro del navegador**: es gratis, no necesita clave y **el audio no sale de la computadora**. La primera vez se descarga el modelo de voz (100–300 MB según el modelo elegido en Ajustes) y luego queda guardado en el navegador.

> ⚠️ Nunca escribas claves de API ni correos dentro de los archivos de este repositorio. Si se usan, se ingresan en la sección **Ajustes** de la página y se guardan solo en el navegador de cada persona.

## Cómo publicarla en GitHub Pages

1. Sube todos los archivos de esta carpeta (`index.html`, `README.md`, `logo.webp`, `manifest.webmanifest` y los íconos `.png`) a la rama `main` de este repositorio.
2. Ve a **Settings > Pages**.
3. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guarda.
4. Después de uno o dos minutos aparecerá la dirección: `https://TU-USUARIO.github.io/voz-a-texto-wellkind/`

Para actualizar la página, sube el nuevo `index.html` encima del anterior.

## Instalarla como app en el teléfono

- **Android (Chrome):** abre la página, toca el menú ⋮ y elige **Instalar app** o **Agregar a la pantalla principal**.
- **iPhone (Safari):** abre la página, toca el botón **Compartir** y elige **Agregar a pantalla de inicio**.

Aparecerá el ícono de SpeedScribe como una app más.

## Recomendaciones de uso

- Usa **Google Chrome en computadora** para mejores resultados.
- Modelo **Preciso** para computadora; modelo **Rápido** para teléfono o computadoras lentas.
- Con el modelo gratuito, un video de 10 minutos puede tardar varios minutos en procesarse. No cierres la pestaña mientras trabaja.
- Revisa siempre la transcripción y la traducción antes de publicarlas o enviarlas a donantes.
- Al corregir un .srt, cambia solo el texto; no borres las líneas de tiempo (`-->`).

