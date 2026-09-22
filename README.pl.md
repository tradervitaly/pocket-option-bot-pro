🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 Polski | 🇵🇹 [Português](README.pt.md) | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

Bot do automatycznego handlu na platformie [Pocket Option](https://pocketoption.com), dystrybuowany tutaj jako gotowe do instalacji buildy — bez czekania na weryfikację w Chrome Web Store, a każda poprzednia wersja pozostaje dostępna.

- Strona internetowa: https://2bot.top/pl/
- Telegram (kanał z nowościami): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

Masz sugestię lub znalazłeś problem? Zostaw ją na [stronie kontaktowej 2bot.top](https://2bot.top/pl/contact/).

To repozytorium publikuje gotowe do instalacji wersje rozszerzenia, dzięki czemu możesz zainstalować nowe wersje, zanim przejdą weryfikację w Chrome Web Store, i zawsze pobrać starszą wersję, jeśli potrzebujesz się wycofać. Historię wersji znajdziesz w [CHANGELOG.md](CHANGELOG.md).

## Przykłady wideo działania strategii

| [![strategia „none”.](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![Strategia RSI](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![Strategia MACD](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![Strategia stochastyczna](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![Strategia smug świecowych](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [strategia „none”.](https://youtu.be/RYci6-vpeNQ) | [Strategia RSI](https://youtu.be/rpceGtEW_9U) | [Strategia MACD](https://youtu.be/gqMDqFxTA-U) | [Strategia stochastyczna](https://youtu.be/eW3je_L8W3s) | [Strategia smug świecowych](https://youtu.be/ukDODbFWKFY) |

## Instalacja (ręczna, Tryb dewelopera)

Chrome blokuje bezpośrednią instalację plików `.crx` spoza Chrome Web Store, więc jedynym sposobem na zainstalowanie buildu stąd jest wczytanie go jako **rozszerzenia niespakowanego (unpacked)** w Trybie dewelopera:

1. Przejdź na stronę [Releases](../../releases) i pobierz plik `.zip` żądanej wersji (najwyższa jest oznaczona jako **Latest**).
2. Rozpakuj go do folderu, który zamierzasz zachować na dysku — nie usuwaj tego folderu później, Chrome wczytuje z niego rozszerzenie przy każdym uruchomieniu przeglądarki.
3. Otwórz `chrome://extensions` w Chrome (lub dowolnej przeglądarce opartej na Chromium).
4. Włącz **Tryb dewelopera** (przełącznik w prawym górnym rogu).
5. Kliknij **Wczytaj rozpakowane (Load unpacked)** i wybierz folder rozpakowany w kroku 2.
6. Rozszerzenie pojawi się na liście rozszerzeń i aktywuje się automatycznie na pocketoption.com i jego oficjalnych lustrach.

### Aktualizacja do nowej wersji

Rozszerzenia niespakowane zainstalowane w ten sposób **nie** aktualizują się automatycznie. Aby zaktualizować:

1. Pobierz i rozpakuj plik `.zip` nowej wersji z [Releases](../../releases) do **nowego** folderu (lub nadpisz stary).
2. Jeśli nadpisałeś ten sam folder: otwórz `chrome://extensions` i kliknij ikonę odświeżania (↻) na karcie rozszerzenia.
3. Jeśli użyłeś nowego folderu: usuń stary wpis rozszerzenia w `chrome://extensions` i ponownie kliknij **Wczytaj rozpakowane** z nowego folderu.

### Powrót do poprzedniej wersji

Każda opublikowana wersja pozostaje dostępna na stronie [Releases](../../releases) — pobierz plik `.zip` potrzebnej wersji i zainstaluj go w ten sam sposób.

## Zastrzeżenie

Handel opcjami binarnymi wiąże się z wysokim ryzykiem straty. To rozszerzenie jest narzędziem do automatyzacji, które postępuje zgodnie z regułami, które konfigurujesz — nie stanowi porady finansowej i nie gwarantuje zysku. Ponosisz wyłączną odpowiedzialność za swoje decyzje handlowe.
