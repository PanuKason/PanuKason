# 🔐 Lab : Configure Network Security Appliance Access



---

##  โจทย์ 

Configure Network Security Appliance Access

คุณทำงานเป็นผู้ดูแลระบบความปลอดภัยด้านไอที (IT Security Administrator) สำหรับเครือข่ายองค์กรขนาดเล็ก
คุณจำเป็นต้องเพิ่มความปลอดภัยในการเข้าถึงอุปกรณ์ pfSense ซึ่งตอนนี้ยังคงใช้การตั้งค่าผู้ใช้เริ่มต้น (Default)
งานที่ต้องทำใน Lab นี้คือ

---

## 🛠️ ขั้นตอนที่ 1 :ที่อยู่เว็บไซต์ (URL): http://198.28.56.22/

### 1️⃣ ชื่อผู้ใช้เริ่มต้น (Username): admin รหัสผ่าน (Password): P@ssw0rd
![cf](p1.png)

---

### 2️⃣ สร้างผู้ดูแลระบบ (Administrative User) ใหม่`  
### Username: zolsen
### Password: St@yout!
### Full Name: Zoey Olsen
### Group Membership: admins
![cf](p2.png)

---

### 3️⃣ ตั้งค่า Session Timeout ของ pfSense
### ให้หมดเวลา (timeout) หลังจากไม่มีการใช้งานเป็นเวลา 15 นาที
![cf](p3.png)

---

### 4️⃣ เปลี่ยนรหัสผ่านของบัญชีผู้ใช้เริ่มต้น (admin)
### เปลี่ยนจาก P@ssw0rd
### เป็น 1w0rm4b8
![cf](p4.png)

---

### 5️⃣ ปิดกฎป้องกันการล็อกตัวเองออก (webConfigurator anti-lockout rule) สำหรับ HTTP
![cf](p5.png)

---

### 6️⃣ เสร็จ

![cf](p6.png)

---
