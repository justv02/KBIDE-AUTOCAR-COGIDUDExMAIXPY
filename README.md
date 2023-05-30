# KBIDE-AUTOCAR-COGIDUDExMAIXPY
- โค้ดนี้เป็นส่วนหนึ่งของรถอัตโนมัติ ที่ควบคุมผ่าน KB32 และ Cogidude ทำให้รถวิ่งตามทางอัตโนมัติ
- Remote Dataset เป็นโค้ดที่เก็บรูป dataset เพื่อที่จะนำไปเทรนต่อที่ Colab 
https://colab.research.google.com/drive/1IQ5Ywn9TI0dDZHtpnu5tgU98N7NWTFT6?usp=sharing#scrollTo=5KUUHhn8F6Ed

- ตัวรถจะสามารถเลี้ยวได้นั้นจำเป็นต้องมีกรวยเพื่อเป็นตัวช่วยในการเลี้ยว เนื่องจาก Ai ที่เทรนนั้นจะ Detec หากรวยจากกล้องเพื่อจะให้ตัวรถนั้นคำนวณการเลี้ยวซ้ายหรือขวา

![image](https://user-images.githubusercontent.com/93038026/166404934-898b2a20-e23e-42dd-b980-673b33dec70d.png)


- และเมื่อได้ไฟล์แล้ว นำไฟล์ไป flash ที่โปรแกรม kflash_gui เพื่อที่จะสามารถให้รถสามารถวิ่งอัตโนมัติได้
https://github.com/sipeed/kflash_gui

- ขั้นตอนการทำโดยละเอียดสามารถดูได้ที่ลิงค์นี้ (เฉพาะเดินอัตโนมัติ)
https://www.youtube.com/watch?v=ZlzB1Bnp5cg

![image](https://user-images.githubusercontent.com/93038026/166404442-20238047-4326-4ed3-885b-4f0e22609c7b.png)

#Maixpy
- 1.เมื่อตรวจจับเจอสิ่งของจะทำการส่ง logic = 1 ไปยังขา 18 
- 2.เมื่อตรวจจับเจอสิ่งของจะทำการส่ง logic = 1 ไปยังขา 18 และทำการถ่ายรูปไว้ 
- 3.ใช้สำหรับถ่ายรูปปกติ
- 4.Yolo Detection Person

![image](https://user-images.githubusercontent.com/93038026/166405014-5e77cb59-d8dd-4cb2-921e-62f6782ce8e3.png)
![image](https://user-images.githubusercontent.com/93038026/166405129-1272e1cf-dbda-4d15-984e-9d9a24b6b76b.png)


#Diagram
![image](https://user-images.githubusercontent.com/93038026/166404559-aacb27f7-78f3-4c66-bbe0-b1c963b97292.png)

#Kflash
- ไฟล์เฟรชโมเดล YOLO 20 class และ ไฟล์เฟรชรอมบอร์ด Cogidude

จัดทำโดย
- Mr. Supakit Singkaew
- Mr. Nontawat Matong
- Mr. Siwat Chauycharoen

อาจารย์ที่ปรึกษา
- ผศ.ดร.ขวัญชัย เอื้อวิริยานุกูล
- นายณัฐชาสิทธิ์ ชูเกียรติขจร
- นายอนุพงศ์ ไพโรจน์
- นายปรัชญ์ ปิยะวงศ์วิศาล
