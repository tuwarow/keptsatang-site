# site/ — source ของ GitHub Pages repo สาธารณะ `keptsatang-site`

โฟลเดอร์นี้คือซอร์สของเว็บไซต์สถิตที่ push ไปยัง repo สาธารณะ `keptsatang-site` (GitHub Pages) แยกจาก repo แอปหลักนี้ ประกอบด้วย `index.html`, `privacy.html`, `terms.html`, `style.css`, `.nojekyll`

แหล่งความจริง (source of truth) ของเนื้อหานโยบาย/ข้อกำหนดคือ `handover/PRIVACY-POLICY-DRAFT.md` ในโปรเจกต์นี้ — ไฟล์ HTML ในโฟลเดอร์นี้คือฉบับแปลงจาก draft นั้น ไม่ใช่ต้นฉบับ

วิธีอัปเดต: แก้ไข `handover/PRIVACY-POLICY-DRAFT.md` ก่อน แล้ว regenerate ไฟล์ HTML ในโฟลเดอร์นี้ให้ตรงกับ draft ใหม่ (คงโครงสร้าง id/anchor เดิมถ้าเป็นไปได้เพื่อไม่ให้ลิงก์ที่แชร์ไว้เสีย) จากนั้น copy ไฟล์ในโฟลเดอร์นี้ทั้งหมดไปยัง repo `keptsatang-site` แล้ว commit + push เพื่อให้ GitHub Pages deploy อัตโนมัติ

หมายเหตุ: `{{DEVELOPER_NAME}}` ใน `privacy.html` แทนด้วยชื่อผู้ควบคุมข้อมูลจริงแล้ว (`Worawut Sriworaphot`) และ `AppLinks.PRIVACY_POLICY_URL` ในโค้ดแอปตั้งเป็น URL จริงแล้วเช่นกัน

repo ปลายทาง: `https://github.com/tuwarow/keptsatang-site`
URL ที่เผยแพร่: `https://tuwarow.github.io/keptsatang-site/`
