# ผลตรวจโปรโมชั่น 393 แพ็กเกจ — 26 กันยายน 2569

- ตัวเลขที่เทียบตรง: 333 แพ็กเกจ
- ต้องยืนยันหลักฐาน: 52 แพ็กเกจ
- คงเดิมตามผู้ใช้: 6 แพ็กเกจ
- แก้แล้ว: 2 แพ็กเกจ

## ขอบเขตและข้อจำกัด

- numeric-match คือฟิลด์ตัวเลขที่เทียบตรง ไม่ใช่รับรองสต็อก สิทธิ์ขาย พื้นที่ติดตั้ง ของแถม หรือข้อความทุกส่วน
- ข้อมูล parser ไม่ใช้เลื่อนสถานะ verified อัตโนมัติ; baseline ของรายการที่ยังไม่ได้รับรองยังคงล็อกอยู่
- ยึด PDF ล่าสุดเมื่อมีแถวชัดเจน; Excel ใช้สำหรับ 3Y/OBS/รุ่นไม่มีใน PDF; WS510SN ใช้ข้อยกเว้น June ที่ผู้ใช้ยืนยัน
- โปรโมชัน .5 ใน PDF บางแถวปัดลง แต่กฎ OSMS เดิมปัดขึ้น; ห้ามเปลี่ยนทั้งกลุ่มจากกฎเหมารวม
- GC-L24: Sep V4 p7 รองรับราคาเดิม 624/499 แต่รุ่นหายจาก V4_2_1; ผู้ใช้สั่งคงเดิมรอยืนยัน
- ทุกรายการได้รับผลประเมินแล้ว แต่รายการที่หลักฐานไม่พอยังไม่ผ่านการรับรองราคา

## รายการที่แก้แล้ว

- WS523S.AEWPLTH|3Y|Visit|ทุก 4 เดือน|false: แก้รอบบริการ 3 → 4 เดือน ตาม Updated_Price3Y.xlsx Price3Y row18
- 32U889SA.GRAB|5Y|No Service|ไม่มีบริการ|false: แก้ยอดประหยัด 2097 → 0 บาท ตาม PDF p61 และ Excel GTM row275

## รายการที่ต้องยืนยัน

### GC-L24FFCBB.AEVPLM1|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: PTOL24FFCB2.APTO; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 4; source code PTOL24FFCB2.APTO; cycle ทุก 6 เดือน

### GC-L24FFCBB.AEVPLM1|5Y|Visit|ทุก 6 เดือน|false

- ผู้ใช้ยืนยัน 26 ก.ย.: คงราคาปัจจุบัน รอยืนยันการปัดเศษ
- ตัวเลขบางช่องไม่ตรงต้นฉบับ: billSchedule, totalSaving
- หลักฐาน: sep-excel GTM!row 4; OSMS half-up per user

### GC-L24FFCBB.AEVPLM1|7Y|Visit|ทุก 6 เดือน|false

- ผู้ใช้ยืนยัน 26 ก.ย.: คงราคาปัจจุบัน รอยืนยันการปัดเศษ
- ตัวเลขบางช่องไม่ตรงต้นฉบับ: billSchedule, totalSaving
- หลักฐาน: sep-excel GTM!row 5; OSMS half-up per user

### GC-X24FFCRB.AEVPLM1|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: PTOX24FFCR2.APTO; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 3; source code PTOX24FFCR2.APTO; cycle ทุก 6 เดือน

### GC-X257CMHW.AEEPLMT|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: PTOX257CMHW.APTO; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 2; source code PTOX257CMHW.APTO; cycle ทุก 6 เดือน

### TX2725AT9G.AEGPETH|5Y|Visit|ทุก 12 เดือน|false

- ราคาตาม Excel แต่สถานะสินค้า: รอของเข้ากลางเดือน
- หลักฐาน: sep-excel GTM!row 129; OSMS half-up per user

### TX2725AT9G.AEGPETH|5Y|Self|ทุก 12 เดือน|false

- ราคาตาม Excel แต่สถานะสินค้า: รอของเข้ากลางเดือน
- หลักฐาน: sep-excel GTM!row 130; OSMS half-up per user

### TX2725AT9G.AEGPETH|7Y|Visit|ทุก 12 เดือน|false

- ราคาตาม Excel แต่สถานะสินค้า: รอของเข้ากลางเดือน
- หลักฐาน: sep-excel GTM!row 131; OSMS half-up per user

### TX2725AT9G.AEGPETH|7Y|Self|ทุก 12 เดือน|false

- ราคาตาม Excel แต่สถานะสินค้า: รอของเข้ากลางเดือน
- หลักฐาน: sep-excel GTM!row 132; OSMS half-up per user

### RX10VHP3KR.AEBPETH|5Y|Visit|ทุก 12 เดือน|false

- ค้น PDF และ Excel ใน promotions/docs แล้วไม่พบแถวราคา 5Y/7Y ของรหัสนี้; ห้ามนำราคา RV รุ่นเก่ามาแทน
- ไม่มีหลักฐานราคาปัจจุบันของแพ็กเกจนี้
- หลักฐาน: 

### RX10VHP3KR.AEBPETH|5Y|Self|ทุก 12 เดือน|false

- ค้น PDF และ Excel ใน promotions/docs แล้วไม่พบแถวราคา 5Y/7Y ของรหัสนี้; ห้ามนำราคา RV รุ่นเก่ามาแทน
- ไม่มีหลักฐานราคาปัจจุบันของแพ็กเกจนี้
- หลักฐาน: 

### RX10VHP3KR.AEBPETH|7Y|Visit|ทุก 12 เดือน|false

- ค้น PDF และ Excel ใน promotions/docs แล้วไม่พบแถวราคา 5Y/7Y ของรหัสนี้; ห้ามนำราคา RV รุ่นเก่ามาแทน
- ไม่มีหลักฐานราคาปัจจุบันของแพ็กเกจนี้
- หลักฐาน: 

### RX10VHP3KR.AEBPETH|7Y|Self|ทุก 12 เดือน|false

- ค้น PDF และ Excel ใน promotions/docs แล้วไม่พบแถวราคา 5Y/7Y ของรหัสนี้; ห้ามนำราคา RV รุ่นเก่ามาแทน
- ไม่มีหลักฐานราคาปัจจุบันของแพ็กเกจนี้
- หลักฐาน: 

### DD23GMWE1S.ATH|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: DD23GMWE1.ATH; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 55; source code DD23GMWE1.ATH; cycle ทุก 12 เดือน

### DD23GMWE1S.ATH|3Y|Self|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: DD23GMWE1.ATH; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 55; source code DD23GMWE1.ATH; cycle ทุก 12 เดือน

### MD19GQGA1S.ATH|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: MD19GQGA1.ATH; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 54; source code MD19GQGA1.ATH; cycle ทุก 12 เดือน

### MD19GQGA1S.ATH|3Y|Self|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: MD19GQGA1.ATH; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 54; source code MD19GQGA1.ATH; cycle ทุก 12 เดือน

### MD19GQGA1S.ATH|5Y|Visit|ทุก 12 เดือน|false

- ผู้ใช้ยืนยัน 26 ก.ย.: คงราคาปัจจุบัน รอยืนยันการปัดเศษ
- ตัวเลขบางช่องไม่ตรงต้นฉบับ: billSchedule, effectiveMonthly, totalSaving
- หลักฐาน: sep-excel GTM!row 231; OSMS half-up per user

### MD19GQGA1S.ATH|5Y|Self|ทุก 12 เดือน|false

- ผู้ใช้ยืนยัน 26 ก.ย.: คงราคาปัจจุบัน รอยืนยันการปัดเศษ
- ตัวเลขบางช่องไม่ตรงต้นฉบับ: billSchedule, effectiveMonthly, totalSaving
- หลักฐาน: sep-excel GTM!row 232; OSMS half-up per user

### MD19GQGA1S.ATH|7Y|Visit|ทุก 12 เดือน|false

- ผู้ใช้ยืนยัน 26 ก.ย.: คงราคาปัจจุบัน รอยืนยันการปัดเศษ
- ตัวเลขบางช่องไม่ตรงต้นฉบับ: billSchedule, effectiveMonthly, totalSaving
- หลักฐาน: sep-excel GTM!row 233; OSMS half-up per user

### MD19GQGA1S.ATH|7Y|Self|ทุก 12 เดือน|false

- ผู้ใช้ยืนยัน 26 ก.ย.: คงราคาปัจจุบัน รอยืนยันการปัดเศษ
- ตัวเลขบางช่องไม่ตรงต้นฉบับ: billSchedule, effectiveMonthly, totalSaving
- หลักฐาน: sep-excel GTM!row 234; OSMS half-up per user

### SAQ11A.S11|5Y|Visit|ทุก 12 เดือน|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- PDF p41 ระบุ 3490 แต่คำนวณจากงวดในหน้าเดียวกันได้ 3450 ซึ่งตรง Calculator จึงคงเดิม
- หลักฐาน: sep-price-list PDF p41; 5Y_Visit; ทุก 12 เดือน

### SAQ13A.S13|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SAQ13A.S11; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 66; source code SAQ13A.S11; cycle ทุก 6 เดือน

### SAQ13A.S13|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SAQ13A.S11; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 67; source code SAQ13A.S11; cycle ทุก 12 เดือน

### SAQ18B.S18|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SAQ18B.S21; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 68; source code SAQ18B.S21; cycle ทุก 6 เดือน

### SAQ18B.S18|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SAQ18B.S21; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 69; source code SAQ18B.S21; cycle ทุก 12 เดือน

### SAQ24B.S24|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SAQ24B.S21; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 70; source code SAQ24B.S21; cycle ทุก 6 เดือน

### SAQ24B.S24|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SAQ24B.S21; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 71; source code SAQ24B.S21; cycle ทุก 12 เดือน

### SIQ11B.S11|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ11B.S01; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 72; source code SIQ11B.S01; cycle ทุก 6 เดือน

### SIQ11B.S11|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ11B.S01; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 73; source code SIQ11B.S01; cycle ทุก 12 เดือน

### SIQ13B.S13|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ13B.S01; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 74; source code SIQ13B.S01; cycle ทุก 6 เดือน

### SIQ13B.S13|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ13B.S01; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 75; source code SIQ13B.S01; cycle ทุก 12 เดือน

### SIQ13B.S13|7Y|Visit|ทุก 6 เดือน|false

- ต้นฉบับพิมพ์ช่วงสุดท้ายเพียงบิล 84; Policy DC7M สื่อถึงบิล 9-84 แต่ต้องยืนยัน
- หลักฐาน: sep-price-list PDF p46; incomplete final range

### SIQ18B.S18|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ18B.S11; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 76; source code SIQ18B.S11; cycle ทุก 6 เดือน

### SIQ18B.S18|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ18B.S11; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 77; source code SIQ18B.S11; cycle ทุก 12 เดือน

### SIQ24B.S24|3Y|Visit|ทุก 6 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ24B.S11; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 78; source code SIQ24B.S11; cycle ทุก 6 เดือน

### SIQ24B.S24|3Y|Visit|ทุก 12 เดือน|false

- รหัสในต้นฉบับต่างกัน: SIQ24B.S11; ต้องยืนยันการจับคู่รุ่น/บันเดิล
- หลักฐาน: three-year Price3Y!row 79; source code SIQ24B.S11; cycle ทุก 12 เดือน

### 100MRGB96BS.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 13497 ต่างจากผลรวมล่วงหน้า+ทุกงวด 13506; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p54; 5Y; ไม่มีบริการ

### 100QNED86BS.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 7797 ต่างจากผลรวมล่วงหน้า+ทุกงวด 7806; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p56; 5Y; ไม่มีบริการ

### 27LX6TDGA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 2247 ต่างจากผลรวมล่วงหน้า+ทุกงวด 2256; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p59; 5Y; ไม่มีบริการ

### 32LX6BDGA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 2547 ต่างจากผลรวมล่วงหน้า+ทุกงวด 2556; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p58; 5Y; ไม่มีบริการ

### 55QNED80BSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 1647 ต่างจากผลรวมล่วงหน้า+ทุกงวด 1656; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p56; 5Y; ไม่มีบริการ

### 65QNED80BSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 1947 ต่างจากผลรวมล่วงหน้า+ทุกงวด 1956; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p56; 5Y; ไม่มีบริการ

### 85QNED80BSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 4047 ต่างจากผลรวมล่วงหน้า+ทุกงวด 4056; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p56; 5Y; ไม่มีบริการ

### 75QNED86BSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- ยอดประหยัดในระบบ 2697 ต่างจากผลรวมล่วงหน้า+ทุกงวด 2706; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-excel GTM!row 266

### OLED55C6PSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 3297 ต่างจากผลรวมล่วงหน้า+ทุกงวด 3306; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p55; 5Y; ไม่มีบริการ

### OLED48C6PSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- ยอดประหยัดในระบบ 2247 ต่างจากผลรวมล่วงหน้า+ทุกงวด 2256; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-excel GTM!row 264

### OLED48C6PSA.BOUNCE|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- หลักฐาน: sep-excel GTM!row 265

### OLED65C6PSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 3897 ต่างจากผลรวมล่วงหน้า+ทุกงวด 3906; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p55; 5Y; ไม่มีบริการ

### OLED77C6PSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ยอดประหยัดในระบบ 6000 ต่างจากผลรวมล่วงหน้า+ทุกงวด 6006; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p55; 5Y; ไม่มีบริการ

### OLED83C6PSA.ATM|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 8997 ต่างจากผลรวมล่วงหน้า+ทุกงวด 9006; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p55; 5Y; ไม่มีบริการ

### 27GX704A-B.ATM|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- หลักฐาน: sep-excel GTM!row 279

### 40U990A-W.ATM|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- หลักฐาน: sep-excel GTM!row 277

### 45GX950A-B.ATM|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- หลักฐาน: sep-excel GTM!row 273

### 52G930B-B.ATM|5Y|No Service|ไม่มีบริการ|false

- ราคาเดือนตรง/เทียบได้ แต่ Excel ไม่ระบุเงินล่วงหน้าและงวดหักล่วงหน้า ต้องยืนยันจากใบราคาของรุ่น
- หลักฐาน: sep-excel GTM!row 278

### BOUNCE.ATHALBK|5Y|No Service|ไม่มีบริการ|false

- ยอดประหยัดในระบบ 420 ต่างจากผลรวมล่วงหน้า+ทุกงวด 426; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p62; label BOUNCE.ATHALBK

### GRAB.ATHALBK|5Y|No Service|ไม่มีบริการ|false

- ยอดประหยัดในระบบ 330 ต่างจากผลรวมล่วงหน้า+ทุกงวด 336; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p62; label GRAB.ATHALBK

### STAGE501.ATHALBK|5Y|No Service|ไม่มีบริการ|false

- ตัวเลขบางช่องไม่ตรงต้นฉบับ: totalSaving
- ยอดประหยัดในระบบ 1347 ต่างจากผลรวมล่วงหน้า+ทุกงวด 1356; เอกสารอาจใช้การปัดเศษคนละวิธี ต้องยืนยันก่อนเปลี่ยน
- หลักฐาน: sep-price-list PDF p64; label STAGE501.ATHALBK

## ทุกรายการ

| รุ่น / แพ็กเกจ | ผลตรวจ | หลักฐาน |
|---|---|---|
| GC-J257SQZW.AEPPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 9 (F) |
| GC-B257SQYL.AMCPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 14 (F) |
| GC-B257SQYL.AMCPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 32; OSMS half-up per user |
| GC-B257SQYL.AMCPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 33; OSMS half-up per user |
| GC-L257SFZW.APYPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 11 (F) |
| GC-L257SFZW.APYPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p8; 5Y_Visit; ทุก 24 เดือน |
| GC-L257SFZW.APYPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p8; 7Y_Visit; ทุก 24 เดือน |
| GC-L257KQKW.AEPPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 12 (F) |
| GC-L257KQKW.AEPPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 30; OSMS half-up per user |
| GC-L257KQKW.AEPPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 31; OSMS half-up per user |
| GC-X257CMEW.ATEPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 6 (F) |
| GC-X257CMEW.ATEPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p9; 5Y_Visit; ทุก 24 เดือน |
| GC-X257CMEW.ATEPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p9; 7Y_Visit; ทุก 24 เดือน |
| GC-G24FFQKB.AEEPLM1 / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 5 (F) |
| GC-G24FFQKB.AEEPLM1 / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p10; 5Y_Visit; ทุก 24 เดือน |
| GC-G24FFQKB.AEEPLM1 / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p10; 7Y_Visit; ทุก 24 เดือน |
| GC-V22FFQMB.AEPPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 8 (F) |
| GV-B25FFGDB.ABMPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 10 (F) |
| GV-V25FFGRB.ABMPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 7 (F) |
| GC-B48FPGAM.ADBPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p11; 5Y_Visit; ทุก 24 เดือน |
| GC-B48FPGAM.ADBPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p11; 7Y_Visit; ทุก 24 เดือน |
| GN-F392PQAK.AEPPLM1 / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 16 (F) |
| GN-F392PQAK.AEPPLM1 / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p13; 5Y_Visit; ทุก 24 เดือน |
| GN-F392PQAK.AEPPLM1 / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p13; 7Y_Visit; ทุก 24 เดือน |
| GN-F452PQAK.AEPPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 15 (F) |
| GN-F452PQAK.AEPPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p12; 5Y_Visit; ทุก 24 เดือน |
| GN-F452PQAK.AEPPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p12; 7Y_Visit; ทุก 24 เดือน |
| GN-V389FQEF.AEPPLMT / 3Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 13 (F) |
| GN-V389FQEF.AEPPLMT / 5Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p12; 5Y_Visit; ทุก 24 เดือน |
| GN-V389FQEF.AEPPLMT / 7Y / Visit / ทุก 24 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p12; 7Y_Visit; ทุก 24 เดือน |
| GC-L24FFCBB.AEVPLM1 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 4; source code PTOL24FFCB2.APTO; cycle ทุก 6 เดือน |
| GC-L24FFCBB.AEVPLM1 / 5Y / Visit / ทุก 6 เดือน / false | คงเดิมตามผู้ใช้ | sep-excel GTM!row 4; OSMS half-up per user |
| GC-L24FFCBB.AEVPLM1 / 7Y / Visit / ทุก 6 เดือน / false | คงเดิมตามผู้ใช้ | sep-excel GTM!row 5; OSMS half-up per user |
| GC-X24FFCRB.AEVPLM1 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 3; source code PTOX24FFCR2.APTO; cycle ทุก 6 เดือน |
| GC-X24FFCRB.AEVPLM1 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p6; 5Y_Visit; ทุก 6 เดือน; sep-price-list PDF p7; 5Y_Visit; ทุก 6 เดือน |
| GC-X24FFCRB.AEVPLM1 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p6; 7Y_Visit; ทุก 6 เดือน; sep-price-list PDF p7; 7Y_Visit; ทุก 6 เดือน |
| GC-X257CMHW.AEEPLMT / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 2; source code PTOX257CMHW.APTO; cycle ทุก 6 เดือน |
| GC-X257CMHW.AEEPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p7; 5Y_Visit; ทุก 6 เดือน |
| GC-X257CMHW.AEEPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p7; 7Y_Visit; ทุก 6 เดือน |
| WT1410NHEG.ABGPQTH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 30 (F) |
| WT1410NHEG.ABGPQTH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 30 (G) |
| WT1410NHEG.ABGPQTH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p18; 5Y_Visit; ทุก 12 เดือน |
| WT1410NHEG.ABGPQTH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p18; 5Y_Self; ทุก 12 เดือน |
| WT1410NHEG.ABGPQTH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p18; 7Y_Visit; ทุก 12 เดือน |
| WT1410NHEG.ABGPQTH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p18; 7Y_Self; ทุก 12 เดือน |
| WT1410NHEN.ABNPQTH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 31 (F) |
| WT1410NHEN.ABNPQTH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 31 (G) |
| WT1410NHEN.ABNPQTH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p19; 5Y_Visit; ทุก 12 เดือน |
| WT1410NHEN.ABNPQTH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p19; 5Y_Self; ทุก 12 เดือน |
| WT1410NHEN.ABNPQTH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p19; 7Y_Visit; ทุก 12 เดือน |
| WT1410NHEN.ABNPQTH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p19; 7Y_Self; ทุก 12 เดือน |
| WT2116SHEG.ABGPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 29 (F) |
| WT2116SHEG.ABGPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 29 (G) |
| WT2116SHEG.ABGPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p17; 5Y_Visit; ทุก 12 เดือน |
| WT2116SHEG.ABGPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p17; 5Y_Self; ทุก 12 เดือน |
| WT2116SHEG.ABGPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p17; 7Y_Visit; ทุก 12 เดือน |
| WT2116SHEG.ABGPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p17; 7Y_Self; ทุก 12 เดือน |
| WT2116SHBB.ABLPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p16; 5Y_Visit; ทุก 12 เดือน |
| WT2116SHBB.ABLPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p16; 5Y_Self; ทุก 12 เดือน |
| WT2116SHBB.ABLPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p16; 7Y_Visit; ทุก 12 เดือน |
| WT2116SHBB.ABLPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p16; 7Y_Self; ทุก 12 เดือน |
| WT2520NHEG.ABGPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p14; 5Y_Visit; ทุก 12 เดือน |
| WT2520NHEG.ABGPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p14; 5Y_Self; ทุก 12 เดือน |
| WT2520NHEG.ABGPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p14; 7Y_Visit; ทุก 12 เดือน |
| WT2520NHEG.ABGPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p14; 7Y_Self; ทุก 12 เดือน |
| WT2520NHEN.ABNPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p15; 5Y_Visit; ทุก 12 เดือน |
| WT2520NHEN.ABNPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p15; 5Y_Self; ทุก 12 เดือน |
| WT2520NHEN.ABNPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p15; 7Y_Visit; ทุก 12 เดือน |
| WT2520NHEN.ABNPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p15; 7Y_Self; ทุก 12 เดือน |
| F2520RNTB.AEBPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 32 (F) |
| F2520RNTB.AEBPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 32 (G) |
| F2520RNTB.AEBPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p20; 5Y_Visit; ทุก 12 เดือน |
| F2520RNTB.AEBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p20; 5Y_Self; ทุก 12 เดือน |
| F2520RNTB.AEBPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p20; 7Y_Visit; ทุก 12 เดือน |
| F2520RNTB.AEBPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p20; 7Y_Self; ทุก 12 เดือน |
| FX2725SFXKA.AEBPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 95; OSMS half-up per user |
| FX2725SFXKA.AEBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 96; OSMS half-up per user |
| FX2725SFXKA.AEBPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 97; OSMS half-up per user |
| FX2725SFXKA.AEBPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 98; OSMS half-up per user |
| FV1413H4M.AMBPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 33 (F) |
| FV1413H4M.AMBPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 33 (G) |
| FV1413H4M.AMBPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p21; 5Y_Visit; ทุก 12 เดือน |
| FV1413H4M.AMBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p21; 5Y_Self; ทุก 12 เดือน |
| FV1413H4M.AMBPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p21; 7Y_Visit; ทุก 12 เดือน |
| FV1413H4M.AMBPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p21; 7Y_Self; ทุก 12 เดือน |
| FV1413S4M.AMBPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 34 (F) |
| FV1413S4M.AMBPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 34 (G) |
| FV1413S4M.AMBPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p22; 5Y_Visit; ทุก 12 เดือน |
| FV1413S4M.AMBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p22; 5Y_Self; ทุก 12 เดือน |
| FV1413S4M.AMBPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p22; 7Y_Visit; ทุก 12 เดือน |
| FV1413S4M.AMBPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p22; 7Y_Self; ทุก 12 เดือน |
| FV1409H4W.ABWPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 36 (F) |
| FV1409H4W.ABWPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 36 (G) |
| TX2315DT5G.DEGPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 39 (F) |
| TX2315DT5G.DEGPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 39 (G) |
| TX2723ST5J.APBPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 38 (F) |
| TX2723ST5J.APBPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 38 (G) |
| TX2523AT7G.AEGPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p24; 5Y_Visit; ทุก 12 เดือน |
| TX2523AT7G.AEGPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p24; 5Y_Self; ทุก 12 เดือน |
| TX2523AT7G.AEGPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p24; 7Y_Visit; ทุก 12 เดือน |
| TX2523AT7G.AEGPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p24; 7Y_Self; ทุก 12 เดือน |
| TX2726ST5J.APBPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p23; 5Y_Visit; ทุก 12 เดือน |
| TX2726ST5J.APBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p23; 5Y_Self; ทุก 12 เดือน |
| TX2725AT9G.AEGPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 37 (F) |
| TX2725AT9G.AEGPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 37 (G) |
| TX2725AT9G.AEGPETH / 5Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 129; OSMS half-up per user |
| TX2725AT9G.AEGPETH / 5Y / Self / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 130; OSMS half-up per user |
| TX2725AT9G.AEGPETH / 7Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 131; OSMS half-up per user |
| TX2725AT9G.AEGPETH / 7Y / Self / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 132; OSMS half-up per user |
| DFC335HM.ABMPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 41 (F) |
| DFC335HM.ABMPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 41 (G) |
| DFC335HM.ABMPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p27; 5Y Visit; ทุก 12 เดือน |
| DFC335HM.ABMPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p27; 5Y Self; ทุก 12 เดือน |
| DFC335HM.ABMPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p27; 7Y Visit; ทุก 12 เดือน |
| DFC335HM.ABMPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p27; 7Y Self; ทุก 12 เดือน |
| DFC533FV.APYPETH / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 42 (F) |
| DFC533FV.APYPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 42 (G) |
| DFC533FV.APYPETH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p28; 5Y Visit; ทุก 12 เดือน |
| DFC533FV.APYPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p28; 5Y Self; ทุก 12 เดือน |
| DFC533FV.APYPETH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p28; 7Y Visit; ทุก 12 เดือน |
| DFC533FV.APYPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p28; 7Y Self; ทุก 12 เดือน |
| RX10VHP3KR.AEBPETH / 5Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน |  |
| RX10VHP3KR.AEBPETH / 5Y / Self / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน |  |
| RX10VHP3KR.AEBPETH / 7Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน |  |
| RX10VHP3KR.AEBPETH / 7Y / Self / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน |  |
| S3MFC.ALBPETH / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 40 (G) |
| S3MFC.ALBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p29; 5Y Self; ทุก 12 เดือน |
| S3MFC.ALBPETH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p29; 7Y Self; ทุก 12 เดือน |
| MS4295DIS.BBKPETH / 3Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 26 (G) |
| MS4295DIS.BBKPETH / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p30 |
| AS10GDBY0.ABAE / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 52 (F) |
| AS10GDBY0.ABAE / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 53 (F) |
| AS10GDBY0.ABAE / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 52 (G) |
| AS10GDBY0.ABAE / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 53 (G) |
| AS10GDBY0.ABAE / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p37; 5Y Visit; ทุก 6 เดือน |
| AS10GDBY0.ABAE / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p37; 5Y Visit; ทุก 12 เดือน |
| AS10GDBY0.ABAE / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p37; 5Y Self; ทุก 6 เดือน |
| AS10GDBY0.ABAE / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p37; 5Y Self; ทุก 12 เดือน |
| AS10GDBY0.ABAE / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p38; 7Y Visit; ทุก 6 เดือน |
| AS10GDBY0.ABAE / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p38; 7Y Visit; ทุก 12 เดือน |
| AS10GDBY0.ABAE / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p38; 7Y Self; ทุก 6 เดือน |
| AS10GDBY0.ABAE / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p38; 7Y Self; ทุก 12 เดือน |
| AS25GCBY0.ABAE / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 46 (F) |
| AS25GCBY0.ABAE / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 46 (G) |
| AS25GCBY0.ABAE / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p32; 5Y_Visit; ทุก 12 เดือน |
| AS25GCBY0.ABAE / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p32; 5Y_Self; ทุก 12 เดือน |
| AS25GCBY0.ABAE / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p32; 7Y_Visit; ทุก 12 เดือน |
| AS25GCBY0.ABAE / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p32; 7Y_Self; ทุก 12 เดือน |
| AS35GGW10.ATH / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 47 (F) |
| AS35GGW10.ATH / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 47 (G) |
| AS35GGW10.ATH / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 227; OSMS half-up per user |
| AS35GGW10.ATH / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 228; OSMS half-up per user |
| AS35GGW10.ATH / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 229; OSMS half-up per user |
| AS35GGW10.ATH / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 230; OSMS half-up per user |
| AS60GHWG0.ABAE / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 48 (F) |
| AS60GHWG0.ABAE / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 49 (F) |
| AS60GHWG0.ABAE / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 48 (G) |
| AS60GHWG0.ABAE / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 49 (G) |
| AS60GHWG0.ABAE / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p33; 5Y Visit; ทุก 6 เดือน |
| AS60GHWG0.ABAE / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p33; 5Y Visit; ทุก 12 เดือน |
| AS60GHWG0.ABAE / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p33; 5Y Self; ทุก 6 เดือน |
| AS60GHWG0.ABAE / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p33; 5Y Self; ทุก 12 เดือน |
| AS60GHWG0.ABAE / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p34; 7Y Visit; ทุก 6 เดือน |
| AS60GHWG0.ABAE / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p34; 7Y Visit; ทุก 12 เดือน |
| AS60GHWG0.ABAE / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p34; 7Y Self; ทุก 6 เดือน |
| AS60GHWG0.ABAE / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p34; 7Y Self; ทุก 12 เดือน |
| AS65GDBY0.ABAE / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 50 (F) |
| AS65GDBY0.ABAE / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 51 (F) |
| AS65GDBY0.ABAE / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 50 (G) |
| AS65GDBY0.ABAE / 3Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 51 (G) |
| AS65GDBY0.ABAE / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p35; 5Y Visit; ทุก 6 เดือน |
| AS65GDBY0.ABAE / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p35; 5Y Visit; ทุก 12 เดือน |
| AS65GDBY0.ABAE / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p35; 5Y Self; ทุก 6 เดือน |
| AS65GDBY0.ABAE / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p35; 5Y Self; ทุก 12 เดือน |
| AS65GDBY0.ABAE / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p36; 7Y Visit; ทุก 6 เดือน |
| AS65GDBY0.ABAE / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p36; 7Y Visit; ทุก 12 เดือน |
| AS65GDBY0.ABAE / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p36; 7Y Self; ทุก 6 เดือน |
| AS65GDBY0.ABAE / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p36; 7Y Self; ทุก 12 เดือน |
| DD23GMWE1S.ATH / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 55; source code DD23GMWE1.ATH; cycle ทุก 12 เดือน |
| DD23GMWE1S.ATH / 3Y / Self / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 55; source code DD23GMWE1.ATH; cycle ทุก 12 เดือน |
| DD23GMWE1S.ATH / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p31; 5Y_Visit; ทุก 12 เดือน |
| DD23GMWE1S.ATH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p31; 5Y_Self; ทุก 12 เดือน |
| DD23GMWE1S.ATH / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p31; 7Y_Visit; ทุก 12 เดือน |
| DD23GMWE1S.ATH / 7Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p31; 7Y_Self; ทุก 12 เดือน |
| MD19GQGA1S.ATH / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 54; source code MD19GQGA1.ATH; cycle ทุก 12 เดือน |
| MD19GQGA1S.ATH / 3Y / Self / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 54; source code MD19GQGA1.ATH; cycle ทุก 12 เดือน |
| MD19GQGA1S.ATH / 5Y / Visit / ทุก 12 เดือน / false | คงเดิมตามผู้ใช้ | sep-excel GTM!row 231; OSMS half-up per user |
| MD19GQGA1S.ATH / 5Y / Self / ทุก 12 เดือน / false | คงเดิมตามผู้ใช้ | sep-excel GTM!row 232; OSMS half-up per user |
| MD19GQGA1S.ATH / 7Y / Visit / ทุก 12 เดือน / false | คงเดิมตามผู้ใช้ | sep-excel GTM!row 233; OSMS half-up per user |
| MD19GQGA1S.ATH / 7Y / Self / ทุก 12 เดือน / false | คงเดิมตามผู้ใช้ | sep-excel GTM!row 234; OSMS half-up per user |
| SAQ11A.S11 / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 64 (F) |
| SAQ11A.S11 / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 65 (F) |
| SAQ11A.S11 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p41; 5Y_Visit; ทุก 6 เดือน |
| SAQ11A.S11 / 5Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p41; 5Y_Visit; ทุก 12 เดือน |
| SAQ11A.S11 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p42; 7Y_Visit; ทุก 6 เดือน |
| SAQ11A.S11 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p42; 7Y_Visit; ทุก 12 เดือน |
| SAQ13A.S13 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 66; source code SAQ13A.S11; cycle ทุก 6 เดือน |
| SAQ13A.S13 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 67; source code SAQ13A.S11; cycle ทุก 12 เดือน |
| SAQ13A.S13 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p41; 5Y_Visit; ทุก 6 เดือน |
| SAQ13A.S13 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p41; 5Y_Visit; ทุก 12 เดือน |
| SAQ13A.S13 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p42; 7Y_Visit; ทุก 6 เดือน |
| SAQ13A.S13 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p42; 7Y_Visit; ทุก 12 เดือน |
| SAQ18B.S18 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 68; source code SAQ18B.S21; cycle ทุก 6 เดือน |
| SAQ18B.S18 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 69; source code SAQ18B.S21; cycle ทุก 12 เดือน |
| SAQ18B.S18 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p43; 5Y_Visit; ทุก 6 เดือน |
| SAQ18B.S18 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p43; 5Y_Visit; ทุก 12 เดือน |
| SAQ18B.S18 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p44; 7Y_Visit; ทุก 6 เดือน |
| SAQ18B.S18 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p44; 7Y_Visit; ทุก 12 เดือน |
| SAQ24B.S24 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 70; source code SAQ24B.S21; cycle ทุก 6 เดือน |
| SAQ24B.S24 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 71; source code SAQ24B.S21; cycle ทุก 12 เดือน |
| SAQ24B.S24 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p43; 5Y_Visit; ทุก 6 เดือน |
| SAQ24B.S24 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p43; 5Y_Visit; ทุก 12 เดือน |
| SAQ24B.S24 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p44; 7Y_Visit; ทุก 6 เดือน |
| SAQ24B.S24 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p44; 7Y_Visit; ทุก 12 เดือน |
| SIQ11B.S11 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 72; source code SIQ11B.S01; cycle ทุก 6 เดือน |
| SIQ11B.S11 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 73; source code SIQ11B.S01; cycle ทุก 12 เดือน |
| SIQ11B.S11 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p45; 5Y_Visit; ทุก 6 เดือน |
| SIQ11B.S11 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p45; 5Y_Visit; ทุก 12 เดือน |
| SIQ11B.S11 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p46; 7Y_Visit; ทุก 6 เดือน |
| SIQ11B.S11 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p46; 7Y_Visit; ทุก 12 เดือน |
| SIQ13B.S13 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 74; source code SIQ13B.S01; cycle ทุก 6 เดือน |
| SIQ13B.S13 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 75; source code SIQ13B.S01; cycle ทุก 12 เดือน |
| SIQ13B.S13 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p45; 5Y_Visit; ทุก 6 เดือน |
| SIQ13B.S13 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p45; 5Y_Visit; ทุก 12 เดือน |
| SIQ13B.S13 / 7Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p46; incomplete final range |
| SIQ13B.S13 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p46; 7Y_Visit; ทุก 12 เดือน |
| SIQ18B.S18 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 76; source code SIQ18B.S11; cycle ทุก 6 เดือน |
| SIQ18B.S18 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 77; source code SIQ18B.S11; cycle ทุก 12 เดือน |
| SIQ18B.S18 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p47; 5Y_Visit; ทุก 6 เดือน |
| SIQ18B.S18 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p47; 5Y_Visit; ทุก 12 เดือน |
| SIQ18B.S18 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p48; 7Y_Visit; ทุก 6 เดือน |
| SIQ18B.S18 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p48; 7Y_Visit; ทุก 12 เดือน |
| SIQ24B.S24 / 3Y / Visit / ทุก 6 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 78; source code SIQ24B.S11; cycle ทุก 6 เดือน |
| SIQ24B.S24 / 3Y / Visit / ทุก 12 เดือน / false | ต้องยืนยันหลักฐาน | three-year Price3Y!row 79; source code SIQ24B.S11; cycle ทุก 12 เดือน |
| SIQ24B.S24 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p47; 5Y_Visit; ทุก 6 เดือน |
| SIQ24B.S24 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p47; 5Y_Visit; ทุก 12 เดือน |
| SIQ24B.S24 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p48; 7Y_Visit; ทุก 6 เดือน |
| SIQ24B.S24 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p48; 7Y_Visit; ทุก 12 เดือน |
| ART13A.SR1 / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 80 (F) |
| ART13A.SR1 / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 81 (F) |
| ART13A.SR1 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p39; 5Y_Visit; ทุก 6 เดือน |
| ART13A.SR1 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p39; 5Y_Visit; ทุก 12 เดือน |
| ART13A.SR1 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p40; 7Y_Visit; ทุก 6 เดือน |
| ART13A.SR1 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p40; 7Y_Visit; ทุก 12 เดือน |
| ART18A.SR1 / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 82 (F) |
| ART18A.SR1 / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 83 (F) |
| ART18A.SR1 / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p39; 5Y_Visit; ทุก 6 เดือน |
| ART18A.SR1 / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p39; 5Y_Visit; ทุก 12 เดือน |
| ART18A.SR1 / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p40; 7Y_Visit; ทุก 6 เดือน |
| ART18A.SR1 / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p40; 7Y_Visit; ทุก 12 เดือน |
| IXY11A / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 56 (F) |
| IXY11A / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 57 (F) |
| IXY11A / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 179; OSMS half-up per user |
| IXY11A / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 180; OSMS half-up per user |
| IXY11A / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 187; OSMS half-up per user |
| IXY11A / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 188; OSMS half-up per user |
| IXY13A / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 58 (F) |
| IXY13A / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 59 (F) |
| IXY13A / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 181; OSMS half-up per user |
| IXY13A / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 182; OSMS half-up per user |
| IXY13A / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 189; OSMS half-up per user |
| IXY13A / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 190; OSMS half-up per user |
| IXY18A / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 60 (F) |
| IXY18A / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 61 (F) |
| IXY18A / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 183; OSMS half-up per user |
| IXY18A / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 184; OSMS half-up per user |
| IXY18A / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 191; OSMS half-up per user |
| IXY18A / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 192; OSMS half-up per user |
| IXY24A / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 62 (F) |
| IXY24A / 3Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 63 (F) |
| IXY24A / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 185; OSMS half-up per user |
| IXY24A / 5Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 186; OSMS half-up per user |
| IXY24A / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 193; OSMS half-up per user |
| IXY24A / 7Y / Visit / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 194; OSMS half-up per user |
| ZT4Q18GPLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 89 (F) |
| ZT4Q18GPLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p49 |
| ZT4Q24GPLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 88 (F) |
| ZT4Q24GPLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p49 |
| ZT4Q36GNLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 87 (F) |
| ZT4Q36GNLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p49 |
| ZT4Q48GMLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 86 (F) |
| ZT4Q48GMLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p49 |
| ZT1Q12GULA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 95 (F) |
| ZT1Q12GULA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p50 |
| ZT1Q18GTLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 94 (F) |
| ZT1Q18GTLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p50 |
| ZT1Q24GTLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 93 (F) |
| ZT1Q24GTLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p50 |
| ZTRQ36GYLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 85 (F) |
| ZTRQ36GYLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p51 |
| ZTRQ48GYLA1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 84 (F) |
| ZTRQ48GYLA1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p51 |
| ZVCQ18GM1A1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 92 (F) |
| ZVCQ18GM1A1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 244; OSMS half-up per user |
| ZVCQ24GM1A1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 91 (F) |
| ZVCQ24GM1A1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 245; OSMS half-up per user |
| ZVCQ36GM2A1.EWGHATH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 90 (F) |
| ZVCQ36GM2A1.EWGHATH / 5Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 246; OSMS half-up per user |
| 100MRGB96BS.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p54; 5Y; ไม่มีบริการ |
| 100QNED86BS.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p56; 5Y; ไม่มีบริการ |
| 27LX6TDGA.GRAB / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p59; 5Y; ไม่มีบริการ |
| 27LX6TDGA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p59; 5Y; ไม่มีบริการ |
| 32LX6BDGA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p58; 5Y; ไม่มีบริการ |
| 55QNED80BSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p56; 5Y; ไม่มีบริการ |
| 65NU855BPSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p57; 5Y; ไม่มีบริการ |
| 65QNED80BSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p56; 5Y; ไม่มีบริการ |
| 75NU855BPSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p57; 5Y; ไม่มีบริการ |
| 85QNED80BSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p56; 5Y; ไม่มีบริการ |
| 75QNED86BSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 266 |
| OLED55C6PSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p55; 5Y; ไม่มีบริการ |
| OLED48C6PSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 264 |
| OLED48C6PSA.BOUNCE / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 265 |
| OLED55C6PSA.S30A / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p60; 5Y; ไม่มีบริการ |
| OLED65C6PSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p55; 5Y; ไม่มีบริการ |
| OLED65C6PSA.S80TY / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p60; 5Y; ไม่มีบริการ |
| OLED77C6PSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p55; 5Y; ไม่มีบริการ |
| OLED83C6PSA.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p55; 5Y; ไม่มีบริการ |
| OLED77C6PSA.S80TY / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p60; 5Y; ไม่มีบริการ |
| 32U889SA-W.ATM / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p61; 5Y; ไม่มีบริการ; sep-price-list PDF p61; 5Y; ไม่มีบริการ |
| 27GX704A-B.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 279 |
| 32U889SA.GRAB / 5Y / No Service / ไม่มีบริการ / false | แก้แล้ว | sep-price-list PDF p61; label 32U889SA.GRAB |
| 34U650A-B.ATM / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p61; 5Y; ไม่มีบริการ |
| 40U990A-W.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 277 |
| 45GX950A-B.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 273 |
| 52G930B-B.ATM / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-excel GTM!row 278 |
| BOUNCE.ATHALBK / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p62; label BOUNCE.ATHALBK |
| GRAB.ATHALBK / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p62; label GRAB.ATHALBK |
| S70TY.ATHALLD / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p65; 5Y; ไม่มีบริการ |
| S95TR.DTHALLK / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p65; 5Y; ไม่มีบริการ |
| STAGE301.ATH / 5Y / No Service / ไม่มีบริการ / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p63; label STAGE301.ATH |
| STAGE501.ATHALBK / 5Y / No Service / ไม่มีบริการ / false | ต้องยืนยันหลักฐาน | sep-price-list PDF p64; label STAGE501.ATHALBK |
| A9T-CORE.DCGPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p5; 5Y_Self; ทุก 12 เดือน |
| A9T-ULTRA.DCBPETH / 5Y / Self / ทุก 12 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p5; 5Y_Self; ทุก 12 เดือน |
| WD110MN.ABGPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 25 (F) |
| WD110MN.ABGPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 25 (G) |
| WD110MN.ABGPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD110MN.ABGPLMT 5Y Visit |
| WD110MN.ABGPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD110MN.ABGPLMT 5Y Self |
| WD110MN.ABGPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD110MN.ABGPLMT 7Y Visit |
| WD110MN.ABGPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD110MN.ABGPLMT 7Y Self |
| WS521S.AEWPLTH / 3Y / Visit / ทุก 4 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 17 (F) |
| WS523S.AEWPLTH / 3Y / Visit / ทุก 4 เดือน / false | แก้แล้ว | three-year Price3Y!row 18 (F) |
| WS523S.AEWPLTH / 5Y / Visit / ทุก 3 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 73; OSMS half-up per user |
| WS523S.AEWPLTH / 7Y / Visit / ทุก 3 เดือน / false | ตัวเลขที่เทียบตรง | sep-excel GTM!row 74; OSMS half-up per user |
| WS510SN.AWHPLMT / 5Y / Visit / ทุก 3 เดือน / false | ตัวเลขที่เทียบตรง | june-user-exception June V1.2; Price Jun_Water Purifier row14; RAW All Channel rows63-64 (updated columns AC/AI/AK); user exception 18 Sep |
| WS510SN.AWHPLMT / 7Y / Visit / ทุก 3 เดือน / false | ตัวเลขที่เทียบตรง | june-user-exception June V1.2; Price Jun_Water Purifier row14; RAW All Channel rows63-64 (updated columns AC/AI/AK); user exception 18 Sep |
| WD516AN.ACNPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 19 (F) |
| WD516AN.ACNPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 19 (G) |
| WD516AN.ACNPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ACNPLMT 5Y Visit |
| WD516AN.ACNPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ACNPLMT 5Y Self |
| WD516AN.ACNPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ACNPLMT 7Y Visit |
| WD516AN.ACNPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ACNPLMT 7Y Self |
| WD516AN.ACNPLMT / 2Y / Visit / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Visit |
| WD516AN.ACNPLMT / 2Y / Self / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Self |
| WD516AN.AEWPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 20 (F) |
| WD516AN.AEWPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 20 (G) |
| WD516AN.AEWPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.AEWPLMT 5Y Visit |
| WD516AN.AEWPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.AEWPLMT 5Y Self |
| WD516AN.AEWPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.AEWPLMT 7Y Visit |
| WD516AN.AEWPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.AEWPLMT 7Y Self |
| WD516AN.AEWPLMT / 2Y / Visit / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Visit |
| WD516AN.AEWPLMT / 2Y / Self / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Self |
| WD516AN.ASLPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 21 (F) |
| WD516AN.ASLPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 21 (G) |
| WD516AN.ASLPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ASLPLMT 5Y Visit |
| WD516AN.ASLPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ASLPLMT 5Y Self |
| WD516AN.ASLPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ASLPLMT 7Y Visit |
| WD516AN.ASLPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD516AN.ASLPLMT 7Y Self |
| WD516AN.ASLPLMT / 2Y / Visit / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Visit |
| WD516AN.ASLPLMT / 2Y / Self / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Self |
| WD518AN.ABGPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 22 (F) |
| WD518AN.ABGPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 22 (G) |
| WD518AN.ABGPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ABGPLMT 5Y Visit |
| WD518AN.ABGPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ABGPLMT 5Y Self |
| WD518AN.ABGPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ABGPLMT 7Y Visit |
| WD518AN.ABGPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ABGPLMT 7Y Self |
| WD518AN.ABGPLMT / 2Y / Visit / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Visit |
| WD518AN.ABGPLMT / 2Y / Self / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Self |
| WD518AN.ACGPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 24 (F) |
| WD518AN.ACGPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 24 (G) |
| WD518AN.ACGPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ACGPLMT 5Y Visit |
| WD518AN.ACGPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ACGPLMT 5Y Self |
| WD518AN.ACGPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ACGPLMT 7Y Visit |
| WD518AN.ACGPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.ACGPLMT 7Y Self |
| WD518AN.ACGPLMT / 2Y / Visit / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Visit |
| WD518AN.ACGPLMT / 2Y / Self / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Self |
| WD518AN.AWHPLMT / 3Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 23 (F) |
| WD518AN.AWHPLMT / 3Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | three-year Price3Y!row 23 (G) |
| WD518AN.AWHPLMT / 5Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.AWHPLMT 5Y Visit |
| WD518AN.AWHPLMT / 5Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.AWHPLMT 5Y Self |
| WD518AN.AWHPLMT / 7Y / Visit / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.AWHPLMT 7Y Visit |
| WD518AN.AWHPLMT / 7Y / Self / ทุก 6 เดือน / false | ตัวเลขที่เทียบตรง | sep-price-list PDF p4; WD518AN.AWHPLMT 7Y Self |
| WD518AN.AWHPLMT / 2Y / Visit / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Visit |
| WD518AN.AWHPLMT / 2Y / Self / ทุก 6 เดือน / true | ตัวเลขที่เทียบตรง | sep-price-list PDF p3 OUTRIGHT Self |
