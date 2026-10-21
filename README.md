# Faol fuqaro — O‘zgarishlar tashabbuskori

9-sinf BSB-1 uchun o‘zbek tilidagi taqdimot-sayt. Loyihada 11 sahifa bor. Har bir sahifadagi matn 150 so‘zdan ortiq; dizayn qog‘oz, yashil va to‘q sariq ranglar asosidagi sokin editorial uslubda, ortiqcha neon va dekorativ effektlarsiz. Sahifalar orasida mayin 3D o‘tish bor.

## Ishga tushirish

Bu statik sayt. Alohida framework yoki build bosqichi kerak emas. \`index.html\` faylini brauzerda ochish kifoya.

## Taqdimot boshqaruvi

- \`→\` / \`←\`: keyingi yoki oldingi sahifa
- Telefonda chapga/o‘ngga surish
- \`F\` yoki \`⛶\`: to‘liq ekran
- \`Home\` / \`End\`: birinchi / oxirgi sahifa

## So‘rov natijalarini kiritish

“Natijalar va diagramma” sahifasida jami javoblar soni va uchta ko‘rsatkich bo‘yicha haqiqiy javob sonlarini kiriting, so‘ng “Diagrammani yangilash” tugmasini bosing. Diagramma foizni avtomatik hisoblaydi. Saytda oldindan tayyor soxta foizlar yo‘q. So‘rovni o‘tkazmagan bo‘lsangiz, natija o‘ylab topmang: avval anonim so‘rovni o‘tkazing va ma’lumotni keyin kiriting. Hozirgi diagramma kiritilgan qiymatlarni joriy brauzer sessiyasida hisoblaydi; natijalarni saqlab qo‘yish uchun ularni alohida qayd eting.

## Asosiy manbalar

- Topshiriq: “9-sinf BSB-1 loyiha ishi” — 6 sahifali ko‘rsatma va baholash mezonlari.
- O‘zbekiston Respublikasi Konstitutsiyasi, 36-, 40- va 49-moddalar: https://lex.uz/uz/acts/-6445145
- UNICEF Innocenti, “Exploring civic education”: https://www.unicef.org/innocenti/exploring-civic-education
- UNESCO, “What you need to know about education for sustainable development”: https://www.unesco.org/en/sustainable-development/education/need-know

Huquqiy xulosalarni taqdimotdan oldin rasmiy Konstitutsiya matni bilan solishtiring. UNICEF va UNESCO materiallari umumiy tadqiqot mazmuni uchun keltiriladi; ular jamoaning o‘z so‘rovi va kuzatuvi o‘rnini bosmaydi.

## Jamoa

- Loyiha muallifi: Qurbonov Asilbek
- Baxtiyorov Suxrob
- Achilbayev Javohir
- Shovkatov Azizbek
- Põlatov Sardor

## Joylashtirish — Cloudflare Pages

1. Cloudflare boshqaruv panelida **Workers & Pages → Create → Pages → Connect to Git** ni tanlang.
2. GitHub’ni ulang va \`premiummaster156-cmd/tarbiya-presentation-\` repozitoriysini tanlang.
3. Production branch sifatida \`main\` ni belgilang.
4. Build command maydonini bo‘sh qoldiring.
5. Build output directory maydoniga \`.\` kiriting.
6. Deploy tugmasini bosing. Keyingi \`main\` commitlari yangi deployga olib keladi.
