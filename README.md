HLVhf = HAM LOG VHF — แพ็กเกจเว็บแอป (PWA)  v1.0 · 2026-10-31
==============================================================
บันทึก Log QSO โหมดเสียง VHF / UHF (2m · 70cm) เปิดจากลิงก์เว็บ ติดตั้งเป็นแอปบน Windows / Mac ด้วย Chrome หรือ Edge

ไฟล์ที่ต้องอัปโหลดทั้งหมด:
  index.html  manifest.webmanifest  sw.js  icons/ (4 ไฟล์)  .nojekyll

--- ขึ้น GitHub Pages (repository ใหม่ แยกจาก HAM-LOG-DATA) ---
1) github.com > New repository ตั้งชื่อ HAM-LOG-Vhf เลือก Public > Create repository
2) กด "uploading an existing file" ลากไฟล์ทั้งหมด + โฟลเดอร์ icons ลงไป > Commit changes
3) Settings > Pages > Source: Deploy from a branch · Branch: main · / (root) > Save
4) รอ 1-2 นาที ลิงก์จะเป็น https://e25ynh.github.io/HAM-LOG-Vhf/
5) เปิดด้วย Chrome / Edge กดไอคอนติดตั้งที่แถบที่อยู่ เพื่อติดตั้งเป็นแอป

--- อัปเดตเวอร์ชัน ---
อัปโหลดไฟล์ทับใน repository เดิม (Add file > Upload files) แล้วกด Commit changes
แอปที่ติดตั้งไว้จะขึ้นแถบ "มีเวอร์ชันใหม่" ให้กดโหลดใหม่

--- วิธีใช้ใหม่ในรุ่นนี้ ---
* หน้า VOICE > คลิกตัวเลขความถี่บนหน้าจอวิทยุ = แผงพิมพ์ความถี่ (MODE / DUP / TONE / ความถี่ล่าสุด)
  พิมพ์ได้: 145.625 · 145.337.500 · 145625 (kHz) · 145337500 (Hz) · ต่อวิทยุอยู่จะสั่งวิทยุผ่าน CI-V
* ตั้งค่า > ข้อมูลวิทยุ > อุปกรณ์เสียง: เลือกครั้งเดียว หน้า VOICE เปิดฟังเสียงให้เอง

--- ข้อควรรู้ ---
* ใช้คู่กับ HLD บนเว็บเดียวกัน (e25ynh.github.io) ได้ ข้อมูลตั้งค่าและ Log แยกกัน ไม่ปนกัน
  ถ้าต้องการย้าย Log จาก HLD มา HLVhf: HLD > ตั้งค่า > สำรองข้อมูล แล้ว HLVhf > นำเข้าจากไฟล์สำรอง (หรือใช้ไฟล์ ADIF)
* ใช้ได้กับ Chrome / Edge (Web Serial สำหรับต่อวิทยุ CI-V / CAT) ไม่รองรับ Safari / Firefox
* ครั้งแรกที่เปิดหน้า VOICE เบราว์เซอร์จะถามสิทธิ์ไมโครโฟน (เสียงเข้าจากวิทยุ) ให้กดอนุญาต
* ข้อมูลผู้ใช้ (รหัส QRZ / HamQTH, Log) เก็บในเครื่องผู้ใช้เอง ไม่ได้อยู่บน GitHub
* ออฟไลน์ใช้บันทึก Log ได้ แต่การค้น QRZ / HamQTH ต้องมีอินเทอร์เน็ต
