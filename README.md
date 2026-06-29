# iPhone Icon Fix

แก้ปัญหาไอคอนไม่ขึ้นบน iPhone

เพิ่มไฟล์:
- icons/apple-touch-icon-180.png

แก้:
- index.html เพิ่ม apple-touch-icon แบบ explicit sizes
- sw.js เปลี่ยน cache เป็น minimal-life-tracker-v3 และ cache icon 180

หลังอัปโหลด:
1. รอ GitHub Pages deploy
2. เปิด Safari เข้า URL ของเว็บ แล้วเติม /icons/apple-touch-icon-180.png?v=3 เพื่อตรวจว่ารูปขึ้น
3. ลบ shortcut เดิมจาก Home Screen
4. Add to Home Screen ใหม่
