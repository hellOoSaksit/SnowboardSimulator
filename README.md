# *** โปรเจคนี้เป็นโปรเจคที่นำไปสร้างโปรดักของจริง

# เครื่องจำลองการเล่นสโนว์บอร์ด (Snowboard Simulator)



> **ต้นแบบระบบฝังตัว (Embedded System) ที่พัฒนาขึ้นเพื่อจำลองการเล่นสโนว์บอร์ดในร่ม**  
> 🎯 มุ่งเน้นด้านความปลอดภัย ประสบการณ์ผู้ใช้ และความสามารถในการควบคุมผ่านระบบดิจิทัล  
> 👤 บทบาทของฉัน: Business Analyst (หัวหน้าด้าน BA), System Analyst, UX/UI Designer, Backend Developer

---

## 🔍 ภาพรวมของโครงการ

“เครื่องจำลองการเล่นสโนว์บอร์ด” เป็นโครงงานที่ออกแบบมาเพื่อให้ผู้ใช้สามารถฝึกทักษะการเล่นสโนว์บอร์ดได้โดยไม่ต้องอยู่ในพื้นที่ที่มีหิมะจริง ผ่านการจำลองสภาพแวดล้อมการเล่นที่สมจริง ควบคุมด้วยจอสัมผัส ระบบมอเตอร์ และระบบไฮดรอลิก

> โปรเจกต์นี้แสดงถึงความสามารถของผมในการทำงานแบบข้ามสายงาน (Cross-functional) โดยเฉพาะอย่างยิ่งในบทบาท **Business Analyst** ที่รับผิดชอบตั้งแต่การวิเคราะห์ปัญหา ไปจนถึงการแปลงความต้องการของผู้ใช้เป็นฟีเจอร์จริง

---

## 👤 บทบาทของฉัน

### 📊 Business Analyst (BA) - **เน้นหลัก**
- วิเคราะห์ปัญหาและ **ความต้องการของผู้ใช้เป้าหมาย**
- กำหนด **วัตถุประสงค์หลัก 5 ข้อ** เช่น เพิ่มความปลอดภัย, ลดความเสี่ยงจากอุบัติเหตุ, ฝึกฝนได้ทุกสภาพอากาศ
- วางขอบเขตโครงการ (Scope) และถ่ายทอดความต้องการไปสู่ทีมพัฒนาอย่างชัดเจน
- แปลงความต้องการเป็นฟีเจอร์ระบบ เช่น:
  - ปรับความเร็วของมอเตอร์ได้
  - ระบบไฮดรอลิกเอียงด้านหน้า/หลัง
  - ตรวจจับระยะเพื่อหยุดอัตโนมัติ
- สร้าง **User Flow Diagram ** เพื่ออธิบายการใช้งานอย่างเป็นระบบ
- ประเมินคุณค่าทางธุรกิจ (Business Value) และโอกาสต่อยอดเชิงพาณิชย์


---

## Functional Requirements
![image](https://github.com/user-attachments/assets/95749fd7-2ea1-44ab-a175-601f3776d5b2)

## Non-Functional Requirements
![image](https://github.com/user-attachments/assets/26a9e1b5-2e92-4eaf-8328-bfe16445b36e)

## Use Case Diagram

![UML Ski drawio](https://github.com/user-attachments/assets/f7c15863-2f9b-4af6-a143-c3b794893ddc)

## Use Case Table
![image](https://github.com/user-attachments/assets/8033add6-b73b-4e3c-a09b-353e393a851c)

## Interface Design (UI Overview)

## System Architecture Diagram
![Frame 1 (1)](https://github.com/user-attachments/assets/20aaafe0-0a38-4dd6-8330-2eeba83157d9)

## Requirement Traceability Matrix (RTM)
![image](https://github.com/user-attachments/assets/461920e1-5a50-4114-8ce2-b034d39061d8)

---

## ⚠️ ความเสี่ยงและข้อจำกัด (Risks & Constraints)
* อุปกรณ์ต้นแบบอาจทำงานผิดพลาดหากเซ็นเซอร์ระยะเสียหาย
* ต้องสอบเทียบเซ็นเซอร์และมอเตอร์เป็นระยะเพื่อความแม่นยำ
* ระบบต้องใช้ไฟฟ้าต่อเนื่อง และไม่เหมาะกับสภาพแวดล้อมเปียกชื้น
* รองรับเฉพาะผู้เล่น 1 คนต่อรอบ

## BPNM 2.0
![DOF Ski BPNM2 0 drawio](https://github.com/user-attachments/assets/073e6ce5-8855-4c0f-a459-3219b2eb83f1)

## Lean Canvas : Snowboard Simulator
![01 Problem](https://github.com/user-attachments/assets/14e47f23-52f9-42b0-b8b8-b0e371f11e64)

## 🧪 UX/UI Designer
- ออกแบบหน้าจอใช้งาน (Touchscreen Interface) ด้วยแนวคิด **เรียบง่ายและปลอดภัย**
- สร้างหน้าหลัก (Home), หน้าตั้งค่า (Settings), และหน้าปรับความเร็ว (Speed)
- ติดตั้งจอบนฐานสูง 1 เมตร เพื่อรองรับการใช้งานขณะยืนฝึก
- พัฒนา flow ให้ **เหมาะกับผู้เริ่มต้น** และมีปุ่มหยุดฉุกเฉิน (Emergency Stop)

![image](https://github.com/user-attachments/assets/df3c4234-3b5a-457a-ac43-9e982af4ae7d)
![image](https://github.com/user-attachments/assets/a114bb93-1eb9-4865-b264-e76cf3ffd897)
![image](https://github.com/user-attachments/assets/9be52944-0a2e-402d-be95-0ff449ccee8a)


---

### 🧠 System Analyst (SA)
- ออกแบบ **สถาปัตยกรรมระบบ** และ **แผนภาพลำดับ (Flowchart / Block Diagram)**
- จัดโครงสร้างการสื่อสารระหว่างจอสัมผัส, Arduino Mega, Arduino Uno, Relay, Sensor และ Motor
- อธิบายลำดับการประมวลผลของคำสั่งจากผู้ใช้ถึงฮาร์ดแวร์

![123](https://github.com/user-attachments/assets/0c6df030-46a4-42c4-9e35-096893481a4a)

---

### 🔧 Backend Developer (Embedded)
- พัฒนาโค้ดภาษา C บน Arduino IDE & Visual Studio Code
- เขียนโปรแกรมควบคุม:
  - AC Servo Motor ผ่าน PWM
  - ระบบไฮดรอลิกผ่าน Relay
  - ตรวจจับระยะผู้เล่นผ่าน VL53L0X Sensor
- ตั้งค่าการตัดการทำงานเมื่อผู้ใช้พ้นระยะ เพื่อความปลอดภัย

---

## ⚙️ เทคโนโลยีและอุปกรณ์ที่ใช้

| ประเภท | รายละเอียด |
|--------|-------------|
| MCU    | Arduino Mega 2560, Arduino Uno |
| UI     | หน้าจอสัมผัส BeeNext ขนาด 7 นิ้ว |
| Motion | มอเตอร์ AC Servo 1kW + Gearbox NMRV075 |
| Safety | เซ็นเซอร์ระยะ VL53L0X (Time-of-Flight) |
| Control| รีเลย์ 8 ช่อง, ปั๊มน้ำ, ระบบไฮดรอลิก |
| Power  | แหล่งจ่ายไฟ 12V / 5V |
| Coding | ภาษา C, Arduino IDE, Visual Studio Code |

---

## 🎯 คุณค่าทางธุรกิจ (Business Value)

| เป้าหมายทางธุรกิจ | ฟีเจอร์ที่ตอบสนอง |
|--------------------|---------------------|
| ฝึกซ้อมโดยไม่ใช้หิมะ | ระบบมอเตอร์ปรับความเร็วและไฮดรอลิกจำลองความเอียง |
| ลดความเสี่ยงจากการบาดเจ็บ | เซ็นเซอร์ตรวจจับระยะหยุดอัตโนมัติ |
| ฝึกได้ทุกที่ทุกเวลา | ระบบเคลื่อนย้ายง่าย ใช้พลังงานไฟฟ้า |
| เพิ่มประสบการณ์สมจริง | ปรับองศา, ความเร็ว, แรงตึงพื้น |
| ต่อยอดเป็นธุรกิจฝึกกีฬา | สามารถนำไปใช้งานในฟิตเนสหรือโรงเรียนกีฬา |
