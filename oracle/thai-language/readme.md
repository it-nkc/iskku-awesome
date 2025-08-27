# แก้ไขภาษาไทยเพี้ยน (ภาษาต่างดาว) ใน Oracle

1. เปิด regedit

2. ค้นหาว่า NLS_LANG
   ![รูปภาพที่ 1](https://bucket.kku.ac.th/iskku/KM/3-1.jpg)

3. NLS_LANG ที่อยู่ภายใต้ Folder ORCLE ใน Folder KEY_Oraclient(ตามด้วยเวอร์ชั่น Oracle)
   ![รูปภาพที่ 2](https://bucket.kku.ac.th/iskku/KM/oracle/thai-lang/Screenshot%202025-08-27%20163832.png)

4. แก้ไขข้อความในช่อง Value data จากของเดิม AMERICAN_AMERICA.WE8MSWIN1252 เปลี่ยนเป็น THAI_AMERICA.TH8TISASCII

```
THAI_AMERICA.TH8TISASCII
```

![รูปภาพที่ 3](https://bucket.kku.ac.th/iskku/KM/oracle/thai-lang/Screenshot%202025-08-27%20163914.png)
