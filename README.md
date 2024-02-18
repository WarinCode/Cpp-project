<div align="center">
  <img src="./imgs/KU.png" width="300px" height="300px" > 
</div>

<h1 align="center">มหาวิทยาลัยเกษตรศาสตร์วิทยาเขตศรีราชา</h1>

> ส่งงาน project วิชา Computer Programming ปี 1 ภาคปลาย

<h1 align="center">โปรแกรมระบบจัดการสินค้า</h1>

รายละเอียดโปรเจค : โปรเจคนี้ทำเกี่ยวกับ โปรเแกรมระบบจัดการสินค้าใน ร้านสินค้า , ร้านขายของ , ร้านสดวกซื้อ โดยการใช้งานเมื่อรันโปรแกรมผ่าน CLI ของโปรแกรมจะมีตัวเลือกคือตัวเลขให้ผู้ใช้งานป้อนตัวเลขใน
cmd , terminal หรือ powershell ก็จะแสดงข้อมูล หรือ การจัดการกับสินค้าต่างๆ ตามฟีเจอร์ที่ได้ระบุไว้ และ เมื่อมีการจัดการกับข้อมูลสินค้าโปรแกรมจะมีการเขียนไฟล์ข้อมูล <code>data.txt</code>
เพื่อจัดเก็บข้อมูลการเปลี่ยนแปลงต่างๆของสินค้า

เป็นโปรเจคแบบง่ายๆ โดยใช้ภาษา C++ ในการเขียนโปรแกรม

---

### เวลาที่ใช้ในการทำโปรเจค

[![wakatime](https://wakatime.com/badge/user/68e3e2dc-451c-45ef-bca8-9fc3ad60e2f9/project/018dad0f-df31-4661-aeef-7cab5890fdeb.svg)](https://wakatime.com/badge/user/68e3e2dc-451c-45ef-bca8-9fc3ad60e2f9/project/018dad0f-df31-4661-aeef-7cab5890fdeb)

วันที่เริ่มทำโปรแกรม : 13/2/2567

วันที่ทำโปรแกรมเสร็จ : ยังไม่เสร็จ

### ฟีเจอร์ของโปรแกรม
- เพิ่มสินค้า
- ลบสินค้า
- แก้ไขสินค้า
- สั่งซื้อสินค้า
- เพิ่มสินค้าใน stock
- อ่านเขียนไฟล์ข้อมูล

### ขั้นตอนการติดตั้งและใช้งานโปรเจค

1. ดาวน์โหลด project
```
git clone https://github.com/WarinCode/CPP-project.git
```

2. เปิด terminal แล้วเข้าไปใน directory ของโปรเจค
```
cd CPP-project
```

3. compile ไฟล์ main.cpp จะได้ตัวโปรแกรม program.exe ขึ้นมา
```
g++ main.cpp -o program.exe
```

4. เปิดตัวโปรแกรม program.exe หรือใช้คำสั่งนี้จะเปิดโปรแกรมขึ้นมาใน terminal แทน
```
./program.exe
```

<div align="center">
<img src="imgs/preview.jpg" alt="preview" height="100%" width="100%"/>
</div>

5. ถ้าทำตามขั้นตอนที่ว่ามาทั้งหมดก็ถือเกือบพร้อมใช้งานแต่ที่สำคัญในส่วนของการอ่านและเขียนไฟล์ข้อมูลให้ทำการเขียนทับ path ในส่วนของ method read และ write ของ class File
<code>string path = R"(C:\Users\ACER USER5949486\Desktop\CPP-project\txt\data.txt)"</code> โดยให้เปลี่ยนเป็นชื่อผู้ใช้งานแทน <code>string path = R"(C:\Users\user\Desktop\CPP-project\txt\data.txt)"</code>
ให้เปลี่ยนจาก <code>user</code> เป็นเครื่องชื่อผู้ใช้งานแทน

ปล. สามารถนำไปใช้งานหรือพัฒนาต่อยอดได้ฟรี แต่ข้อห้ามคือห้าม copy code ไปส่งเป็นงานกลุ่มโปรเจคของตัวเองทั้งที่ไม่ได้ทำเอง หรือ นำโปรแกรมไปขาย

### รายชื่อสมาชิกในกลุ่ม
1. นาย วรินทร์ สายปัญญา รหัสนิสิต 6630250435 หมู่เรียน 881
