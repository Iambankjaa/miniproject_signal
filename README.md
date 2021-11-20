# Audio Signals Analysis & Mixing
 
  รายงานนี้เป็นส่วนหนึ่งของรายวิชา Introduction to Signals & Systems รหัสวิชา 010123106 ภาคเรียนที่ 1 ปีการศึกษา 2564 สาขาวิชาคอมพิวเตอร์ ภาควิชาไฟฟ้าและคอมพิวเตอร์ คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าพระนครเหนือ

## หัวข้อที่ทำการเลือกทำ
ตัวเลือกที่ 2
- เลือกไฟล์ สัญญาณเสียง ( เช่น .wav) และโหลดไฟล์เสียง เช่น ใช้คำสั่ง audioread()
- สร้างเสียงจากข้อมูลที่อ่านเป็นอินพุต
- แสดงรูปคลื่นสัญญาณใน time domain
- แสดง Frequency Spectrum ของสัญญาณเสียง (Sounds) โดยใช้ FFT
- ผู้ใช้สามารถเลือกสัญญาณเสียงได้มากกว่าหนึ่ง และรวมสัญญาณเสียงให้เป็นสัญญาณเสียงเดียว
เพื่อการวิเคราะห์และแสดงผล

## วัตถุประสงค์
1.เพื่อศึกษาและทำความเข้าใจเกี่ยวกับโปรแกรม mathlab

2.เพื่อศึกษาและทำความเข้าใจเกี่ยวกับ Fourier Series

3.เพื่อให้สามารถแก้ไขสัญญาณเสียงที่มีได้

## ขอบเขตของงาน
1.สามารถใช้ไฟล์เสียง .Wav เป็นอินพุตได้

2.สามารถแสดงรูปคลื่นสัญญาณใน time domain ได้

3.สามารถแสดง Frequency Spectrum ของสัญญาณเสียง (Sounds) ได้

4.สามารถรวมสัญญาณเสียงได้อย่างน้อย 2 สัญญาณ เป็น 1 สัญญาณได้

## การดำเนินการ
	
  ทำการสร้างหน้าต่าง GUI โดยมีฟังก์ชั่นสามารถ import ไฟล์ .wav มาทำการ plot ได้ 
โดยสามารถ import ได้ 2ไฟล์ แสดงกราฟสัญญาณเสียง 1 ไฟล์ ต่อ 1 กราฟ และสามารถพล็อตกราฟแบบใช้ FFT(Fast Fourier Transformation) 
โดยมีให้เลือกสามรูปแบบ คือ เฉพาะไฟล์เสียงที่ 1 ,เฉพาะไฟล์เสียงที่ 2 และทั้งสองไฟล์เสียงรวมกัน
        
 ## วิธีการใช้งาน
 ![image](https://i.imgur.com/TdjMWSv.png)
                         
1.เลือกไฟล์เสียงโดยการกดปุ่ม Import 
 
2.เมื่อเลือกไฟล์เสียงแล้ว จะแสดงกราฟเสียง เราสามารถซูมเข้าหรือซูมออกกราฟได้จาก เครื่องมือแว่นขยายบนกราฟ และสามารถกลับรูปแบบเริ่มต้นโดยกดเครื่องมือรูปบ้าน

3.กดปุ่ม Plot เพื่อแสดงกราฟ FFT(Fast Fourier Transformation) โดยไฟล์จะเลือกมาแสดง จะเลือกจากกล่องเครื่องมือด้านข้าง โดยจะแบ่งเป็น เฉพาะไฟล์เสียงที่ 1 ,เฉพาะไฟล์เสียงที่ 2 และทั้งสองไฟล์เสียงรวมกัน ถ้ามีการเปลี่ยนตัวเลือกใหม่ ต้องกดปุ่ม Plot ใหม่อีกครั้ง เพื่อแสดงผล
 
 ## อ้างอิง
  https://www.mathworks.com/help/matlab/ref/fft.html 
  
  https://www.mathworks.com/discovery/matlab-gui.html
   ## สมาชิก
 กรณ์ เพชรเจริญกุล 	รหัสนักศึกษา 5801011611019
 ธนวัฒน์ โชติศิริ 	รหัสนักศึกษา 5901012620151
 นวัต พงษ์ภาสุระ 	รหัสนักศึกษา 5901012610074
 สราวุธ จันทร์เทศ	รหัสนักศึกษา 6001012610089
 
 https://youtu.be/H-UpNcQvpUE 
