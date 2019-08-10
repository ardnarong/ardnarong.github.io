[comment]: <> (Application Security Verification Standard [ASVS]  V4)

<h2>Requirement ID : V5.1</h2>

<h2>Requirement Name : Input Validation Requirements</h2>

เนื่องจากการพัฒนาเว็บไซต์มีความจำเป็นต้องมีการรับข้อมูลจากผู้ใช้งาน ในความเป็นจริงอาจจะมีผู้ไม่ประสงค์ดี(Attacker) ทำการส่งข้อมูลเข้ามา ทำการ SQL/Code Injection  เพื่อโจมตีเว็บไซต์ ดังนั้น Input Validation จึงเป็นเป็นกระบวนการเพื่อทำให้มั่นใจว่าข้อมูลเข้ายังคงเข้ากันได้กับระบบงาน และทำให้ระบบทำงานได้ตรงตามที่คาดหวัง แต่ถ้าข้อมูลเหล่านี้มันผิดปกติ หรือ ไม่เข้ากับการทำงานของระบบ มันย่อมทำให้เกิดผลลัพธ์ที่ไม่เป็นดังหวังเช่นกัน

[comment]: <> (OWASP Testing Guide)

OTG #1  : Testing for SQL Injection (OTG-INPVAL-005)

OTG #2  : Testing for Code Injection (OTG-INPVAL-012)

