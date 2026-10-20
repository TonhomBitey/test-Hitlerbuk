วิธีสร้างไฟล์ APK (ไม่ต้องติดตั้งโปรแกรมใดในคอมพิวเตอร์)
1) สมัคร GitHub ฟรี แล้วสร้าง repository ใหม่ (Create new repository)
2) อัปโหลดไฟล์และโฟลเดอร์ทั้งหมดในโฟลเดอร์ HitlerBuk นี้ขึ้นไป (Add file > Upload files)
   สำคัญ: ต้องมีโฟลเดอร์ .github/workflows/build.yml ด้วย ถ้าลากโฟลเดอร์ที่ขึ้นต้นด้วยจุดไม่ได้
   ให้ใช้ Add file > Create new file แล้วพิมพ์ชื่อ .github/workflows/build.yml แล้ววางเนื้อหาจากไฟล์นี้
3) ไปที่แท็บ Actions รอจน "Build APK" ขึ้นเครื่องหมายถูก (ประมาณ 3-6 นาที)
4) กดเข้างานที่เสร็จแล้ว ดาวน์โหลด HitlerBuk-apk ที่ส่วน Artifacts แตกไฟล์ zip จะได้ app-debug.apk
5) ส่งไฟล์ไปมือถือ Android เปิดไฟล์ แล้วอนุญาตติดตั้งจากแหล่งที่ไม่รู้จักเมื่อระบบถาม

ทางเลือก: เปิดโฟลเดอร์นี้ด้วย Android Studio แล้วเลือก Build > Build APK(s)
