Executive Summary

รายงานฉบับนี้มีเพื่อพัฒนาระบบ Merchant Guard โดยมีเป้าหมายเพื่อยกระดับ Trust & Safety ในระบบ onboarding ของ merchant โดยตรวจสอบความสอดคล้องเชิงความหมาย (semantic consistency) ระหว่าง ภาพที่ merchant อัปโหลด กับ หมวดหมู่ร้านค้าที่เลือก แบบอัตโนมัติด้วย model
ปัญหาหลักที่พบคือ merchant บางรายเลือกหมวดหมู่ผิดพลาดหรือเจตนาหลอกระบบ ซึ่งส่งผลกระทบโดยตรงต่อ คุณภาพ marketplace, ความเชื่อมั่นของผู้ใช้ และต้นทุนการตรวจสอบแบบ manual รายงานฉบับนี้นำเสนอ pipeline สำหรับ Image–Text Consistency Checking โดยเปรียบเทียบแนวทาง SOTA สองแบบ และเลือกใช้ Vision–Language Foundation Model (CLIP-based) เป็นแกนหลักของระบบ
ผลลัพธ์ชี้ให้เห็นว่าแนวทาง multimodal embedding ให้สมดุลที่ดีที่สุดระหว่าง performance, scalability และ deployment feasibility พร้อมศักยภาพในการนำไปใช้จริงใน production
