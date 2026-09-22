🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 [Português](README.pt.md) | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 Español | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

Bot de trading automatizado para la plataforma [Pocket Option](https://pocketoption.com), distribuido aquí como builds listos para instalar — sin esperar la revisión de la Chrome Web Store, y cada versión anterior permanece disponible.

- Sitio web: https://2bot.top/es/
- Telegram (canal de noticias): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

¿Tienes una sugerencia o encontraste un problema? Déjalo en la [página de contacto de 2bot.top](https://2bot.top/es/contact/).

Este repositorio publica versiones listas para instalar de la extensión, para que puedas instalar nuevas versiones antes de que pasen la revisión de la Chrome Web Store, y siempre puedas descargar una versión anterior si necesitas revertir. Consulta [CHANGELOG.md](CHANGELOG.md).

## Ejemplos en vídeo de cómo funcionan las estrategias

| [![estrategia "none"](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![estrategia RSI](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![Estrategia MACD](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![Estrategia estocástica](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![Estrategia de racha de velas](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [estrategia "none"](https://youtu.be/RYci6-vpeNQ) | [estrategia RSI](https://youtu.be/rpceGtEW_9U) | [Estrategia MACD](https://youtu.be/gqMDqFxTA-U) | [Estrategia estocástica](https://youtu.be/eW3je_L8W3s) | [Estrategia de racha de velas](https://youtu.be/ukDODbFWKFY) |

## Instalación (manual, Modo desarrollador)

Chrome bloquea la instalación directa de archivos `.crx` fuera de la Chrome Web Store, por lo que la única forma de instalar un build desde aquí es cargarlo como **extensión sin empaquetar (unpacked)** en Modo desarrollador:

1. Ve a la página [Releases](../../releases) y descarga el `.zip` de la versión que quieras (la primera está marcada como **Latest**).
2. Descomprímelo en una carpeta que pienses conservar en el disco — no elimines esta carpeta después, Chrome carga la extensión desde ahí cada vez que se inicia el navegador.
3. Abre `chrome://extensions` en Chrome (o cualquier navegador basado en Chromium).
4. Activa el **Modo desarrollador** (interruptor en la esquina superior derecha).
5. Haz clic en **Cargar descomprimida (Load unpacked)** y selecciona la carpeta descomprimida en el paso 2.
6. La extensión aparecerá en tu lista de extensiones y se activará automáticamente en pocketoption.com y sus espejos oficiales.

### Actualizar a una nueva versión

Las extensiones sin empaquetar instaladas de esta forma **no** se actualizan automáticamente. Para actualizar:

1. Descarga y descomprime el `.zip` de la nueva versión desde [Releases](../../releases) en una carpeta **nueva** (o sobrescribe la anterior).
2. Si sobrescribiste la misma carpeta: abre `chrome://extensions` y haz clic en el icono de recarga (↻) en la tarjeta de la extensión.
3. Si usaste una carpeta nueva: elimina la entrada antigua de la extensión en `chrome://extensions` y vuelve a hacer clic en **Cargar descomprimida** desde la nueva carpeta.

### Volver a una versión anterior

Cada versión publicada permanece disponible en la página [Releases](../../releases) — descarga el `.zip` de la versión que necesites e instálalo de la misma forma.

## Descargo de responsabilidad

El trading de opciones binarias conlleva un alto riesgo de pérdida. Esta extensión es una herramienta de automatización que sigue las reglas que configures — no constituye asesoramiento financiero ni garantiza beneficios. Eres el único responsable de tus decisiones de trading.
