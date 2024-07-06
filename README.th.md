# README.md
- [English](README.md)
- [Deutsch](README.de.md)
- [Spanish](README.es.md)
- [Finnish](README.fi.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [Indonesian](README.id.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)
- [Norwegian](README.nb.md)
- [Dutch](README.nl.md)
- [Polish](README.pl.md)
- [Portuguese](README.pt.md)
- [Swedish](README.sv.md)
- [ภาษาไทย](README.th.md)
- [Turkish](README.tr.md)
- [Ukrainian](README.uk.md)
- [Vietnamese](README.vi.md)

# iCroc - แอพ CLI ของ Croc สำหรับ iOS และ macOS

ดาวน์โหลด [เวอร์ชันล่าสุดจาก App Store](https://apps.apple.com/us/app/id6444355962)

V1.3
---
- ออกแบบอินเทอร์เฟซและตรรกะการทำงานของแอพใหม่ทั้งหมด
- อัปเกรดเวอร์ชัน croc ที่ฝังเป็น v10.0.8
- เพิ่มการสนับสนุนฟีเจอร์ Handoff สำหรับ iOS และ macOS
- รองรับหลายภาษา

V1.1
---
- ออกแบบไอคอนแอพใหม่
- แก้ไขข้อบกพร่องและปรับปรุงประสิทธิภาพ

V1.0
---
croc เป็นเครื่องมือที่ช่วยให้คอมพิวเตอร์สองเครื่องสามารถถ่ายโอนไฟล์และโฟลเดอร์ได้อย่างง่ายดายและปลอดภัย เท่าที่ทราบ croc เป็นเครื่องมือ CLI การถ่ายโอนไฟล์เพียงเครื่องเดียวที่ทำทั้งหมดต่อไปนี้:

- อนุญาตให้คอมพิวเตอร์สองเครื่องถ่ายโอนข้อมูล (โดยใช้ relay)
- ให้การเข้ารหัสแบบ end-to-end (โดยใช้ PAKE)
- รองรับการถ่ายโอนข้ามแพลตฟอร์มอย่างง่าย (Windows, Linux, Mac)
- อนุญาตให้ถ่ายโอนไฟล์หลายไฟล์
- อนุญาตให้ดำเนินการถ่ายโอนที่ถูกขัดจังหวะต่อ
- ไม่จำเป็นต้องมีเซิร์ฟเวอร์ท้องถิ่นหรือการส่งต่อพอร์ต
- ให้ความสำคัญกับ IPv6 โดยมีการ fallback เป็น IPv4
- สามารถใช้พร็อกซี เช่น tor

แอปพลิเคชันบรรทัดคำสั่งที่ใช้สามารถพบได้ที่นี่:

https://github.com/schollz/croc

## เปิดใช้งาน iCroc ในการตั้งค่า macOS
![macOS-iCroc-1](images/macos1.png)
![macOS-iCroc-2](images/macos2.png)
![macOS-iCroc-3](images/macos3.png)

# 🚚 ส่งไฟล์อย่างรวดเร็วด้วย iCroc
- เลือกไฟล์ใน Finder แล้วใช้เปิดด้วย iCroc
- ใน Finder เลือกไฟล์และใช้ ⌘+C เพื่อคัดลอกแล้วเปิด iCroc และใช้ ⌘+V เพื่อส่งไฟล์
- ลากไฟล์เข้าไปใน iCroc

# ⚡ Handoff
- อุปกรณ์ iOS และ macOS ทั้งสองติดตั้งแอพ iCroc
- เปิดใช้งานฟีเจอร์ Handoff ใน iOS และ macOS
- เมื่อผู้ส่งสร้างรหัสผ่านแล้ว iCroc ของอุปกรณ์อื่นจะได้รับรหัสผ่านโดยอัตโนมัติ

# 🔮 ดำเนินงานที่ขัดจังหวะต่อ
- ผู้ส่งส่งไฟล์ใหม่และผู้รับใช้รูปแบบรหัสผ่านใหม่@รหัสผ่านเก่า เช่น 4161-mambo-young-baby@7611-south-concept-satire
- ผู้ส่งส่งไฟล์ใหม่ใช้โทเค็นแบบกำหนดเองเป็นรหัสผ่านก่อนหน้า

# 💾 โฟลเดอร์รับแบบกำหนดเอง
- โฟลเดอร์รับจะถูกบันทึกไว้ที่ ~/Downloads/'${code-phrase}'
- ใช้ '@folderName' จะถูกบันทึกไว้ที่ ~/Downloads/folderName เช่น 8443-siren-mayor-origin@mypics
- ใช้โฟลเดอร์เป้าหมายเดียวกันจะดำเนินการถ่ายโอนงานที่ถูกขัดจังหวะต่อโดยอัตโนมัติ