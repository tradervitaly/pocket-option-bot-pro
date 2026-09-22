🇬🇧 [English](README.md) | 🇩🇪 [Deutsch](README.de.md) | 🇬🇷 [Ελληνικά](README.el.md) | 🇫🇷 [Français](README.fr.md) | 🇮🇹 [Italiano](README.it.md) | 🇲🇾 [Bahasa Melayu](README.ms.md) | 🇵🇱 [Polski](README.pl.md) | 🇵🇹 [Português](README.pt.md) | 🇻🇳 [Tiếng Việt](README.vi.md) | 🇹🇭 ไทย | 🇰🇷 [한국어](README.ko.md) | 🇯🇵 [日本語](README.ja.md) | 🇷🇺 [Русский](README.ru.md) | 🇪🇸 [Español](README.es.md) | 🇮🇩 [Bahasa Indonesia](README.id.md) | 🇸🇦 [العربية](README.ar.md)

# Pocket Option Bot PRO

บอทเทรดอัตโนมัติสำหรับแพลตฟอร์ม [Pocket Option](https://pocketoption.com) เผยแพร่ที่นี่ในรูปแบบไฟล์ build พร้อมติดตั้ง — ไม่ต้องรอการตรวจสอบจาก Chrome Web Store และทุกเวอร์ชันก่อนหน้ายังคงใช้งานได้

- เว็บไซต์: https://2bot.top/th/
- ช่องข่าว Telegram: https://t.me/PO_bot_news
- YouTube: https://www.youtube.com/@PocketOptionRobot
- Chrome Web Store: https://chromewebstore.google.com/detail/pocket-option-bot-pro/fgpcopnjkdcheolcfjlkcfifiphpakla

มีข้อเสนอแนะหรือพบปัญหา? แจ้งได้ที่ [หน้าติดต่อของ 2bot.top](https://2bot.top/th/contact/).

ที่เก็บนี้เผยแพร่เวอร์ชันของส่วนขยายที่พร้อมติดตั้ง ทำให้คุณสามารถติดตั้งเวอร์ชันใหม่ได้ก่อนที่จะผ่านการตรวจสอบของ Chrome Web Store และสามารถดาวน์โหลดเวอร์ชันเก่ากว่าได้เสมอหากต้องการย้อนกลับ ดู [CHANGELOG.md](CHANGELOG.md).

## ตัวอย่างวิดีโอเกี่ยวกับวิธีการทำงานของกลยุทธ์

| [![กลยุทธ์ "none"](https://img.youtube.com/vi/RYci6-vpeNQ/hqdefault.jpg)](https://youtu.be/RYci6-vpeNQ) | [![กลยุทธ์อาร์เอสไอ](https://img.youtube.com/vi/rpceGtEW_9U/hqdefault.jpg)](https://youtu.be/rpceGtEW_9U) | [![กลยุทธ์ MACD](https://img.youtube.com/vi/gqMDqFxTA-U/hqdefault.jpg)](https://youtu.be/gqMDqFxTA-U) | [![กลยุทธ์สุ่ม](https://img.youtube.com/vi/eW3je_L8W3s/hqdefault.jpg)](https://youtu.be/eW3je_L8W3s) | [![กลยุทธ์แนวเทียน](https://img.youtube.com/vi/ukDODbFWKFY/hqdefault.jpg)](https://youtu.be/ukDODbFWKFY) |
|:---:|:---:|:---:|:---:|:---:|
| [กลยุทธ์ "none"](https://youtu.be/RYci6-vpeNQ) | [กลยุทธ์อาร์เอสไอ](https://youtu.be/rpceGtEW_9U) | [กลยุทธ์ MACD](https://youtu.be/gqMDqFxTA-U) | [กลยุทธ์สุ่ม](https://youtu.be/eW3je_L8W3s) | [กลยุทธ์แนวเทียน](https://youtu.be/ukDODbFWKFY) |

## การติดตั้ง (ด้วยตนเอง, โหมดนักพัฒนา)

Chrome ป้องกันการติดตั้งไฟล์ `.crx` โดยตรงนอก Chrome Web Store ดังนั้นวิธีเดียวที่จะติดตั้ง build จากที่นี่คือการโหลดเป็น **ส่วนขยายที่ยังไม่แพ็ก (unpacked)** ในโหมดนักพัฒนา:

1. ไปที่หน้า [Releases](../../releases) และดาวน์โหลดไฟล์ `.zip` ของเวอร์ชันที่ต้องการ (เวอร์ชันบนสุดมีป้าย **Latest**)
2. แตกไฟล์ไปยังโฟลเดอร์ที่คุณตั้งใจจะเก็บไว้ในดิสก์ — อย่าลบโฟลเดอร์นี้ในภายหลัง เนื่องจาก Chrome จะโหลดส่วนขยายจากโฟลเดอร์นี้ทุกครั้งที่เบราว์เซอร์เริ่มทำงาน
3. เปิด `chrome://extensions` ใน Chrome (หรือเบราว์เซอร์ใดก็ตามที่ใช้ Chromium)
4. เปิดใช้งาน **โหมดนักพัฒนา** (สวิตช์มุมขวาบน)
5. คลิก **โหลดส่วนขยายที่ยังไม่แพ็ก (Load unpacked)** แล้วเลือกโฟลเดอร์ที่แตกไฟล์ในขั้นตอนที่ 2
6. ส่วนขยายจะปรากฏในรายการส่วนขยายของคุณและเปิดใช้งานอัตโนมัติบน pocketoption.com และมิเรอร์ทางการของแพลตฟอร์ม

### การอัปเดตเป็นเวอร์ชันใหม่

ส่วนขยายที่ยังไม่แพ็กซึ่งติดตั้งด้วยวิธีนี้จะ **ไม่** อัปเดตอัตโนมัติ วิธีอัปเดต:

1. ดาวน์โหลดและแตกไฟล์ `.zip` ของเวอร์ชันใหม่จาก [Releases](../../releases) ไปยังโฟลเดอร์ **ใหม่** (หรือเขียนทับโฟลเดอร์เดิม)
2. หากเขียนทับโฟลเดอร์เดิม: เปิด `chrome://extensions` แล้วคลิกไอคอนโหลดซ้ำ (↻) บนการ์ดของส่วนขยาย
3. หากใช้โฟลเดอร์ใหม่: ลบรายการส่วนขยายเก่าใน `chrome://extensions` แล้วคลิก **โหลดส่วนขยายที่ยังไม่แพ็ก** อีกครั้งจากโฟลเดอร์ใหม่

### การย้อนกลับไปเวอร์ชันก่อนหน้า

ทุกเวอร์ชันที่เผยแพร่ยังคงพร้อมใช้งานที่หน้า [Releases](../../releases) — ดาวน์โหลดไฟล์ `.zip` ของเวอร์ชันที่ต้องการแล้วติดตั้งด้วยวิธีเดียวกัน

## ข้อจำกัดความรับผิดชอบ

การเทรดไบนารีออปชันมีความเสี่ยงสูงที่จะขาดทุน ส่วนขยายนี้เป็นเครื่องมืออัตโนมัติที่ทำงานตามกฎที่คุณตั้งค่า — ไม่ใช่คำแนะนำทางการเงินและไม่รับประกันผลกำไร คุณต้องรับผิดชอบแต่เพียงผู้เดียวต่อการตัดสินใจเทรดของคุณ
