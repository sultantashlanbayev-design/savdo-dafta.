# Savdo Daftari — telefon uchun ilova

Bu papkada "Savdo Daftari" ilovasining to'liq versiyasi bor. Uni GitHub Pages orqali
internetga qo'ysangiz, u telefoningizda oddiy sayt emas, balki ekranga o'rnatiladigan
ilova (PWA) sifatida ishlaydi — internetsiz ham ochiladi, o'z ikonkasi bilan.

## Fayllar
- `index.html` — asosiy ilova
- `manifest.json` — ilova sozlamalari (nomi, ikonka, rangi)
- `service-worker.js` — internetsiz ishlash uchun
- `icon-192.png`, `icon-512.png` — ilova ikonkasi

## 1-qadam: GitHub'da repository yaratish
1. https://github.com ga kiring (akkaunt bo'lmasa — ro'yxatdan o'ting, bepul).
2. Yuqori o'ng burchakda **+** tugmasi → **New repository**.
3. Repository nomi: masalan `savdo-daftari`.
4. **Public** qilib qoldiring, **Create repository** bosing.

## 2-qadam: Fayllarni yuklash
1. Yangi repository sahifasida **"uploading an existing file"** havolasini bosing
   (yoki **Add file → Upload files**).
2. Shu papkadagi barcha fayllarni (index.html, manifest.json, service-worker.js,
   icon-192.png, icon-512.png) sudrab tashlang.
3. Pastda **Commit changes** tugmasini bosing.

## 3-qadam: GitHub Pages'ni yoqish
1. Repository ichida **Settings** bo'limiga o'ting.
2. Chap menyudan **Pages** ni tanlang.
3. **Branch** qismida `main` ni tanlang, papka `/ (root)` bo'lsin, **Save** bosing.
4. Bir necha daqiqadan so'ng yuqorida shunday havola paydo bo'ladi:
   `https://FOYDALANUVCHI-NOMI.github.io/savdo-daftari/`

## 4-qadam: Telefonga ilova sifatida o'rnatish
**Android (Chrome):**
1. Yuqoridagi havolani Chrome'da oching.
2. Yuqori o'ng burchakdagi ⋮ menyuni bosing → **"Bosh ekranga qo'shish"** /
   **"Add to Home screen"** → **Qo'shish**.
3. Ilova ikonkasi bosh ekranga chiqadi, oddiy ilova kabi ochiladi.

**iPhone (Safari):**
1. Havolani Safari'da oching.
2. Pastdagi **Ulashish (Share)** tugmasini bosing.
3. **"Bosh ekranga qo'shish" / "Add to Home Screen"** ni tanlang → **Qo'shish**.

## Muhim eslatmalar
- Ma'lumotlar (tovarlar, narxlar, qoldiqlar) telefoningizning shu brauzerida
  saqlanadi. Agar brauzer keshi/ma'lumotlari tozalansa, ro'yxat ham o'chib ketadi —
  vaqti-vaqti bilan "Revizsiya varag'i" tugmasi orqali chop etib, zaxira sifatida
  saqlab qo'yish tavsiya etiladi.
- Ilova ikkita alohida telefon/brauzerda ikkita alohida ma'lumot bazasi bo'ladi —
  ular hozircha bir-biri bilan sinxronlanmaydi.
- Kategoriyani aniqlash endi internetga bog'liq emas — so'zlarga qarab (masalan
  "sut", "gўsht", "shokolad") avtomatik taxmin qiladi. Xato bo'lsa, har doim qo'lda
  o'zgartirishingiz mumkin.
