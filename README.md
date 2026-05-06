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
