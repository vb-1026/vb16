Viloyatga Boramiz — server bilan ishlaydigan loyiha

Talab: Node.js 18 yoki yangiroq.

Ishga tushirish (Windows):
1. ZIP faylni to‘liq chiqarib oling.
2. Shu papkada terminal/PowerShell oching.
3. npm start buyrug‘ini kiriting (yoki node server.js).
4. Brauzerda http://localhost:3000 ni oching.

API va ma’lumotlar:
- GET /api/health — server holati
- POST /api/accounts — foydalanuvchi ma’lumotlarini saqlash
- GET/POST /api/drivers — haydovchi e’lonlarini olish/saqlash
- GET/POST /api/bookings — bronlarni olish/yaratish
- DELETE /api/bookings/:id — bronni bekor qilish
- Ma’lumotlar data.json faylida saqlanadi.

MUHIM:
- Saytni file:// orqali emas, http://localhost:3000 orqali oching.
- Server ma’lumotlarni bir xil serverga ulangan foydalanuvchilar o‘rtasida ulashadi.
- Internetga chiqarish uchun Node.js qo‘llaydigan hostingga joylash va doimiy disk/database sozlash kerak.
- Bu boshlang‘ich backend: production uchun parol/OTP autentifikatsiyasi, email/telefon tasdiqlash, HTTPS, rate limit va haqiqiy ma’lumotlar bazasi qo‘shilishi kerak.
- Karta to‘lovi hozir ulanmagan. Karta raqami/CVV kiritmang.
- Haydovchilar tizimga kirgach alohida safar e’lon qilish sahifasini ko‘radi; yo‘lovchilar esa hudud bo‘yicha qidiruv va bron sahifasini ko‘radi.
- Yo‘lovchi manzil tanlashida O‘zbekistonning 14 ta hududi, tumanlari va asosiy shahar/tuman markazlari mavjud. Aniq mahalla, ko‘cha, bino yoki uy manzilini ham yozish mumkin. Hududlar ro‘yxati keng qamrovli, lekin har bir ko‘cha va kichik aholi punktining rasmiy katalogi emas.
- Sign-in animatsiyasida yashil rangli, aylanadigan interaktiv Yer shari ko‘rsatiladi.
- Haydovchi e’lonlari server API orqali saqlanadi. E’lonlar/bronlar bir serverga ulangan foydalanuvchilar uchun ko‘rinadi; hostingga joylashtirilmagan bo‘lsa, localhost faqat shu kompyuterda ishlaydi.
