FinalExam
https://drive.google.com/drive/folders/1zedJP5ggmIDAqQvR2H6d3hupoaEhFjpk?usp=drive_link

🎮 คำอธิบายเกี่ยวกับเกม
ชื่อเกม: 2-Player Tag Game
ประเภทเกม: Multiplayer / Tag Game (ไล่จับ 2 ผู้เล่น)

🛠️ เทคโนโลยีที่ใช้สร้าง
Unity: ใช้สำหรับพัฒนาเกมแบบ 2D

C#: เขียนสคริปต์ควบคุมการเล่นเกม

Mirror: ระบบ Networking สำหรับสร้าง Multiplayer แบบ Peer-to-Peer

TextMeshPro: สำหรับแสดงข้อความใน UI และบนตัวละคร

AudioSource: ใช้เพิ่มเสียงพื้นหลัง (BGM) และเสียงประกาศผลแพ้ชนะ

Animator: เพิ่มการเคลื่อนไหวตัวละครให้สมจริง

UI System:  Timer,Result

🕹️ วิธีการเล่น
เริ่มต้นเกม

ผู้เล่นแต่ละคนกรอกชื่อตัวเองก่อนเริ่มเกม

เมื่อเข้าสู่เกม จะมีตัวละคร 2 ตัว:

🎅 Santa: เป็นผู้ไล่ล่า

🎃 Jack: เป็นผู้หลบหนี

เงื่อนไขการชนะ

Santa ชนะ: ถ้า Santa สามารถวิ่งไปแตะตัว Jack ได้ก่อนหมดเวลา

Jack ชนะ: ถ้า Jack หลบหนีจนเวลาหมด (60 วินาที)

การควบคุมตัวละคร

Player 1 (Santa): ปุ่มลูกศร ← ↑ → ↓ หรือปุ่มกำหนดเอง

Player 2 (Jack): ปุ่ม W A S D หรือปุ่มกำหนดเอง

ทั้งสองตัวละครสามารถ กระโดด และ เคลื่อนที่ในฉาก 2D

ระบบเสียง

มีเสียงเพลงพื้นหลัง (BGM) ขณะเล่น

เมื่อเกมจบ จะมีเสียงชนะดังขึ้นฝั่งผู้เล่นทุกคน

การรีเซ็ตเกม

เกมจะรีเซ็ตโดยอัตโนมัติภายใน 5 วินาทีหลังจากประกาศผล

ตัวละครกลับไปที่จุดเริ่มต้น และเริ่มจับเวลาใหม่
![Image](https://github.com/user-attachments/assets/ccb63726-9d7c-49fe-a253-f6aac6460ba3)
![Image](https://github.com/user-attachments/assets/4538f221-2121-4d35-a059-96ea870cd3ed)
![Image](https://github.com/user-attachments/assets/b7654460-9efe-4170-a123-1494a62ea62d)
