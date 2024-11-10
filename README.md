## Cool Book 1
# LEDC_FADE
โปรเจคนี้เป็นการทำให้ LED ในบอร์ด ESP32 ค่อนๆสว่างและดับตามเวลาที่กำหนด

# ขั้นตอนการทำ
กดเข้าไปที่หัวข้อ Show Example

![cl1](https://github.com/user-attachments/assets/d543f2ff-5569-45a0-bd7c-0c55190fdea9)

หลังจากเลือกแล้ว ให้ค้นหาและเลือกคำว่า  Ledc_fade จากนั้นให้กด create project using example Ledc_fade ตามขั้นตอนดังรูป

![cl1 1](https://github.com/user-attachments/assets/a2596fe7-fb2e-4bcf-a953-aeab712ed5c2)

#การต่อวงจร
 ต่อขาGPIO18 ไปที่ LED1 ,ต่อขาGPIO19 ไปที่ LED2,ต่อขาGPIO14 ไปที่ LED3,ต่อขาGPIO5 ไปที่ LED4 ดังรูป

 ![cl1 4](https://github.com/user-attachments/assets/6b440636-5f4b-4a21-a430-483c81e8a11d)

#การ build
เมื่อทำการต่อวงจรเรียบร้อยแล้วให้ทำการอัพโหลดโค้ดลงบอร์ด แล้วกด build ผลลัพธ์ที่ได้จะเป็นดังรูป

![cl1 2](https://github.com/user-attachments/assets/98c9c745-7810-48d0-aac7-4c77496ae53a)

# ส่วนที่ปรับปรุงแก้ไขการใช้งานมีดังนี้
ส่วนของไฟล์ main.c บรรทัดที่ 63 จะเป็นการปรับค่าให้ LED เร็วขึ้นหรือช้าลง

![cl1 3](https://github.com/user-attachments/assets/59a82264-d07a-4e04-914c-e6f4fd2061eb)

#วิดีโอการแสดงผล

https://drive.google.com/file/d/1Y9BT2CUiUhf-IjdybXC-zHhhCZ1SuILN/view?usp=sharing

