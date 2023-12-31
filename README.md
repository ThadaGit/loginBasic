# loginBasic

เป็น Application พื้นฐานที่จะมี หน้า login และหน้าจอ register มาให้ โดยจะมีการใช้ remember me เพื่อจดจำรหัสผ่านและอีเมลของเรา พร้อมกับมีการใช้ในส่วนของ validator ในการเช็ครหัสผ่านกับอีเมลว่าถูกหรือไม่ หรือว่า ผิดหลักการเขียนหรือไม่

## How to install

วิธีการติดตั้ง

```bash
git clone https://github.com/ThadaGit/loginBasic.git
cd loginBasic
```

ถ้าเกิด Error ให้ลอง run คำสั่งนี้

```bash
flutter pub get
```

คำสั่ง "flutter pub get" ใช้ในการดาวน์โหลดแพ็กเกจ (packages) ที่ระบุในไฟล์ pubspec.yaml ของโปรเจ็กต์ Flutter ของคุณ โดยคุณสามารถใช้คำสั่งนี้เพื่อดาวน์โหลดและติดตั้งแพ็กเกจที่ระบุในไฟล์ pubspec.yaml เข้าสู่โปรเจ็กต์ของคุณ ทำให้คุณสามารถใช้งานแพ็กเกจเหล่านั้นในโปรเจ็กต์ของคุณได้.

## APK

APK ที่สร้างไว้ให้แล้วอยู่ที่
```bash
APK\app-release.apk 
```

ถ้าต้องการสร้าง APK ให้ใช้คำสั่ง
```bash
flutter build apk --build-name=1.0 --build-number=1  
```

ในส่วนของ APK ที่พึ่งสร้างจะอยู่ที่
```bash
build\app\outputs\flutter-apk\app-release.apk
```

***Android***
1. คุณสามารถคัดลอก APK ไปยังอุปกรณ์ Android โดยใช้การเชื่อมต่อ USB หรืออื่น ๆ ที่ใช้สื่อสารระหว่างคอมพิวเตอร์และอุปกรณ์ Android ของคุณ
2. หลังจากคัดลอก APK ไปยังอุปกรณ์ Android ของคุณแล้ว ให้ไปที่แอพ "เกี่ยวกับโทรศัพท์" ในอุปกรณ์ Android ของคุณ (อาจเรียกว่า "About Phone" หรือ "About Device")
3. ในหมวด "ข้อมูลซอฟต์แวร์" หรือชื่อที่คล้ายกัน คุณจะพบตัวเลือก "การติดตั้งแอปพลิเคชัน" หรือ "Install Apps" หรือบางครั้งเรียกว่า "แอปพลิเคชัน" หรือ "Apps"
4. จากนั้นเลือก "แอปพลิเคชันที่ดาวน์โหลด" หรือ "Downloaded Apps" และค้นหาไฟล์ APK ที่คุณคัดลอกมา จากนั้นคุณสามารถเลือกและติดตั้งแอป APK ได้จากนั้น

***Emulator***

ถ้าต้องการใช้งาน APK ให้ลาก app-release.apk ไปใส่ในหน้าจอของ Emulator
