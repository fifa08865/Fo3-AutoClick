<div align="center">

# FO3 Auto League

**โปรแกรมช่วยเล่นลีก (VS COM) ใน FIFA Online 3 TH อัตโนมัติ — ใช้ฟรี**
**Free auto-player for the League (VS COM) mode in FIFA Online 3 TH**

[![Latest release](https://img.shields.io/github/v/release/fifa08865/Fo3-AutoClick?label=download&style=for-the-badge)](https://github.com/fifa08865/Fo3-AutoClick/releases/latest)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge)
![Languages](https://img.shields.io/badge/TH%20%7C%20EN%20%7C%20VI-supported-F5C400?style=for-the-badge)

[ไทย](#ไทย) · [English](#english) · [Tiếng Việt](#tiếng-việt)

</div>

---

## ไทย

### ดาวน์โหลด
ไปที่หน้า **[Releases](https://github.com/fifa08865/Fo3-AutoClick/releases/latest)** แล้วโหลดไฟล์ `FO3AutoLeague-vX.X.zip` แตกไฟล์ แล้วดับเบิลคลิก `FO3AutoLeague.exe`

### คุณสมบัติ
- กดปุ่มในลูปลีก VS COM ให้เองทั้งหมด: จำลองแข่ง → ดูผล → รับรางวัล → สุ่มเลือก → ต่อไป
- ทำงานเบื้องหลัง ไม่ขยับเมาส์จริงของคุณ
- ทำงานได้หลายขนาดหน้าต่างเกม (ปรับขนาดปุ่มตามความสูงของหน้าต่างอัตโนมัติ)
- จัดการหน้าต่างต่อสัญญา (เลือกต่อสัญญาอัตโนมัติได้ ปิดเป็นค่าเริ่มต้น) และเลือกโหมดมาสเตอร์ลีกให้
- จำกัดจำนวนรอบได้ / ซ่อนหน้าต่างเกม / ธีมสว่าง-มืด / ภาษาไทย อังกฤษ เวียดนาม
- หยุดฉุกเฉินด้วย **F8**

### ขนาดหน้าจอเกมที่แนะนำ

> **เปิดเกมแบบ "หน้าต่าง" (Windowed) เท่านั้น — ไม่แนะนำและไม่รองรับ Full Screen**

โปรแกรมคำนวณขนาดปุ่มจาก **ความสูง** ของหน้าต่างเกม ขนาดต่อไปนี้ผ่านการทดสอบกับภาพจากเกมจริงและแม่นยำที่สุด:

| อันดับ | ขนาดหน้าต่างเกม | หมายเหตุ |
|:--:|:--|:--|
| 1 | **1280 × 960** | แนะนำที่สุด สัดส่วน 4:3 ปุ่มชัด จับแม่น และอ่านภาพเร็ว |
| 2 | **1024 × 768** | เหมาะกับจอเล็ก/โน้ตบุ๊ก สัดส่วน 4:3 |
| 3 | **1920 × 1080** (หน้าต่าง) | สำหรับจอใหญ่ ถ้าไม่ต้องการเกมขนาดเล็ก |

เคล็ดลับ
- ใช้สัดส่วน **4:3** (กว้าง:สูง) ถ้าได้ ถ้าหน้าต่างแคบกว่า 4:3 ขอบขวาของเกมจะถูกตัดและปุ่มบางปุ่มอาจมองไม่เห็น
- ไม่ต้องตั้งความละเอียด Windows ใหม่ แค่ปรับขนาดหน้าต่างเกม
- ระหว่างทำงาน **อย่าย่อ (minimize) หน้าต่างเกม** ให้ใช้สวิตช์ "ซ่อนหน้าต่างเกม" ในโปรแกรมแทน

### วิธีใช้
1. เปิดเกมแบบหน้าต่าง ตั้งขนาดตามตารางด้านบน แล้วเข้าไปที่หน้าลีก
2. ดับเบิลคลิก `FO3AutoLeague.exe` แล้วกด **Yes** ที่หน้าต่าง UAC (เปิดครั้งแรกอาจรอสักครู่)
3. เลือกภาษา แล้วกด **เริ่มทำงาน** หรือกด **F8** (กด F8 อีกครั้งเพื่อหยุด)

### คำถามที่พบบ่อย
- **ทำไมต้องกด Yes ที่ UAC?** เกมรันด้วยสิทธิ์ผู้ดูแลระบบ โปรแกรมจึงต้องใช้สิทธิ์เดียวกันเพื่อส่งการกดไปที่เกมได้
- **Windows SmartScreen/แอนตี้ไวรัสเตือน?** โปรแกรมไม่ได้ลงชื่อรับรอง (code signing) จึงอาจมีคำเตือน ตรวจไฟล์ได้ด้วยค่า SHA-256 ในหน้า Release
- **ถอนการติดตั้ง?** ลบไฟล์ `.exe` และโฟลเดอร์ `%APPDATA%\FO3AutoLeague`
- **บอทค้างที่หน้าใดหน้าหนึ่ง?** แจ้งใน [Issues](https://github.com/fifa08865/Fo3-AutoClick/issues) พร้อมขนาดหน้าต่างเกมและหน้าที่ค้าง

---

## English

### Download
Go to **[Releases](https://github.com/fifa08865/Fo3-AutoClick/releases/latest)**, download `FO3AutoLeague-vX.X.zip`, extract it and double-click `FO3AutoLeague.exe`.

### Features
- Plays the whole VS COM league loop for you: simulate match → results → rewards → random pick → next
- Works in the background; your real mouse is never moved
- Adapts to different game window sizes (button size follows the window height)
- Handles the contract dialog (optional auto-renew, OFF by default) and selects Master League mode
- Round limit, hide-game switch, light/dark theme, Thai / English / Vietnamese UI
- Emergency stop with **F8**

### Recommended game window size

> **Run the game in Windowed mode only — Full Screen is not recommended and not supported.**

The scale is derived from the game window **height**. These three sizes were verified on real game captures and are the most accurate:

| Rank | Game window size | Notes |
|:--:|:--|:--|
| 1 | **1280 × 960** | Best choice. 4:3, sharp buttons, accurate and fast detection |
| 2 | **1024 × 768** | Good for laptops / small screens. 4:3 |
| 3 | **1920 × 1080** (windowed) | For large monitors |

Tips
- Prefer a **4:3** window. A window narrower than 4:3 clips the right edge of the game and some buttons may be hidden.
- You do not need to change the Windows resolution, just resize the game window.
- **Do not minimize the game window** while running; use the "Hide game window" switch instead.

### Quick start
1. Open the game in windowed mode at one of the sizes above and go to the League page.
2. Double-click `FO3AutoLeague.exe` and click **Yes** on the UAC prompt (the first start may take a moment).
3. Pick your language, then click **Start** or press **F8** (press F8 again to stop).

### FAQ
- **Why the UAC prompt?** The game runs as administrator, so the program needs the same rights to send clicks to it.
- **SmartScreen / antivirus warning?** The executable is not code-signed, so a warning is possible. Verify the download with the SHA-256 on the Release page.
- **Uninstall?** Delete the `.exe` and the `%APPDATA%\FO3AutoLeague` folder.
- **Stuck on a screen?** Open an [Issue](https://github.com/fifa08865/Fo3-AutoClick/issues) with your window size and the screen it stuck on.

---

## Tiếng Việt

**Tải về:** vào **[Releases](https://github.com/fifa08865/Fo3-AutoClick/releases/latest)**, tải `FO3AutoLeague-vX.X.zip`, giải nén rồi chạy `FO3AutoLeague.exe` (bấm **Yes** ở cửa sổ UAC).

**Kích thước cửa sổ game khuyến nghị** — chỉ dùng chế độ **cửa sổ**, không khuyến nghị toàn màn hình:

| Hạng | Kích thước | Ghi chú |
|:--:|:--|:--|
| 1 | **1280 × 960** | Tốt nhất, tỉ lệ 4:3 |
| 2 | **1024 × 768** | Phù hợp màn hình nhỏ / laptop |
| 3 | **1920 × 1080** (cửa sổ) | Cho màn hình lớn |

Nên dùng tỉ lệ 4:3. Đừng thu nhỏ (minimize) cửa sổ game, hãy dùng nút "Ẩn cửa sổ game". Nhấn **F8** để bắt đầu / dừng.

---

## Disclaimer

This is a closed-source program by an independent developer, distributed free of charge as a compiled executable. It is not affiliated with or endorsed by the developer or operator of FIFA Online 3. Using automation tools may be against the game's terms of service; use at your own risk.

โปรแกรมนี้พัฒนาโดยผู้พัฒนาอิสระ ไม่ได้เกี่ยวข้องกับผู้พัฒนาหรือผู้ให้บริการ FIFA Online 3 การใช้โปรแกรมอัตโนมัติอาจขัดกับข้อกำหนดของเกม โปรดใช้ด้วยความเข้าใจและรับความเสี่ยงเอง

## License

Copyright (c) 2026 FO3 Auto League. All rights reserved. Free for personal use; redistribution of modified copies, reverse engineering and resale are not permitted. See [LICENSE](LICENSE).
