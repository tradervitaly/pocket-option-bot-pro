🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 [Português](README.pt.md) | 🇻🇳 Tiếng Việt | 🇹🇭 [ไทย](README.th.md) | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

Bot giao dịch tự động cho nền tảng [Pocket Option](https://pocketoption.com), được phân phối tại đây dưới dạng các bản build sẵn sàng cài đặt — không cần chờ Chrome Web Store duyệt, và mọi phiên bản trước đó vẫn luôn khả dụng.

- Trang web: https://2bot.top/vi/
- Telegram (kênh tin tức): https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

Có góp ý hoặc phát hiện sự cố? Hãy để lại trên [trang liên hệ của 2bot.top](https://2bot.top/vi/contact/).

Kho lưu trữ này phát hành các phiên bản sẵn sàng cài đặt của tiện ích mở rộng, nhờ đó bạn có thể cài đặt phiên bản mới trước khi chúng được Chrome Web Store duyệt, và luôn có thể tải về phiên bản cũ hơn nếu cần quay lại. Xem [CHANGELOG.md](CHANGELOG.md).

## Video ví dụ về cách hoạt động của chiến lược

| [![chiến lược “none”](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![chiến lược RSI](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![Chiến lược MACD](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![Chiến lược ngẫu nhiên](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![Chiến lược chuỗi nến](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [chiến lược “none”](https://youtu.be/RYci6-vpeNQ) | [chiến lược RSI](https://youtu.be/rpceGtEW_9U) | [Chiến lược MACD](https://youtu.be/gqMDqFxTA-U) | [Chiến lược ngẫu nhiên](https://youtu.be/eW3je_L8W3s) | [Chiến lược chuỗi nến](https://youtu.be/ukDODbFWKFY) |

## Cài đặt (thủ công, Chế độ nhà phát triển)

Chrome chặn việc cài đặt trực tiếp file `.crx` bên ngoài Chrome Web Store, vì vậy cách duy nhất để cài đặt một bản build từ đây là tải nó lên dưới dạng **tiện ích chưa đóng gói (unpacked)** trong Chế độ nhà phát triển:

1. Vào trang [Releases](../../releases) và tải về file `.zip` của phiên bản bạn muốn (phiên bản trên cùng được đánh dấu **Latest**).
2. Giải nén vào một thư mục bạn dự định giữ lại trên ổ đĩa — đừng xóa thư mục này sau đó, vì Chrome sẽ tải tiện ích từ đó mỗi khi trình duyệt khởi động.
3. Mở `chrome://extensions` trong Chrome (hoặc bất kỳ trình duyệt nào dựa trên Chromium).
4. Bật **Chế độ nhà phát triển** (công tắc ở góc trên bên phải).
5. Nhấp vào **Tải tiện ích chưa đóng gói (Load unpacked)** và chọn thư mục đã giải nén ở bước 2.
6. Tiện ích sẽ xuất hiện trong danh sách tiện ích của bạn và tự động kích hoạt trên pocketoption.com cùng các trang gương chính thức của nó.

### Cập nhật lên phiên bản mới

Các tiện ích chưa đóng gói được cài đặt theo cách này sẽ **không** tự động cập nhật. Để cập nhật:

1. Tải về và giải nén file `.zip` của phiên bản mới từ [Releases](../../releases) vào một thư mục **mới** (hoặc ghi đè lên thư mục cũ).
2. Nếu bạn ghi đè lên cùng thư mục: mở `chrome://extensions` và nhấp vào biểu tượng tải lại (↻) trên thẻ tiện ích.
3. Nếu bạn dùng thư mục mới: xóa mục tiện ích cũ trong `chrome://extensions` và nhấp lại **Tải tiện ích chưa đóng gói** từ thư mục mới.

### Quay lại phiên bản trước

Mọi phiên bản đã phát hành đều luôn khả dụng trên trang [Releases](../../releases) — tải về file `.zip` của phiên bản bạn cần và cài đặt theo cách tương tự.

## Tuyên bố miễn trừ trách nhiệm

Giao dịch quyền chọn nhị phân tiềm ẩn rủi ro thua lỗ cao. Tiện ích này là công cụ tự động hóa tuân theo các quy tắc bạn cấu hình — nó không phải là lời khuyên tài chính và không đảm bảo lợi nhuận. Bạn hoàn toàn chịu trách nhiệm về các quyết định giao dịch của mình.
