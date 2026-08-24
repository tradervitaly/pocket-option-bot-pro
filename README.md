# Pocket Option Bot PRO

Automated trading bot for the [Pocket Option](https://pocketoption.com) platform, distributed here as ready-to-install
builds — no Chrome Web Store review wait, and every previous version stays available.

- Website: https://2bot.top
- Telegram (news channel): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

Have a suggestion or found an issue? Leave it on the [2bot.top contact page](https://2bot.top/contact/).

This repository publishes ready-to-install releases of the extension, so you can install new versions before they
pass Chrome Web Store review, and always download an older release if you need to roll back. See
[CHANGELOG.md](CHANGELOG.md) for the version history.

## Installation (manual, Developer Mode)

Chrome blocks installing `.crx` files directly outside the Chrome Web Store, so the only way to install a build from
here is by loading it as an **unpacked extension** in Developer Mode:

1. Go to the [Releases](../../releases) page and download the `.zip` of the version you want (the top one is marked
   **Latest**).
2. Unzip it into a folder you intend to keep on disk — do not delete this folder afterwards, Chrome loads the
   extension from it every time the browser starts.
3. Open `chrome://extensions` in Chrome (or any Chromium-based browser).
4. Turn on **Developer mode** (toggle in the top-right corner).
5. Click **Load unpacked** and select the folder you unzipped in step 2.
6. The extension appears in your extensions list and activates automatically on pocketoption.com and its official
   mirrors.

### Updating to a new version

Unpacked extensions installed this way do **not** auto-update. To update:

1. Download and unzip the new version's `.zip` from [Releases](../../releases) into a **new** folder (or overwrite
   the old one).
2. If you overwrote the same folder: open `chrome://extensions` and click the reload icon (↻) on the extension's
   card.
3. If you used a new folder: remove the old extension entry in `chrome://extensions` and **Load unpacked** again
   from the new folder.

### Reverting to a previous version

Every published version stays available on the [Releases](../../releases) page — download the `.zip` for the version
you need and load it the same way.

## Disclaimer

Binary options trading carries a high risk of loss. This extension is an automation tool that follows the rules you
configure — it is not financial advice and does not guarantee profit. You are solely responsible for your trading
decisions.
