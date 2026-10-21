# Faol fuqaro — O‘zgarishlar tashabbuskori

9-sinf BSB-1 uchun o‘zbek tilidagi taqdimot-sayt. Loyihada 11 sahifa bor. Har bir sahifadagi matn 150 so‘zdan ortiq; dizayn qog‘oz, yashil va to‘q sariq ranglar asosidagi sokin editorial uslubda, ortiqcha neon va dekorativ effektlarsiz. Sahifalar orasida yo‘nalishga qarab o‘zgaradigan, 3D perspektiva va silliq chiqish-kirish animatsiyasi bor. JavaScript faqat sahifa navigatsiyasi, animatsiya, swipe va to‘liq ekran boshqaruvi uchun ishlatiladi; so‘rov formasi va hisob-kitob skripti olib tashlangan.

## Ishga tushirish

Bu statik sayt. Alohida framework yoki build bosqichi kerak emas. \`index.html\` faylini brauzerda ochish kifoya.

## Taqdimot boshqaruvi

- \`→\` / \`←\`: keyingi yoki oldingi sahifa
- Telefonda chapga/o‘ngga surish
- \`F\` yoki \`⛶\`: to‘liq ekran
- \`Home\` / \`End\`: birinchi / oxirgi sahifa

## Dalillar va so‘rov

Taqdimotdagi “Kuzatuv va dalillar” sahifasi interaktiv forma emas. U kuzatuv, anonim so‘rov va natijani tekshirish usullarini tushuntiradi. Jamoa hali haqiqiy ma’lumot yig‘magan bo‘lsa, foiz yoki xulosa o‘ylab topmasligi kerak; haqiqiy natijalar o‘qituvchi bilan kelishilgan jadvalda ko‘rsatiladi.

Topshiriqda og‘zaki himoya uchun 3–5 daqiqa ko‘rsatilgan. Sahifalar kengroq yozma izoh beradi; himoyada ularni boshidan oxirigacha o‘qish o‘rniga muammo, dalil, huquqiy bog‘lanish va tanlangan yechimni qisqa bayon qiling.

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
