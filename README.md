# StayGreen 🟢

Keep your Microsoft Teams / Slack status **green** while you step away.
A tiny Windows tray app by [Fushi Work](https://fushiwork.com) - free, no account, no tracking.

**[⬇ Download StayGreen.exe (latest)](https://github.com/fushiwork/staygreen/releases/latest/download/StayGreen.exe)**
· [All releases](https://github.com/fushiwork/staygreen/releases)
· [Website](https://fushiwork.com/en/apps/staygreen/)

> ⚠️ Use responsibly - some organizations do not allow tools like this. Check your company policy first.

## What it does

- Sends a harmless keypress (`F15`, a key no app reacts to) on an interval, so your status stays **Active**
- Stops the moment you touch the mouse or keyboard, and resumes when you step away
- Work-hours schedule: pick days, hours and breaks - it rests outside them
- Tray icon shows the state: blinking green = keeping you green · solid green = you are active · orange = off hours · gray = paused
- Thai / English, follows your Windows language
- Optional "Start with Windows" - starts quietly in the tray

## Install

1. Download `StayGreen.exe` above - it is a single portable file, no installer.
2. Put it anywhere (e.g. `Documents\Apps`) and double-click.

Requires Windows 10 or 11 (64-bit) with Microsoft Edge WebView2 (already built into Windows 11 and up-to-date Windows 10).

### "Windows protected your PC"?

StayGreen is not code-signed yet, so Windows SmartScreen may warn on first run.
Click **More info → Run anyway**. Some antivirus tools may also flag it as a false
positive, because it sends keypresses - it contains no malware.
Each release lists a SHA-256 checksum so you can verify the file:

```powershell
Get-FileHash .\StayGreen.exe -Algorithm SHA256
```

## Privacy

Everything stays on your PC. Settings live in `%APPDATA%\StayGreen`; nothing is sent anywhere.

## Pro

A supporter edition with humanized timing and an activity dashboard is a thank-you
for matcha tips - see [ko-fi.com/fushiwork](https://ko-fi.com/fushiwork).

---

## ภาษาไทย

โปรแกรมเล็กๆ บน Windows ที่ช่วยให้สถานะ Teams / Slack **เขียวอยู่ตลอด** แม้ลุกไปพัก - ฟรี ไม่ต้องสมัคร ไม่เก็บข้อมูล

**[⬇ ดาวน์โหลด StayGreen.exe (ล่าสุด)](https://github.com/fushiwork/staygreen/releases/latest/download/StayGreen.exe)**

- ส่งปุ่ม `F15` (ปุ่มที่ไม่มีโปรแกรมไหนตอบสนอง) เป็นระยะ ให้สถานะยัง Active
- หยุดทันทีที่คุณขยับเมาส์หรือพิมพ์ และกลับมาทำงานเมื่อคุณไม่อยู่
- ตั้งวันและเวลาทำงาน + ช่วงพักได้ นอกเวลาจะพักเอง
- ไฟล์เดียว ไม่ต้องติดตั้ง · ใช้กับ Windows 10/11 (64-bit)
- ถ้าขึ้น "Windows protected your PC" ให้กด **More info → Run anyway** (โปรแกรมยังไม่ได้ sign)
- ข้อมูลทั้งหมดอยู่ในเครื่องคุณ (`%APPDATA%\StayGreen`) ไม่ส่งไปไหน

> ⚠️ บางองค์กรไม่อนุญาตให้ใช้เครื่องมือแบบนี้ กรุณาตรวจสอบนโยบายของบริษัทก่อนใช้
