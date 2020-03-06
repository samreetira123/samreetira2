# Samree Library (sam)

สวัสดีจร้า ไลบรารี่นี้ใช้สำหรับฝึกสร้างไลบรารี่เป็นของตัวเอง ความสามารถคือ

  - แสดงชื่อภาษาอังกฤษ 
  - แสดงชื่อภาษาไทย


### วิธีติดตั้งแสนง่าย

เราจะติดตั้งผ่านเจ้า pip

```sh
pip install samreetira2
```

ง่ายไหมล่ะ

วิธีใช้ก็ง่ายมาก
- เปิด Python แล้วพิพม์ตามนี้เลย

```sh
from samreetira2 import samree

mysamree = Samree()
    print(mysamree)
    print(mysamree.name)
    print(mysamree.lastname)
    print(mysamree.nickname)
    mysamree.WhoIAm()
    print(mysamree.email)
    print('-------------')

    mypaa = Samree()
    mypaa.name = 'Somsri'
    mypaa.lastname = 'Konthai'
    mypaa.nickname = 'Sri'
    mypaa.WhoIAm()

    print(mypaa.name)
    print(mypaa.lastname)
    print(mypaa.nickname)

```

