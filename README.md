# FBLS Meter Calculator

เว็บแอปคำนวณปริมาณน้ำมันจากมิเตอร์สำหรับงาน FBLS (Blend + Volume Correction)

## ความสามารถ

- คำนวณการแบ่งปริมาตรระหว่าง Meter 1 (Base) และ Meter 2 (Blend)
- ปรับค่า LOADED GROSS ให้ผลรวมเท่ากับ VOL REQ
- คำนวณ LOADED NEL ด้วยค่า VCF
- คำนวณ Final Corrected Volume โดยใช้ MF × VCF
- ปัดค่าขึ้นทุกขั้นตอน (Round Up)

## สูตรหลัก

- **Blend Target** = VOL REQ × (Blend % / 100)
- **GROSS_M2** = Blend Target
- **GROSS_M1** = VOL REQ − GROSS_M2
- **NEL** = GROSS × VCF
- **Final** = Total NEL × MF

## วิธีใช้

เปิดไฟล์ `index.html` ในเว็บเบราว์เซอร์ หรือ Deploy ผ่าน GitHub Pages

## เทคโนโลยี

HTML + CSS + JavaScript (ไม่ใช้ไลบรารี)
