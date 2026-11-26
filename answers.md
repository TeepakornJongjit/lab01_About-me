# Lab L1: แอป About me

**Name:** Teepakorn Jongjit  
**Student ID:** 67124875

## Test Results

1. **Open App:** แอปสามารถเปิดใช้งานบน Android Emulator ได้ตามปกติ
2. **Tap Like Once:** เมื่อกดปุ่ม Like 1 ครั้ง จำนวน Likes เพิ่มจาก 0 เป็น 1
3. **Tap Like 20 Times:** เมื่อกดปุ่ม Like 20 ครั้ง จำนวน Likes เพิ่มเป็น 20
4. **Hot Reload:** เมื่อแก้ไขโค้ดและกด `r` จำนวน Likes ยังคงเดิม
5. **Hot Restart:** เมื่อกด `R` จำนวน Likes กลับไปเริ่มต้นที่ 0

## Conclusion

แอปสามารถแสดงข้อมูลโปรไฟล์และนับจำนวนการกด Like ได้ถูกต้อง โดยใช้ StatefulWidget และ setState() ในการอัปเดตหน้าจอ