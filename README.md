# โปรแกรมภาษาไทย

## ไพธอนกับภาษาไทย

ใส่โค้ดข้างล่างไว้ที่หัวโปรแกรม

```python
#!/usr/local/bin/python
# -*- coding: utf-8 -*-
```

สำหรับ MS Windows เคยทำแบบนี้แล้วใช้ได้ พิมพ์ออก console เป็นภาษาไทยได้
โดยรัน batch นี้ก่อน
```
ECHO Change encoding to unicode
CHCP 65001
cmd /k activate py35a
```
แล้วทดสอบด้วย
```python
print('ไทย'.encode('utf8'))
```
