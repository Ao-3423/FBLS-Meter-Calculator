FBLS Meter Calculator

เว็บแอปคำนวณปริมาณน้ำมันจากมิเตอร์สำหรับงาน FBLS (Blend + Volume Correction)

ความสามารถ

กระจาย Blend ไป Meter 2–6 อัตโนมัติ

ปรับ LOADED_GROSS ให้รวมเท่ากับ VOL REQ

คำนวณ LOADED_NEL ด้วย VCF

คำนวณ Final Corrected Volume (MF × VCF)

ปัดค่าขึ้นทุกขั้น (Round Up)

สูตรหลัก

Blend Target = VOL REQ × Blend %

Gross (M2–M6) = Blend Target × (Raw / Sum Raw)

M1 Balance = VOL REQ − Sum(M2–M6)

NEL = GROSS × VCF

Final = Total NEL × MF

วิธีใช้

เปิดไฟล์ index.html ในเว็บเบราว์เซอร์ หรือ Deploy ผ่าน GitHub Pages

เทคโนโลยี

HTML + CSS + JavaScript (ไม่ใช้ไลบรารี)
