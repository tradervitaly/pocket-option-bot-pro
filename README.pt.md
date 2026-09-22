🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 Português | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

Bot de negociação automatizado para a plataforma [Pocket Option](https://pocketoption.com), distribuído aqui como builds prontas a instalar — sem esperar pela revisão da Chrome Web Store, e cada versão anterior permanece disponível.

- Website: https://2bot.top/pt/
- Telegram (canal de novidades): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

Tem uma sugestão ou encontrou um problema? Deixe-o na [página de contacto do 2bot.top](https://2bot.top/pt/contact/).

Este repositório publica versões prontas a instalar da extensão, para que possa instalar novas versões antes de passarem pela revisão da Chrome Web Store, e transferir sempre uma versão anterior caso precise de reverter. Consulte o [CHANGELOG.md](CHANGELOG.md).

## Exemplos de vídeo de como as estratégias funcionam

| [![estratégia "none"](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![Estratégia RSI](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![Estratégia MACD](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![Estratégia Estocástica](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![Estratégia de sequência de velas](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [estratégia "none"](https://youtu.be/RYci6-vpeNQ) | [Estratégia RSI](https://youtu.be/rpceGtEW_9U) | [Estratégia MACD](https://youtu.be/gqMDqFxTA-U) | [Estratégia Estocástica](https://youtu.be/eW3je_L8W3s) | [Estratégia de sequência de velas](https://youtu.be/ukDODbFWKFY) |

## Instalação (manual, Modo de Programador)

O Chrome bloqueia a instalação direta de ficheiros `.crx` fora da Chrome Web Store, pelo que a única forma de instalar uma build a partir daqui é carregá-la como **extensão não empacotada (unpacked)** no Modo de Programador:

1. Vá à página [Releases](../../releases) e transfira o `.zip` da versão pretendida (a mais recente está marcada como **Latest**).
2. Descompacte-o numa pasta que pretenda manter no disco — não elimine esta pasta depois, o Chrome carrega a extensão a partir dela sempre que o navegador é iniciado.
3. Abra `chrome://extensions` no Chrome (ou em qualquer navegador baseado em Chromium).
4. Ative o **Modo de Programador** (interruptor no canto superior direito).
5. Clique em **Carregar sem compactação (Load unpacked)** e selecione a pasta descompactada no passo 2.
6. A extensão aparece na sua lista de extensões e ativa-se automaticamente em pocketoption.com e nos seus espelhos oficiais.

### Atualizar para uma nova versão

As extensões não empacotadas instaladas desta forma **não** se atualizam automaticamente. Para atualizar:

1. Transfira e descompacte o `.zip` da nova versão a partir de [Releases](../../releases) para uma **nova** pasta (ou substitua a antiga).
2. Se substituiu a mesma pasta: abra `chrome://extensions` e clique no ícone de recarregar (↻) no cartão da extensão.
3. Se usou uma nova pasta: remova a entrada antiga da extensão em `chrome://extensions` e clique novamente em **Carregar sem compactação** a partir da nova pasta.

### Reverter para uma versão anterior

Cada versão publicada permanece disponível na página [Releases](../../releases) — transfira o `.zip` da versão de que precisa e instale-o da mesma forma.

## Aviso legal

A negociação de opções binárias envolve um elevado risco de perda. Esta extensão é uma ferramenta de automação que segue as regras que configura — não constitui aconselhamento financeiro nem garante lucro. É o único responsável pelas suas decisões de negociação.
