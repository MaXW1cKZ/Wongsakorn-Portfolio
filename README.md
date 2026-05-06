# Wongsakorn-Portfolio
A showcase of my projects covering Business Analysis, System Design, and Full-Stack Development. Bridging the gap between business needs and technical solutions.
## 📌 1. Smart Attendance System using AI
**ระบบเช็คชื่ออัจฉริยะด้วยปัญญาประดิษฐ์ (Web Application)**

**🎯 Problem & Solution (ปัญหาและทางแก้):**
การเช็คชื่อแบบเดิมใช้เวลานานและมีปัญหาการทุจริต (ฝากเพื่อนเช็คชื่อ) โครงการนี้จึงพัฒนาระบบเช็คชื่อแบบ Real-time ด้วยเทคโนโลยี **Face Recognition** ร่วมกับ **Liveness Detection** (ตรวจสอบความมีชีวิตเพื่อป้องกันการใช้รูปถ่าย) โดยออกแบบสถาปัตยกรรมแบบกระจายภาระ (Distributed Processing) ให้เครื่องผู้ใช้ช่วยประมวลผลเบื้องต้น เพื่อลดภาระของเซิร์ฟเวอร์

**🧑‍💻 My Roles (บทบาทหน้าที่):**
* **System Analysis & Requirement Gathering:** เก็บความต้องการและวิเคราะห์ระบบสำหรับผู้ใช้งาน 3 กลุ่ม (Student, Teacher, Admin)
* **System Design & Flow:** ออกแบบ Use Case Diagram และการไหลของข้อมูล (Data Flow) ให้สอดคล้องกับ พ.ร.บ. คุ้มครองข้อมูลส่วนบุคคล (PDPA)
* **UI/UX Design:** ออกแบบหน้าจอ (Wireframes & Prototypes) ด้วย Figma โดยเน้น User Experience ที่ใช้งานง่ายและรวดเร็ว

**📈 Business Value (คุณค่าทางธุรกิจ):**
* ลดเวลาการทำธุรการ (Admin Tasks) ของอาจารย์ผู้สอน
* ป้องกันการทุจริตได้ 100% ด้วยระบบ Anti-Spoofing
* มี Dashboard สรุปข้อมูลสถิติการเข้าเรียนแบบ Real-time เพื่อนำไปวิเคราะห์ต่อยอด

---
### 🖼️ System & Design Highlights

*(ใส่รูปภาพที่ 1: System Architecture)*
![System Architecture](./images/smart-attendance-architecture.png)
> **System Architecture:** การออกแบบระบบแบบ Distributed Processing โดยแบ่งการทำงานระหว่าง Client (Face Cropping) และ Server (AI Processing)

*(ใส่รูปภาพที่ 2: Use Case Diagram)*
![Use Case Diagram](./images/smart-attendance-usecase.png)
> **Use Case Diagram:** โครงสร้างการทำงานและสิทธิ์การเข้าถึงของผู้ใช้งานทั้ง 3 กลุ่ม (Student, Teacher, Admin)

*(ใส่รูปภาพที่ 3: User Interface)*
![User Interface](./images/smart-attendance-ui.png)
> **User Interface:** หน้าจอแสดงผลการเช็คชื่อแบบ Real-time และ Dashboard สรุปสถิติ
<br>

## 📌 2. Learning Management System (LMS)
**ระบบบริหารจัดการการเรียนรู้ (IT Project Management)**

**🎯 Problem & Solution (ปัญหาและทางแก้):**
การพัฒนาระบบที่มีสเกลใหญ่มักเจอปัญหาความต้องการ (Requirement) บานปลายและส่งมอบงานไม่ทันเวลา โครงการนี้จึงมุ่งเน้นที่ **การบริหารจัดการโครงการ (Project Management)** อย่างเป็นระบบตามมาตรฐาน PMBOK โดยเริ่มตั้งแต่การเก็บ Requirement ที่ชัดเจน, การวิเคราะห์ผู้มีส่วนได้ส่วนเสีย, ไปจนถึงการแตกย่อยสโคปงานเพื่อให้ทีม Developer ทำงานได้จริง

**🧑‍💻 My Roles (บทบาทหน้าที่):**
* **Project Manager:** บริหารจัดการโครงการแบบ End-to-End, จัดทำโครงสร้างการแบ่งงาน (Work Breakdown Structure - WBS) และประเมินความเสี่ยงของโครงการ
* **Business Analyst:** รวบรวมและวิเคราะห์ความต้องการจาก Stakeholders เพื่อนำมาจัดทำเอกสาร Business Requirements Document (BRD) 
* **Stakeholder Management:** วิเคราะห์และจัดทำตารางประเมินผู้มีส่วนได้ส่วนเสีย เพื่อวางแผนการสื่อสารให้ตรงจุด

**📈 Business Value (คุณค่าทางธุรกิจ):**
* ควบคุมขอบเขตโครงการ (Scope) และงบประมาณให้อยู่ในแผนที่วางไว้
* ลดความผิดพลาดในการสื่อสารระหว่างฝั่ง Business และ ฝั่ง Developer
* ส่งมอบซอฟต์แวร์ที่ตอบโจทย์ความต้องการของผู้ใช้งานได้จริง

---
### 🖼️ Management & Analysis Highlights

*(ใส่รูปภาพที่ 1: Work Breakdown Structure)*
![Work Breakdown Structure](./images/lms-wbs.png)
> **Work Breakdown Structure (WBS):** การแตกย่อยขอบเขตงานทั้งหมดของโครงการ เพื่อใช้ในการวางแผนเวลาและแจกจ่ายงานให้ทีมงาน

*(ใส่รูปภาพที่ 2: Stakeholder Matrix / BRD)*
![Stakeholder & Requirement](./images/lms-stakeholder.png)
> **Stakeholder Management & Requirements:** การวิเคราะห์ผู้มีส่วนได้ส่วนเสีย และการกำหนดความต้องการของระบบอย่างเป็นโครงสร้าง
