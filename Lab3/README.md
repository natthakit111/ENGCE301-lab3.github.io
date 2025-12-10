# 🧪 ENGCE301 – LAB 3  
## Agile Requirements & Use Case Modeling + Web Layout  
**System: ENGCE301 Lab Submission Portal**

กลุ่ม: **NightFall**  

## 👥 Team Members

| Name | Student ID | Role | GitHub |
|------|-----------|------|--------|
| นายจักรกฤษณ์ จาปัญญะ | 66543206040-8 | Team Leader / Tester / Frontend | @BakaZeno |
| นายเมย์คาร์ สุวรรณวิสุทธิ | 66543206085-3 | Frontend | @Mekha1104 |
| นายปรเมษฐ สุริคำ | 66543206038-2 | Frontend / System Analysis | @porameter |
| นายณัฐกิตติ์ ยั่งยืนปิยรัตน์ | 66543206014-3 | Backend | @natthakit111 |
| นายจิรวัฒน์ มาลัยวรรณ | 66543206070-5 | Backend | @Jirawat66 |

---

# 📌 1. LAB 3 Overview  

งาน LAB 3 แบ่งเป็น 2 ส่วนหลัก:

## **1) Requirements Lab**
- วิเคราะห์เอกสาร SRS  
- จัดทำ User Stories → Product Backlog  
- วาด Use Case Diagram  
- เขียน Use Case Scenarios อย่างน้อย 2–3 UC  

## **2) Web Lab (HTML/CSS)**
สร้างหน้าเว็บต้นแบบของระบบ Lab Submission Portal ได้แก่:

- `index.html` – หน้าแรก + Upcoming Labs + My Status  
- `my-labs.html` – ตารางสถานะ LAB ของนักศึกษา  
- `about.html` – อธิบาย Mapping จาก SRS → Stories → Use Case → UI  
- `styles.css` – ปรับธีม สี และ layout ให้สวยงามตามกลุ่ม  

โฟลเดอร์นี้รวบรวมทุกไฟล์ที่ใช้ส่งใน LMS

---

# 📌 2. Product Backlog (User Stories)

ลิงก์ Backlog ของกลุ่ม (Trello / Jira / Miro):

https://trello.com/b/0uQocTSG/nightfall

ตัวอย่าง User Stories:
- **US-01:** ดูรายการ LAB  
- **US-02:** ดูรายละเอียด LAB  
- **US-03:** ส่งงาน LAB  
- **US-04:** ดูสถานะ LAB ของตัวเอง  
- **US-05:** ระบบแจ้งเตือนเมื่อส่งงานช้า  
- **US-06–08:** ฟีเจอร์ของ Instructor เช่น Create Lab / View Submissions / Grade Submission  

> ทั้งหมดมี Acceptance Criteria ครบตามมาตรฐาน Agile  

---

# 📌 3. Use Case Diagram

Use Case หลัก:
- UC-01 View Lab List  
- UC-02 View Lab Details  
- UC-03 Submit Lab  
- UC-04 View My Lab Status  
- UC-05 Create Lab  
- UC-06 Grade Submission  

Actors:
- Student  
- Instructor  
- TA (optional)

---

# 📌 4. Use Case Scenarios

Use Cases ที่เขียนครบ:
- UC-03 Submit Lab  
- UC-04 View My Lab Status  
- UC-06 Grade Submission  

ประกอบด้วย:
- Preconditions  
- Postconditions  
- Main Flow  
- Alternative Flows  

---

# 📌 5. รายการไฟล์ทั้งหมดภายในโฟลเดอร์ lab3/

📌 5. รายการไฟล์ทั้งหมดภายในโฟลเดอร์ `lab3/`

```text
lab3/
├─ README.md
├─ LAB3_SRS.md
├─ LAB3_UserStories.md
├─ Use Case Scenario.md
├─ Use Case Diagram.pdf
├─ index.html
├─ my-labs.html
├─ about.html
├─ styles.css
└─ (ไฟล์อื่น ๆ ที่เกี่ยวข้อง)

---

# 📌 6. Web Lab (HTML/CSS)

## 6.1 เว็บไซต์ที่ Deploy แล้ว  
👉 **<ลิงก์ Deploy ที่นี่>**

## 6.2 Git Repository  
👉 https://github.com/natthakit111/ENGCE301-Nightfall/tree/main/Lab3

ภายใน Repo มี:
- index.html  
- my-labs.html  
- about.html  
- styles.css  
- README.md  


---

# 📌 7. Mapping: Requirements → User Stories → Use Cases → UI

| Requirements | User Story | Use Case | UI Implementation |
|-------------|------------|----------|--------------------|
| FR-01 View Lab List | US-01 | UC-01 | Upcoming Labs (`index.html`) |
| FR-02 View Lab Details | US-02 | UC-02 | รายละเอียด LAB (ใน card/section) |
| FR-03 Submit Lab | US-03 | UC-03 | ปุ่ม/ฟอร์มส่งงาน |
| FR-04 Late Submission | US-05 | UC-03 AF-2/AF-3 | status-late (สีแดง) |
| FR-08 View My Lab Status | US-04 | UC-04 | ตาราง My Labs (`my-labs.html`) |
| NFR-01 Usability | – | – | Responsive Layout + Navigation |
| NFR-02 Performance | – | – | Lightweight CSS |

---

# 📌 8. Checklist ส่งงาน

## ✔ Requirements
- [ ] อ่าน SRS  
- [ ] ทำ User Stories + Backlog  
- [ ] ทำ Use Case Diagram  
- [ ] ทำ Use Case Scenarios  

## ✔ Web Lab
- [ ] ปรับ Hero section  
- [ ] เพิ่ม Upcoming Labs อย่างน้อย 2 การ์ด  
- [ ] ปรับ My Labs ให้ตรงกับข้อมูล mock  
- [ ] Theme สี + Font + Layout สวยงาม  
- [ ] ตรวจ Responsive ครบทุกหน้า  

## ✔ ส่งงานบน LMS
- [ ] ลิงก์ Backlog  
- [ ] ลิงก์ Use Case Diagram  
- [ ] ลิงก์ Use Case Scenarios  
- [ ] ลิงก์ Git Repo  
- [ ] ลิงก์เว็บ Deploy  

---