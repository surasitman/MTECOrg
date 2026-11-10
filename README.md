# MTECOrg — แผนพัฒนาบุคลากรฝ่ายสนับสนุน ศว. ปีงบประมาณ 2570

> ⚠️ **ข้อมูลภายใน มีข้อมูลส่วนบุคคล** (ชื่อ รหัสพนักงาน ภาระงาน ทักษะรายบุคคล แผนโยกย้าย)
> Repository นี้ต้องเป็น **Private** เท่านั้น ห้ามเปิดเป็น Public และห้ามเปิด GitHub Pages แบบสาธารณะ

## 📊 Skill Matrix รายฝ่าย

คลิก **สรุปบน GitHub** เพื่อดูรายละเอียดได้ทันที หรือคลิก **ไฟล์ Excel** เพื่อดาวน์โหลดฉบับเต็ม (GitHub แสดงตัวอย่างไฟล์ .xlsx ไม่ได้)

| ฝ่าย | ชื่อฝ่าย | คน | Priority สูง | สรุปบน GitHub | ไฟล์ Excel |
|---|---|---:|---:|---|---|
| BDD | ฝ่ายพัฒนาธุรกิจ | 18 | 28 | [ดูสรุป](skillmatrix/BDD.md) | [Skill_Matrix_BDD_2570.xlsx](excel/Skill_Matrix_BDD_2570.xlsx) |
| GMD | ฝ่ายบริหารงานทั่วไป | 11 | 10 | [ดูสรุป](skillmatrix/GMD.md) | [Skill_Matrix_GMD_2570.xlsx](excel/Skill_Matrix_GMD_2570.xlsx) |
| MTD | ฝ่ายเผยแพร่ความรู้เทคโนโลยีวัสดุ | 10 | 14 | [ดูสรุป](skillmatrix/MTD.md) | [Skill_Matrix_MTD_2570.xlsx](excel/Skill_Matrix_MTD_2570.xlsx) |
| RPM | ฝ่ายบริหารโครงการวิจัย | 26 | 29 | [ดูสรุป](skillmatrix/RPM.md) | [Skill_Matrix_RPM_2570.xlsx](excel/Skill_Matrix_RPM_2570.xlsx) |
| PSE | ฝ่ายแผนกลยุทธ์และประเมินผล | 17 | 54 | [ดูสรุป](skillmatrix/PSE.md) | [Skill_Matrix_PSE_2570.xlsx](excel/Skill_Matrix_PSE_2570.xlsx) |
| RIS | ฝ่ายขับเคลื่อนยุทธศาสตร์การวิจัยและนวัตกรรม | 8 | 2 | [ดูสรุป](skillmatrix/RIS.md) | [Skill_Matrix_RIS_2570.xlsx](excel/Skill_Matrix_RIS_2570.xlsx) |
| TSMA | ฝ่ายสนับสนุนเทคนิคด้านวิเคราะห์ลักษณะเฉพาะของวัสดุ | 25 | 318 | [ดูสรุป](skillmatrix/TSMA.md) | [Skill_Matrix_TSMA_2570.xlsx](excel/Skill_Matrix_TSMA_2570.xlsx) |

📥 สรุปผู้บริหาร: [Executive_Summary_SU_2570.xlsx](excel/Executive_Summary_SU_2570.xlsx)

## สิ่งที่อยู่ใน repo

| โฟลเดอร์/ไฟล์ | เนื้อหา |
|---|---|
| `index.html` | Dashboard แบบเว็บ 9 แท็บ: ภาพรวม, ทักษะ, AI Roadmap, งานซ้ำซ้อน, โครงสร้างองค์กร, Mobilize, OKR 2570, รายบุคคล, ข้อมูลที่ขาด |
| `data/data.js` | ข้อมูลทั้งหมดที่ Dashboard ใช้ (ฝังไว้เพื่อให้เปิดแบบ offline ได้) |
| `data/*.csv` | ข้อมูลชุดเดียวกันในรูป CSV สำหรับนำไปวิเคราะห์ต่อ |
| `excel/Skill_Matrix_<ฝ่าย>_2570.xlsx` | Skill Matrix รายฝ่าย 7 ฝ่าย (BDD, GMD, MTD, RPM, PSE, RIS, TSMA) |
| `skillmatrix/<ฝ่าย>.md` | สรุป Skill Matrix รายฝ่ายที่เปิดดูบน GitHub ได้ทันที |
| `excel/Executive_Summary_SU_2570.xlsx` | สรุปผู้บริหารภาพรวมฝ่ายสนับสนุน |
| `assets/d3.min.js` | ไลบรารีวาดกราฟ D3 v7.8.5 (ISC License) |

## วิธีเปิด Dashboard

GitHub แสดง `index.html` เป็นซอร์สโค้ด ไม่ใช่หน้าเว็บ จึงต้องเปิดในเครื่อง

1. Clone หรือดาวน์โหลด repo ลงเครื่อง
2. ดับเบิลคลิก `index.html` เปิดด้วย Chrome หรือ Edge ได้ทันที ไม่ต้องติดตั้งอะไรและไม่ต้องต่ออินเทอร์เน็ต
   (ถ้าต่ออินเทอร์เน็ตจะได้ฟอนต์ IBM Plex Sans Thai ที่สวยกว่า)

## แหล่งข้อมูลและสถานะ

- สร้างจาก StaffList (ณ 6 พ.ย. 2569), Role Profile (JD), Job Analysis (JA), OKR 2569 และ Career Development ของแต่ละฝ่าย
- ระดับเป้าหมาย (Target) อนุมานจาก Role Profile ของตำแหน่ง ส่วน **ระดับปัจจุบัน (Current) ยังรอหัวหน้างานประเมิน** ในไฟล์ Excel
- โครงสร้างองค์กรใหม่ (6 ฝ่าย) แผน Mobilize (34 คน) และ OKR 2570 เป็น **ข้อเสนอเพื่อพิจารณา** ยังไม่ใช่มติ
- รายการข้อมูลที่ขาดหรือขัดกันอยู่ในแท็บ "ข้อมูลที่ขาด" และ sheet `09_Data_Issues` ของแต่ละไฟล์ Excel

## การอัปเดต

เมื่อหัวหน้างานกรอกระดับปัจจุบันใน Excel แล้ว ให้ส่งไฟล์กลับมาประมวลผลใหม่ เพื่ออัปเดต Gap และ Dashboard

---
จัดทำ: ฝ่ายสนับสนุน ศว. (MTEC) · พ.ย. 2569
