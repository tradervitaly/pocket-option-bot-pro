🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 [Português](README.pt.md) | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 한국어 | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

[Pocket Option](https://pocketoption.com) 플랫폼용 자동 트레이딩 봇으로, Chrome 웹 스토어 심사를 기다릴 필요 없이 바로 설치 가능한 빌드 형태로 여기서 배포됩니다. 이전 모든 버전도 계속 사용할 수 있습니다.

- 웹사이트: https://2bot.top/ko/
- 텔레그램(뉴스 채널): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome 웹 스토어: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

제안 사항이 있거나 문제를 발견하셨나요? [2bot.top 문의 페이지](https://2bot.top/ko/contact/).

이 저장소는 바로 설치 가능한 확장 프로그램 버전을 게시하므로, Chrome 웹 스토어 심사를 통과하기 전에 새 버전을 설치할 수 있고, 이전 버전으로 돌아가야 할 경우 언제든지 다운로드할 수 있습니다. 버전 기록은 [CHANGELOG.md](CHANGELOG.md).

## 설치 (수동, 개발자 모드)

Chrome은 Chrome 웹 스토어 외부에서 `.crx` 파일을 직접 설치하는 것을 차단하므로, 여기서 빌드를 설치하는 유일한 방법은 개발자 모드에서 **압축해제된 확장 프로그램(unpacked)**으로 불러오는 것입니다:

1. [Releases](../../releases) 페이지로 이동하여 원하는 버전의 `.zip` 파일을 다운로드하세요 (맨 위 버전에 **Latest** 표시가 있습니다).
2. 디스크에 계속 보관할 폴더에 압축을 풉니다 — 이후 이 폴더를 삭제하지 마세요. Chrome은 브라우저가 시작될 때마다 이 폴더에서 확장 프로그램을 불러옵니다.
3. Chrome(또는 Chromium 기반의 다른 브라우저)에서 `chrome://extensions`를 엽니다.
4. **개발자 모드**를 켭니다 (오른쪽 상단의 스위치).
5. **압축해제된 확장 프로그램 로드(Load unpacked)**를 클릭하고 2단계에서 압축을 푼 폴더를 선택합니다.
6. 확장 프로그램이 목록에 나타나고 pocketoption.com 및 공식 미러 사이트에서 자동으로 활성화됩니다.

### 새 버전으로 업데이트

이 방식으로 설치된 압축해제된 확장 프로그램은 자동으로 업데이트되지 **않습니다**. 업데이트하려면:

1. [Releases](../../releases)에서 새 버전의 `.zip` 파일을 다운로드하여 **새** 폴더에 압축을 풉니다 (또는 기존 폴더를 덮어씁니다).
2. 같은 폴더를 덮어썼다면: `chrome://extensions`를 열고 확장 프로그램 카드의 새로고침 아이콘(↻)을 클릭하세요.
3. 새 폴더를 사용했다면: `chrome://extensions`에서 이전 확장 프로그램 항목을 제거하고 새 폴더에서 다시 **압축해제된 확장 프로그램 로드**를 클릭하세요.

### 이전 버전으로 되돌리기

게시된 모든 버전은 [Releases](../../releases) 페이지에서 계속 사용할 수 있습니다 — 필요한 버전의 `.zip` 파일을 다운로드하여 동일한 방법으로 설치하세요.

## 면책 조항

바이너리 옵션 거래는 높은 손실 위험을 수반합니다. 이 확장 프로그램은 사용자가 설정한 규칙을 따르는 자동화 도구일 뿐이며, 금융 자문이 아니며 수익을 보장하지 않습니다. 거래 결정에 대한 책임은 전적으로 사용자 본인에게 있습니다.
