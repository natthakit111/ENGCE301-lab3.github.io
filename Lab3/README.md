🧪 ENGCE301 – LAB 3
Agile Requirements & Use Case Modeling + Web Layout

System: ENGCE301 Lab Submission Portal

กลุ่ม: NightFall
สมาชิก:

Name	Student ID	Role	GitHub
นายจักรกฤษณ์ จาปัญญะ	66543206040-8	Team Leader / Tester / Frontend	@BakaZeno
นายเมย์คาร์ สุวรรณวิสุทธิ	66543206085-3	Frontend	@Mekha1104
นายปรเมษฐ สุริคำ	66543206038-2	Frontend / System Analysis	@porameter
นายณัฐกิตติ์ ยั่งยืนปิยรัตน์	66543206014-3	Backend	@natthakit111
นายจิรวัฒน์ มาลัยวรรณ	66543206070-5	Backend	@Jirawat66
📌 1. LAB 3 Overview

งาน LAB 3 ประกอบด้วย 2 ส่วนหลัก:

1) Requirements Lab

วิเคราะห์ SRS

จัดทำ User Stories → Product Backlog

วาด Use Case Diagram

เขียน Use Case Scenarios อย่างน้อย 2–3 UC

2) Web Lab (HTML/CSS)

สร้างหน้าเว็บต้นแบบของระบบ ENGCE301 Lab Submission Portal รวม 3 หน้า:

index.html – หน้าแรก + Upcoming Labs + My Status

my-labs.html – ตารางสถานะ Lab ของนักศึกษา

about.html – อธิบาย Mapping ระหว่าง SRS → User Stories → Use Case → UI

styles.css – ปรับแต่ง UI ตาม Color Palette ของกลุ่ม

โฟลเดอร์นี้รวมทุกไฟล์ที่ใช้ส่งงานใน LMS

📌 2. Product Backlog (User Stories)

ลิงก์ไปยัง Product Backlog (Trello):
👉 https://trello.com/b/0uQocTSG/nightfall

ตัวอย่าง User Stories ที่อยู่ใน Backlog:

US-01: นักศึกษาต้องการดูรายการ LAB

US-02: นักศึกษาต้องการดูรายละเอียด LAB

US-03: นักศึกษาต้องการส่งงาน LAB

US-04: นักศึกษาต้องการดูสถานะ LAB ของตัวเอง

US-05: นักศึกษาต้องการรู้ว่าส่งช้าหรือไม่

US-06–08: มุม Instructor ได้แก่ Create Lab / View Submissions / Grade Submission

Backlog ทั้งหมดถูกเรียงลำดับความสำคัญ (priority) และใส่ Acceptance Criteria ครบถ้วน

📌 3. Use Case Diagram

Use Cases หลักที่ระบบมี:

UC-01: View Lab List

UC-02: View Lab Details

UC-03: Submit Lab

UC-04: View My Lab Status

UC-05: Create Lab (Instructor)

UC-06: Grade Submission (Instructor/TA)

Actors:

Student

Instructor

TA (optional)

📌 4. Use Case Scenarios

Use Cases ที่เขียน Scenario ครบถ้วน:

UC-03: Submit Lab

UC-04: View My Lab Status

UC-06: Grade Submission

ประกอบด้วย:

Preconditions

Postconditions

Main Flow

Alternative Flows (AF-1, AF-2, ...)

📌 5. รายการไฟล์ที่จัดส่งในโฟลเดอร์ lab3/
lab3/
├─ README.md                (ไฟล์นี้)
├─ LAB3_SRS.md
├─ LAB3_UserStories.md
├─ Use Case Scenario.md
├─ Use Case Diagram.pdf   (ไฟล์ diagram)
├─ index.html
├─ my-labs.html
├─ about.html
├─ styles.css
└─ (ไฟล์อื่น ๆ ที่เกี่ยวข้อง)

📌 6. Web Lab (HTML/CSS)
6.1 ลิงก์เว็บไซต์ที่ Deploy แล้ว

(เช่น GitHub Pages หรือ Vercel)
👉 <ลิงก์ Deploy ที่นี่>

6.2 ลิงก์ Git Repository

👉 https://github.com/natthakit111/ENGCE301-Nightfall/tree/main/Lab3

ภายใน repository ต้องมีไฟล์:

index.html

my-labs.html

about.html

styles.css

README.md


📌 7. Mapping: Requirements → User Stories → Use Cases → UI
Requirements	User Story	Use Case	UI Implementation
FR-01 View Lab List	US-01	UC-01	Section “Upcoming Labs” (index.html)
FR-02 View Lab Details	US-02	UC-02	ส่วนคำอธิบาย Lab / Link to details
FR-03 Submit Lab	US-03	UC-03	หน้าแบบฟอร์ม / ปุ่มใน Lab Card
FR-04 Late Submission	US-05	UC-03 (AF-2, AF-3)	Status Tag: status-late
FR-08 View My Lab Status	US-04	UC-04	ตารางสถานะใน my-labs.html
NFR-01 Usability	–	–	Responsive Layout + Clean Navigation
NFR-02 Performance	–	–	CSS Optimization + Lightweight UI
📌 8. Checklist สำหรับการส่งงาน

ก่อนส่งงาน ตรวจว่าครบแล้ว:

✔ Requirements

 อ่านและวิเคราะห์ SRS

 แก้ไขและจัดทำ User Stories ใน Backlog

 วาด Use Case Diagram

 เขียน Use Case Scenarios (อย่างน้อย 2–3 UC)

✔ Web Lab

 ปรับข้อความ Hero section

 เพิ่ม Upcoming Labs อย่างน้อย 2 ใบ

 แก้ My Labs ให้ตรงกับสถานะจริงของระบบ Mock

 เลือก Color Palette และ Font

 ปรับ margins / paddings / hover effects

 ตรวจ layout ทุกหน้าว่าแสดงถูกต้อง

✔ Final Submission

 ลิงก์ Trello / Jira

 ลิงก์ Use Case Diagram

 ลิงก์ Use Case Scenarios

 ลิงก์ Git Repository

 ลิงก์ Deployment