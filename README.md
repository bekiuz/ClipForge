# ClipForge

O‘zbek tilidagi qisqa video va Reels ssenariylarini tayyorlash uchun AI yordamchi.

## Hozirgi imkoniyatlar

- Video mavzusini kiritish.
- Auditoriya, davomiylik, ohang va platformani tanlash.
- Mavzuni AI, til o‘rganish, dasturlash, biznes yoki umumiy yo‘nalishlarga ajratish.
- Cloudflare Worker orqali AI ssenariy yaratish.
- AI xizmati ishlamasa, mavzu turiga mos offline generatorga qaytish.
- Hook, asosiy qism, misol, yakun va caption tuzilmasi.
- Ssenariyni nusxalash yoki TXT sifatida yuklab olish.
- Oxirgi mavzular tarixini brauzer `localStorage` xotirasida saqlash.

## Ishga tushirish

`index.html` faylini brauzerda oching yoki GitHub Pages orqali joylashtiring.

## AI integratsiyasi

Ilova Cloudflare Worker'ga `action: "clipforge"` so‘rovi yuboradi. Worker va model limiti mavjud bo‘lmasa, lokal generator ishlaydi. AI yaratgan faktlar va tavsiyalarni e’lon qilishdan oldin tekshirish kerak.

## Cheklovlar

Video montaj, avtomatik subtitr, media fayl eksporti yoki ijtimoiy tarmoqqa avtomatik joylash hozircha mavjud emas. Tarix faqat shu brauzerda saqlanadi.

## Keyingi bosqich

Kontent kalendari, bir mavzudan bir nechta variant, sahna/kadr ko‘rsatmalari va video montaj vositalari bilan integratsiya.

Repo: https://github.com/bekiuz/ClipForge
