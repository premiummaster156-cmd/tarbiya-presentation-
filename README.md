# Faol fuqaro — O‘zgarishlar tashabbuskori

9-sinf BSB-1 uchun o‘zbek tilidagi taqdimot. Sayt 10 sahifadan iborat; oxirgi sahifada jamoa ismlari bir joyda, muallif yorlig‘i bilan va katta “E’tiboringiz uchun rahmat!” sarlavhasi bor. Dizayn cream-yashil ranglardagi sodda editorial uslub va yo‘nalishga mos silliq 3D sahifa o‘tishidan foydalanadi.

## Boshqaruv

- \`→\` / \`←\`: keyingi yoki oldingi sahifa
- Telefonda chapga/o‘ngga surish
- \`F\` yoki \`⛶\`: to‘liq ekran
- \`Home\` / \`End\`: birinchi / oxirgi sahifa

JavaScript faqat sahifa o‘tishlari, tugmalar, touch navigatsiyasi, to‘liq ekran va yengil animatsiya boshqaruvi uchun ishlatiladi. So‘rov formasi, raqam kiritish va hisob-kitob skripti yo‘q.

## Topshiriqqa moslik

Dastlabki loyiha topshirig‘i 6 sahifali PDF bo‘lib, unda taqdimot uchun 3–5 daqiqa belgilangan; slaydlar soni qat’iy ko‘rsatilmagan. Taqdimotda faol fuqaro tushunchasi, tanlangan muammo, tadqiqot savoli va anonim so‘rov, natijalar jadvali/diagrammasi, huquqiy va tarbiyaviy tahlil, 2–3 yechim va tanlangan yechimning asosi, fuqarolik tashabbusi rejasi, kamida uch dalilli yakuniy pozitsiya, manbalar va individual refleksiya bor.

Haqiqiy so‘rov natijalari foydalanuvchi tomonidan berilmagani uchun raqamlar o‘ylab topilmagan. “So‘rov va dalillar” sahifasidagi jadvalni jamoaning haqiqiy so‘rov natijalari bilan to‘ldiring. Yakuniy pozitsiyani ham yig‘ilgan dalillarga qarab himoya qilish yoki o‘zgartirish kerak.

## Manbalar

- Asosiy ko‘rsatma: “9-sinf BSB-1 loyiha ishi” (foydalanuvchi taqdim etgan PDF).
- 9-sinf Tarbiya darsligi va Davlat va huquq asoslari darsligi: amalda foydalanilgan nashr hamda sahifalarni taqdimotda ko‘rsating.
- Huquqiy matn zarur bo‘lsa, O‘zbekiston Respublikasi Konstitutsiyasining amaldagi matni: https://lex.uz/uz/acts/-6445145

Topshiriq SI ishlatilsa, vosita va maqsadini ko‘rsatishni, shaxsiy ma’lumot kiritmaslikni va faktlarni darslik yoki ishonchli manbada tekshirishni so‘raydi. Sayt tuzilishi va matnini tayyorlashda SI yordami ishlatilgan; mazmun jamoa tomonidan tekshirilishi va haqiqiy kuzatuvlar bilan to‘ldirilishi kerak.

## Jamoa sahifasi

- **Qurbonov Asilbek** — Muallif
- Baxtiyorov Suxrob
- Achilbayev Javohir
- Shovkatov Azizbek
- Põlatov Sardor

## Cloudflare Pages orqali joylash

1. Cloudflare boshqaruv panelida **Workers & Pages → Create → Pages → Connect to Git** ni tanlang.
2. GitHub’ni ulang va \`premiummaster156-cmd/tarbiya-presentation-\` repozitoriysini tanlang.
3. Production branch sifatida \`main\` ni belgilang.
4. Build command maydonini bo‘sh qoldiring.
5. Build output directory maydoniga \`.\` kiriting va Deploy bosing.
