🇬🇧 [English](README.md) | 🇩🇪 Deutsch | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 [Português](README.pt.md) | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

Automatisierter Trading-Bot für die [Pocket Option](https://pocketoption.com)-Plattform, hier als fertige Installationspakete verteilt — ohne Wartezeit auf die Überprüfung im Chrome Web Store, und jede vorherige Version bleibt verfügbar.

- Website: https://2bot.top/de/
- Telegram (Neuigkeiten-Kanal): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

Haben Sie einen Vorschlag oder ein Problem gefunden? Hinterlassen Sie es auf der [2bot.top-Kontaktseite](https://2bot.top/de/contact/).

Dieses Repository veröffentlicht fertige Installationsversionen der Erweiterung, sodass Sie neue Versionen installieren können, bevor sie die Überprüfung im Chrome Web Store durchlaufen, und immer eine ältere Version herunterladen können, falls Sie zurückwechseln müssen. Die Versionshistorie finden Sie in [CHANGELOG.md](CHANGELOG.md).

## Videobeispiele, wie Strategien funktionieren

| [![„none“ Strategie](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![RSI-Strategie](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![MACD-Strategie](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![Stochastische Strategie](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![Candle Streak-Strategie](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [„none“ Strategie](https://youtu.be/RYci6-vpeNQ) | [RSI-Strategie](https://youtu.be/rpceGtEW_9U) | [MACD-Strategie](https://youtu.be/gqMDqFxTA-U) | [Stochastische Strategie](https://youtu.be/eW3je_L8W3s) | [Candle Streak-Strategie](https://youtu.be/ukDODbFWKFY) |

## Installation (manuell, Entwicklermodus)

Chrome blockiert die direkte Installation von `.crx`-Dateien außerhalb des Chrome Web Store. Die einzige Möglichkeit, eine Version von hier zu installieren, ist daher das Laden als **nicht gepackte Erweiterung (unpacked)** im Entwicklermodus:

1. Gehen Sie zur Seite [Releases](../../releases) und laden Sie die `.zip`-Datei der gewünschten Version herunter (die oberste ist mit **Latest** markiert).
2. Entpacken Sie sie in einen Ordner, den Sie dauerhaft auf der Festplatte behalten möchten — löschen Sie diesen Ordner anschließend nicht, Chrome lädt die Erweiterung bei jedem Browserstart von dort.
3. Öffnen Sie `chrome://extensions` in Chrome (oder einem beliebigen Chromium-basierten Browser).
4. Aktivieren Sie den **Entwicklermodus** (Schalter oben rechts).
5. Klicken Sie auf **Entpackte Erweiterung laden** und wählen Sie den in Schritt 2 entpackten Ordner aus.
6. Die Erweiterung erscheint in Ihrer Liste und aktiviert sich automatisch auf pocketoption.com und dessen offiziellen Spiegelseiten.

### Aktualisieren auf eine neue Version

Auf diese Weise installierte, nicht gepackte Erweiterungen werden **nicht** automatisch aktualisiert. Zum Aktualisieren:

1. Laden Sie die `.zip`-Datei der neuen Version von [Releases](../../releases) herunter und entpacken Sie sie in einen **neuen** Ordner (oder überschreiben Sie den alten).
2. Wenn Sie denselben Ordner überschrieben haben: Öffnen Sie `chrome://extensions` und klicken Sie auf das Aktualisierungssymbol (↻) auf der Karte der Erweiterung.
3. Wenn Sie einen neuen Ordner verwendet haben: Entfernen Sie den alten Eintrag in `chrome://extensions` und klicken Sie erneut auf **Entpackte Erweiterung laden** für den neuen Ordner.

### Zurückkehren zu einer früheren Version

Jede veröffentlichte Version bleibt auf der Seite [Releases](../../releases) verfügbar — laden Sie die `.zip`-Datei der benötigten Version herunter und installieren Sie sie auf die gleiche Weise.

## Haftungsausschluss

Der Handel mit binären Optionen birgt ein hohes Verlustrisiko. Diese Erweiterung ist ein Automatisierungswerkzeug, das den von Ihnen konfigurierten Regeln folgt — sie stellt keine Finanzberatung dar und garantiert keinen Gewinn. Sie tragen die alleinige Verantwortung für Ihre Handelsentscheidungen.
