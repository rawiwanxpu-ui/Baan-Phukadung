# บ้านภูกระดึง — บันทึกการปรับปรุงพื้นที่

เว็บแอปบันทึกค่าใช้จ่ายและความคืบหน้าการปรับปรุงพื้นที่บ้านภูกระดึง

## 🌐 เข้าใช้งาน
[https://rawiwanxpu-ui.github.io/Baan-Phukadung](https://rawiwanxpu-ui.github.io/Baan-Phukadung)

## ✨ ฟีเจอร์
- แบ่งงานเป็น Phase (ถมดิน, รั้ว, ระบบไฟฟ้า ฯลฯ)
- บันทึกค่าใช้จ่ายแต่ละรายการ พร้อมประเภทและวันที่
- ตั้งงบประมาณต่อ Phase พร้อม Progress Bar
- อัปโหลดรูปก่อน/หลังปรับปรุง
- ข้อมูลเก็บใน Google Sheets แบบ real-time

## 🗂 โครงสร้าง Google Sheet
ชีท `ค่าใช้จ่าย` มีคอลัมน์:
| RowType | PhaseID | PhaseName | PhaseDesc | Budget | Status | Notes | ExpenseID | ExpDate | ExpDesc | ExpCat | Amount | CreatedAt |
