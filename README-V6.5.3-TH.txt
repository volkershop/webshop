0xVoLKER V6.5.3 — Responsive Image/UI Fix

แก้จากภาพที่แจ้ง:
1) โลโก้ 0xVoLKER บน Header มือถือไม่ถูกบีบ/ยืดอีก
2) ใช้รูป avatar วงกลมจริง แทนการ crop จาก banner แนวนอน
3) Header มือถือเปลี่ยนเป็น 2 แถว:
   - แถวบน Brand
   - แถวล่าง TH/EN, FX, Customer ID, Online ฯลฯ
   ถ้าจอเล็กมาก แถว action เลื่อนได้แนวนอน ไม่บีบของ
4) Maintenance image:
   - กรอบเป็นสี่เหลี่ยมจัตุรัส 1:1
   - รูปอยู่กึ่งกลาง
   - ไม่ zoom 1.65 เท่าอีก
   - Desktop และ Mobile ไม่บีบภาพ
5) โทรโข่งย้ายไปมุมล่างขวา ไม่ทับหน้าตัวละครมากเกินไป
6) Maintenance card บนมือถือเป็น 1 คอลัมน์และรักษาสัดส่วนรูป

วิธีใช้:
- GitHub repo webshop
- Upload index.html ตัวนี้ทับ index.html เดิม
- Upload volker-avatar-circle.png ไว้ข้าง index.html
- banner-0xvolker.png ใช้ตัวเดิมได้
- Commit
- รอ GitHub Pages 1-2 นาที
- Ctrl+F5

Backend ไม่ต้องเปลี่ยนสำหรับ UI fix นี้
