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
<img width="433" height="801" alt="Architecture" src="https://github.com/user-attachments/assets/b486e751-897b-46d0-9cff-7096570c1b90" />
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
<br>

## 📌 3. ExpertConnect Platform
**แพลตฟอร์มสื่อกลางถาม-ตอบปัญหาพร้อมระบบ Escrow (Cloud Application)**

**🎯 Problem & Solution (ปัญหาและทางแก้):**
การจ้างงานหรือปรึกษาผู้เชี่ยวชาญออนไลน์มักมีความเสี่ยงเรื่องการฉ้อโกง (เบี้ยวงาน/ไม่จ่ายเงิน) ระบบนี้จึงถูกออกแบบมาให้มี **Escrow System (ตัวกลางถือเงิน)** เพื่อสร้างความมั่นใจให้ทั้งสองฝ่าย พร้อมทั้งออกแบบสถาปัตยกรรมบน Cloud ให้รองรับการขยายตัวของผู้ใช้งาน (Scalability) ในอนาคตได้อย่างมีประสิทธิภาพ

**🧑‍💻 My Roles (บทบาทหน้าที่):**
* **System Architecture Design:** ออกแบบโครงสร้างพื้นฐานระบบ (Infrastructure) บน AWS โดยใช้สถาปัตยกรรม Microservices (ECS Fargate, ALB, RDS, S3)
* **Business Logic & Workflow:** ออกแบบเส้นทางการใช้งาน (User Journey) และการไหลของเงินในระบบตั้งแต่เริ่มตั้งคำถามจนถึงการจ่ายเงินให้ผู้เชี่ยวชาญ
* **CI/CD Pipeline:** วางระบบการทำ Continuous Integration/Continuous Deployment ผ่าน GitHub Actions เพื่อความรวดเร็วในการส่งมอบฟีเจอร์

**📈 Business Value (คุณค่าทางธุรกิจ):**
* สร้างความน่าเชื่อถือให้กับแพลตฟอร์มและลดข้อพิพาทระหว่างผู้ใช้งาน
* ระบบมีความเสถียรและสามารถปรับขนาด (Scale) เพื่อรองรับ Traffic ได้อัตโนมัติ

---
### 🖼️ Architecture & Flow Highlights

*(ใส่รูปภาพที่ 1: AWS Architecture)*
![System Architecture](./images/expertconnect-architecture.png)
> **Cloud Architecture (AWS):** โครงสร้างระบบที่ออกแบบเพื่อรองรับความปลอดภัย (Security) และการขยายตัว (Scalability)

*(ใส่รูปภาพที่ 2: Business Workflow)*
![Business Workflow](./images/expertconnect-flow.png)
> **Business Workflow:** การออกแบบ Flow การทำงานของระบบสื่อกลาง (Escrow System)

<br>
<hr>
<br>

## 📌 4. Hotel Booking System
**ระบบจัดการฐานข้อมูลสำหรับการจองห้องพักโรงแรม (Database Design)**

**🎯 Problem & Solution (ปัญหาและทางแก้):**
ธุรกิจโรงแรมมีข้อมูลที่ต้องจัดการจำนวนมากและซับซ้อน ทั้งข้อมูลลูกค้า, ห้องพัก, การชำระเงิน และสถานะการจอง โครงการนี้จึงมุ่งเน้นไปที่การวิเคราะห์และออกแบบฐานข้อมูลเชิงสัมพันธ์ (Relational Database) เพื่อให้ระบบจัดการข้อมูลได้อย่างถูกต้อง รวดเร็ว และไม่ซ้ำซ้อน

**🧑‍💻 My Roles (บทบาทหน้าที่):**
* **Database Design:** วิเคราะห์กระบวนการทางธุรกิจ (Business Rules) ของโรงแรม และนำมาออกแบบ Entity-Relationship Diagram (ERD)
* **Data Standardization:** จัดทำพจนานุกรมข้อมูล (Data Dictionary) เพื่อส่งต่อโครงสร้างข้อมูลที่เป็นมาตรฐานให้กับทีม Developer ใช้ในการพัฒนา

---
### 🖼️ Database Design Highlight

*(ใส่รูปภาพที่ 1: ER Diagram)*
![ER Diagram](./images/hotel-erd.png)
> **Entity-Relationship Diagram (ERD):** โครงสร้างฐานข้อมูลที่แสดงความสัมพันธ์ของระบบการจองห้องพัก (รองรับ 3 บทบาท: Admin, Customer, Receptionist)
