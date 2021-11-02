# การใช้ภาษาไทย

## การันต์

>> ...ตัวการันต์นั้นจะอยู่สุดท้ายของคำหรืออยู่ระหว่างกลางคำก็ได้ เช่น :- ฉันท์ สาส์น ชอล์ก ...

ที่มา 
[The Journal of the Royal Society of Thailand, vol 40 no 2, Apr-Jun 2015, pp. 26](https://www.orst.go.th/FILEROOM/CABROYINWEB/DRAWER004/GENERAL/DATA0000/00000615.FLP/html/35/#zoom=z)
(สืบค้น 2 พย 64)

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
