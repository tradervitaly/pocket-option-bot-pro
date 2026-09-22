🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 [Português](README.pt.md) | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 日本語 | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

[Pocket Option](https://pocketoption.com)プラットフォーム向けの自動トレーディングボットです。ここではChromeウェブストアの審査を待つことなく、すぐにインストールできるビルドとして配布されており、過去のすべてのバージョンも引き続き利用できます。

- ウェブサイト: https://2bot.top/ja/
- Telegram(ニュースチャンネル): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chromeウェブストア: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

ご提案や不具合を発見された場合は、 [2bot.topのお問い合わせページ](https://2bot.top/ja/contact/).

このリポジトリでは、すぐにインストールできる拡張機能のバージョンを公開しています。そのため、Chromeウェブストアの審査を通過する前に新しいバージョンをインストールでき、必要であればいつでも以前のバージョンをダウンロードして戻すことができます。バージョン履歴は [CHANGELOG.md](CHANGELOG.md).

## 戦略がどのように機能するかを示すビデオの例

| [![「何もしない」戦略](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![RSI戦略](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![MACD戦略](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![確率的戦略](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![キャンドルストリーク戦略](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [「何もしない」戦略](https://youtu.be/RYci6-vpeNQ) | [RSI戦略](https://youtu.be/rpceGtEW_9U) | [MACD戦略](https://youtu.be/gqMDqFxTA-U) | [確率的戦略](https://youtu.be/eW3je_L8W3s) | [キャンドルストリーク戦略](https://youtu.be/ukDODbFWKFY) |

## インストール方法(手動、デベロッパーモード)

Chromeウェブストア以外から`.crx`ファイルを直接インストールすることはChromeによってブロックされています。そのため、ここからビルドをインストールする唯一の方法は、デベロッパーモードで**パッケージ化されていない拡張機能(unpacked)**として読み込むことです:

1. [Releases](../../releases)ページに移動し、必要なバージョンの`.zip`ファイルをダウンロードします(一番上が**Latest**と表示されています)。
2. ディスク上に保持しておくフォルダに解凍します — その後このフォルダを削除しないでください。Chromeはブラウザ起動のたびにこのフォルダから拡張機能を読み込みます。
3. Chrome(または他のChromiumベースのブラウザ)で`chrome://extensions`を開きます。
4. **デベロッパーモード**を有効にします(右上のスイッチ)。
5. **パッケージ化されていない拡張機能を読み込む(Load unpacked)**をクリックし、手順2で解凍したフォルダを選択します。
6. 拡張機能が一覧に表示され、pocketoption.comおよびその公式ミラーで自動的に有効化されます。

### 新しいバージョンへの更新

この方法でインストールされたパッケージ化されていない拡張機能は自動的に更新され**ません**。更新するには:

1. [Releases](../../releases)から新しいバージョンの`.zip`をダウンロードし、**新しい**フォルダに解凍します(または既存のフォルダを上書きします)。
2. 同じフォルダを上書きした場合: `chrome://extensions`を開き、拡張機能カードの再読み込みアイコン(↻)をクリックします。
3. 新しいフォルダを使用した場合: `chrome://extensions`で古い拡張機能のエントリを削除し、新しいフォルダから再度**パッケージ化されていない拡張機能を読み込む**をクリックします。

### 以前のバージョンに戻す

公開されたすべてのバージョンは[Releases](../../releases)ページで引き続き利用可能です — 必要なバージョンの`.zip`をダウンロードし、同じ方法でインストールしてください。

## 免責事項

バイナリオプション取引には高い損失リスクが伴います。この拡張機能は、設定したルールに従って動作する自動化ツールであり、金融アドバイスではなく、利益を保証するものでもありません。取引の判断についてはすべてご自身の責任となります。
