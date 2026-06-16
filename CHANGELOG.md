# Changelog 📝

รายการการเปลี่ยนแปลงทั้งหมดของโปรเจกต์ Data Retention System

## [1.1.0] - 2026-06-16
### Added
- **Dynamic Rows**: เพิ่มความสามารถในการกรอกข้อมูลระดับตารางได้หลายรายการในฟอร์มเดียว
- **Recall System**: เพิ่มระบบดึงข้อมูลเก่ากลับมาแก้ไขด้วย Submit Code
- **Unique Code Generator**: ระบบสร้างรหัสอ้างอิงอัตโนมัติ (Format: REQ-TIMESTAMP-RANDOM)
- **Documentation**: เพิ่มไฟล์ README.md และ CHANGELOG.md

### Changed
- **Form Structure**: ปรับปรุง UI ใหม่เป็นแบบ Master-Detail เพื่อประสบการณ์การใช้งานที่ดีขึ้น
- **API Logic**: ปรับปรุงการส่งข้อมูลเป็นแบบ JSON Payload (Array of objects) และรองรับการ Update/Delete แถวเดิมใน Google Sheets
- **Alert UI**: ปรับปรุงการแสดงผลแจ้งเตือนให้สวยงามและลดความซ้ำซ้อนของ Emoji
- **Form Reset**: เพิ่มระบบ Clear หน้าจออัตโนมัติหลังจากบันทึกสำเร็จ

### Fixed
- **CORS Error**: แก้ไขปัญหา "Failed to fetch" โดยการปรับปรุง Headers และการตั้งค่าใน Google Apps Script
- **Form UI Glitches**: แก้ไขปัญหา Emoji ซ้ำซ้อนใน Alert Box
