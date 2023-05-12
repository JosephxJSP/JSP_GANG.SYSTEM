# JSP_GANG.SYSTEM

> ui สำหรับผู้เล่น (ทั่วไป)
  - รายชื่อแก๊งค์
    - ชื่อแก๊งค์
    - สี
    - จำนวนสมาชิก
    - Class
  - กดตรงชื่อแก๊งค์ (จากข้อบน)
    - Popup ขึ้นมาให้เลือกหัวข้อ
      - รายชื่อสมาชิก
      - ขอเข้าร่วมแก๊งค์
  - สตอรี่แก๊งค์
    - แก๊งค์ 1
    - แก๊งค์ 2
    - ผลคะแนนล่าสุด

> ui สำหรับผู้เล่น (สมาชิกแก๊งค์)
  - ข้อมูลแก๊งค์
    - ชื่อ
    - โลโก้
    - สี
    - แม่สี/ลูกสี
    - Class (Limit Slot จาก Class)
    - หัวหน้าแก๊งค์
  - รายชื่อสมาชิก
    - แสดงออนไลน์/ออฟไลน์
  - แชท
  - สตอรี่แก๊งค์ (หากมีสตอรี่อยู่จึงจะแสดงหัวข้อนี้)
    - แก๊งค์ 1
    - แก๊งค์ 2
    - จำนวนคนเล่น
    - ของเดิมพัน
    - เวลาในการเล่น
    - จำนวนแต้ม

> ui สำหรับสภา
  - สร้างแก๊งค์
    - ชื่อ
    - โลโก้
    - สี
    - แม่สี/ลูกสี
    - Class (Limit Slot จาก Class)
  - จัดการแก๊งค์ (แก้ไข)
    - ชื่อ
    - โลโก้
    - สี
    - แม่สี/ลูกสี
    - Class (Limit Slot จาก Class)
    - หัวหน้าแก๊งค์ (ดึงรายชื่อสมาชิกมาให้เลือก)
    - ยุบแก๊งค์
  - คำขอเข้าแก๊งค์
    - แสดงชื่อผู้ขอเข้าร่วม
    - แสดงชื่อแก๊งค์ที่ขอเข้าร่วม
  - ประกาศสตอรี่แก๊งค์
    - แก๊งค์ 1 (ดึงรายชื่อแก๊งค์มาให้เลือก)
    - แก๊งค์ 2 (ดึงรายชื่อแก๊งค์มาให้เลือก)
    - จำนวนคนเล่น
    - ของเดิมพัน
    - เวลาในการเล่น
    - จำนวนแต้ม

> เพิ่มเติม
  - นับคูลดาวน์หลังออกแก๊งค์ หากยังไม่หมดคูลดาวน์ไม่สามารถกดขอเข้าร่วมแก๊งค์อื่นได้
  - export เช็คแก๊งผ่าน cl/sv
  - Config.database
  - เปิด/ปิดการรใช้งานระบบ Job
