# Python_datavizz
1.วิธีการ install python มีขั้นตอนทั้งหมด 6 ขั้นตอน

ขั้นตอนที่ 1 ทำการ Download Python โดยการ Search คำว่า Miniconda ที่ Google 
![test git](1.png)
*เลือก Version ตามการใช้งานของคอมพิวเตอร์ เเนะนำให้เลือก Python version 3.7 ใหม่ล่าสุด*
ขั้นตอนที่ 2 ติดตั้ง Python version 3.7
![test git](.2.jpg)

ขั้นตอนที่ 3 เปิดใช้งาน Anaconda Prompt
![test git](.3.jpg)
*โดยการกดคีย์ลัด กดที่ปุ่มโฮมวินโดว์+S เพื่อค้นหา Anaconda Prompt*

ขั้นตอนที่ 4 เปิดใช้งาน Anaconda Prompt เเละพิมพ์ Python เพื่อเช็ค version ว่าตรงตามที่ติดตั้งไป
![test git](.31.jpg)

ขั้นตอนที่ 5 ติดตั้ง Package matplotlib ด้วยคำสั่ง conda install matplotlib 
![test git](.41.jpg) 
![test git](.42.jpg)
*จากนั้นให้พิมพ์ y เเล้วกด Enter เป็นอันเสร็จการติดตั้ง Package*

ขั้นตอนที่ 6 การทำให้โปรเเกรมรู้ที่อยู่ของโฟลเดอร์ที่ใช้เก็บไฟล์งานด้วยคำสั่ง cd

![test git](.5.jpg)
*ทำการ copy ที่อยู่ของโฟลเดอร์ที่สร้างไว้เผื่อเก็บงาน*

![test git](.6.jpg)
*เนื่องจากเก็บไฟล์งานไว้ที่ Driver D ให้ใช้คำสั่ง d: จะสามารถเปลี่ยนให้โปรเเกรมรู้ที่อยู่ของโฟลเดอร์งานได้ถูกต้อง*

![test git](.7.jpg)
*จากนั้นใช้คำสั่ง cd + เเหล่งที่อยู่ของโฟลเดอร์ที่ต้องการเก็บ*

![test git](.8.jpg)
*จากนั้นใช้คำสั่ง jupyter notebook เพื่อเปิดการใช้งาน python ได้เลย*

2.การใช้งาน Colab มีขึ้นตอนดังนี้

ขั้นตอนที่ 1 ทำการ Search คำว่า Google colab
![test git](q9.jpg)
*คลิกอันเเรก*

![test git](.10.jpg)
*จากนั้นทำการ sign in ด้วย email*

![test git](.11.jpg)
*เมื่อ sign in เรียบร้อยเเล้ว จะขึ้นหน้านี้ ให้ทำการกดที่ NEW PYTHON 3 NOTEBOOK*
 ![test git](.12.jpg)

 ขั้นตอนที่ 2 เป็นวิธีเปลี่ยนTheme โดยกดที่ Tools>>Settings
 ![test git](.13.jpg)

 ![test git](.14.jpg)
 *เลือก Theme ตามที่ต้องการ*
![test git](.15.jpg)

3.การใช้งาน Github

ขั้นตอนที่ 1 เข้าไปที่ Github.com เเละทำการสมัครใช้งาน Github 
![test git](.16.jpg)
*กด Sign up*
![test git](.17.jpg)
*ทำการ create your account*

ขั้นตอนที่ 2 install git ในโปรเเกรม Anaconda โดยพิมพ์ conda install -c anaconda git
![test git](.20.jpg)

![test git](.18.jpg)
*จากนั้นกด New repository เพื่อสร้างที่เก็บ*
![test git](.19.jpg)
*ตั้งชื่อ เเละ เลือกให้เป็น Pubilc เพื่อให้ทุกคนสามารถเข้ามาดูงานเราได้ จากนั้นกดที่ Creat repository เป็นอันเสร็จ*

![test git](.21.jpg)
*จากนั้น copy URL. จากที่เราสร้างไว้*

ขั้นตอนที่ 3 เป็นการเชื่อมการทำงานระหว่าง Github กับ Python

 ![test git](.22.jpg)
 *โดยการ ใช้คำสั่ง github clone ตามด้วย URL. ที่ copy มา*

 ![test git](.23.jpg)
 *จะเห็นว่าโฟลเดอร์ที่สร้างจาก github จะเชื่อมกับ python*

 ![test git](.24.jpg)
 *จากนั้น ใช้คำสั่ง cd พิมพ์ตัวเเรกของโฟลเดอร์ เเล้วกด Tab ชื่อโฟลเดอร์งานจะขึ้นทันที*

 ขั้นตอนที่ 4 เป็นการเพิ่มไฟล์งานเข้าไปใน github

 ![test git](.25.jpg)

 *ใช้คำสั่ง git status เพื่อดูว่าไฟล์งานไหนที่ยังไม่ได้เชื่อมกับ github บ้างหรือ ยังไม่ได้ sign กับ internet จะเเสดงให้เห็นเป็น สีเเดง*

 ![test git](.26.jpg)
 *จากนั้นใช้คำสั่ง git add ตามด้วยชื่อไฟล์ที่ยังไม่เชื่อมกับ github*

 ![test git](.27.jpg)
 *ใช้คำสั่ง git commit -m "test git"*

![test git](.28.jpg)
*ใช้คำสั่ง git config --global user.email "emailที่ใช้ในgithub" เเละ ใช้คำสั่ง git config --global user.name "ชื่อuserที่ใช้ใน github" เพื่อเข้าใช้งาน*

![test git](.29.jpg)
*จากนั้นใช้คำสั่ง git push ตามด้วยใส่ Username เเละ Password ที่ใช้สมัคร Github*

***...เป็นอันเสร็จเรียบร้อย***


