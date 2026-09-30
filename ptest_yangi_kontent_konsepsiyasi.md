# ptest.uz — yangi kontent konsepsiyasi: "birinchi bo'lish" rejasi

**Asos:** `ptest_raqobat_tahlili.md`, `ptest_kontent_rejasi.md` va `baza uchun.pdf` (Yo'l harakati qoidalari va harakat xavfsizligi asoslari, 223 bet, 2020-yil nashri).

---

## 1. Muammo: hozirgi reja yetarli emas

Mavjud reja (4 rubrika, "10 soniya" shabloni) sifatli, lekin **yangilik emas**:

- 10 soniyalik savol-kartochka — bu aynan avtotest__toshkent (median 127K) formati. Bunda ptest **ikkinchi** bo'ladi, birinchi emas.
- Javob va izoh qo'shish yaxshi farq, lekin kichik. Tomoshabin buni 5 soniyada "yana bir quiz" deb qabul qiladi.
- Raqobatchilar bir xil narsalarni qilyapti: quiz, collab, kalit so'z, humor. Hech kim o'yin, statistika, real imtihon tajribasi bilan shug'ullanmayapti (raqobat tahlili, 6-bo'lim).

**Qaror:** qisqa savol-javob rubrikasini saqlaymiz (arzon reach), lekin brendning yuzini **boshqa narsalar** belgilaydi — faqat ptest qila oladigan formatlar.

---

## 2. Bitta g'oya: "Imtihon ekrani — bu bizning tilimiz"

Hamma prava haqida *gapiradi*. ptest prava imtihonini *o'ynatadi*.
Har bir kontent (reel, karusel, story) imtihon interfeysi mantiqida qurilsin: **taymer, ball, to'g'ri/xato, natija**. Shunda tomoshabin ptestni videodan taniydi, hatto logotipsiz ham.

Vizual qoidalar (mavjud shablon ustiga):
- Doim ekranda: taymer chizig'i + "savol 7/20" hisoblagichi.
- Rang mantiqi o'zgarmaydi: to'q fon, yashil = to'g'ri, qizil = xato. Boshqa rang ishlatilmaydi.
- Tovush: taymer tiqillashi, to'g'ri/xato signali — 0,5 soniyalik "imtihon tovushi" brend belgisiga aylanadi.
- Grid: bitta muqova shabloni (rubrika raqami + rang). Tahlildagi "tartibsiz grid" muammosi shu bilan yopiladi.

---

## 3. Yangi formatlar (raqobatchida yo'q)

### 3.1 "Ommaga qarshi" — komment-referendum ⭐ birinchi ustuvorlik
Reelda savol beriladi, variantlar A/B/C. Tomoshabin **kommentga harfni yozadi**. Ertasi kuni keyingi reelda: *"1 247 kishi A dedi. To'g'ri javob — C. Siz ko'pchilik bilan birgamisiz?"*

- Komment mexanikasi (yanvardagi 1.4M / 18.8K komment, yodla 79K komment) **o'yinning o'zi bo'lib qoladi**, sun'iy "kalit so'z" emas.
- Har reel keyingisiga sabab yaratadi → seriya, qaytib keluvchi auditoriya.
- Natija real ovozlardan olinadi (kommentlarni sanash). Raqamlar to'qilmaydi.

### 3.2 "Kim birinchi o'tadi?" — tepadan animatsiya
Kesishmalar va ustuvorlik savollari eng ko'p adashiladigan mavzu. Raqobatchilar statik 3D rasm beradi. Biz: **tepadan ko'rinish, mashinalar jonli harakatlanadi**, taymer tugaganda to'xtab qoladi, tomoshabin javobni tanlaydi, keyin harakat to'g'ri tartibda davom etadi va qoida moddasi ko'rsatiladi.

- Qoida kitobdan emas, **harakatdan** o'rganiladi.
- Bitta animatsion shablon — yuzlab savolga qayta ishlatiladi (arzon ishlab chiqarish).

### 3.3 "Afsona yoki qoida?" — moddasi bilan
Ijtimoiy tarmoqdagi mish-mishlar ("pravani shu xato uchun olishadi") → **aniq modda raqami va manba** bilan rad etish yoki tasdiqlash.
- Raqobatchilar jarima va yangilikni aytadi, **manba ko'rsatmaydi**. Ishonch — bizning ustunligimiz.
- Tahlilda ptestning eng yaxshi organik reeli (198K) aynan yangilik turidan.
- Faqat joriy qoidalardan foydalaniladi (3-band, 6-bo'lim: eslatma).

### 3.4 "ptest statistikasi" — ma'lumot bilan
*"Bu savolda foydalanuvchilarning X% i xato qildi."* Buni faqat platforma aytishi mumkin. Shart: **raqamlar real bazadan eksport qilinadi**; ma'lumot yo'q bo'lsa, format boshlanmaydi.

### 3.5 "Tuzoq juftlik"
Deyarli bir xil ikki savol/belgi, javoblari qarama-qarshi. "Bir-biriga o'xshash, lekin bittasi xato" — tomoshabin to'xtab, qayta ko'radi (ko'rish vaqti ↑). Namuna: "A va B belgi" reeli (132K) g'oyasining tizimli davomi.

### 3.6 "0 dan pravagacha" — 21 kunlik seriya
Bitta haqiqiy odam (ptest jamoasidan emas) noldan imtihongacha. Har kun 1 ta qisqa reel: ball, xatolar, kayfiyat. Oxirida **real imtihon natijasi**. Hikoya kuzatuvchini saqlaydi; raqobatchilarda bunday seriya yo'q.

### 3.7 "Ball kartasi" — mahsulot + kontent (ikkinchi bosqich)
Imtihon tugagach foydalanuvchiga ulashiladigan natija kartasi ("Prava tayyorgarligim: 18/20"). Har ulashish — bepul reklama. *Bu ilova o'zgarishini talab qiladi; ptest jamoasi bilan kelishiladi.*

---

## 4. Nima qilmaymiz (raqobatchilardan saboq)

| Xato | Kim qilgan | Bizda |
|---|---|---|
| Mavzuga aloqasiz caption | avtotest__toshkent | Har caption mavzuga mos, 2–3 qator |
| Isbotsiz "100% kafolat" | avtotest__toshkent | Hech qachon. Faqat real natijalar |
| Hamma reel "sotuvchi" ko'rinishida | avtotest7 (may 76K → sentabr 25K) | 80% foydali/o'yin, 20% taklif |
| Reach bitta blogerga bog'liq | yodla | Yuz + o'z formatlar + 2–3 collab |
| Bir xil "90% odam adashadi" hook | ptest hozir | Har format o'z hook qoliplariga ega |

---

## 5. Manba: "baza uchun.pdf" bilan qanday ishlaymiz

Kitob (2020) — modda-modda tuzilgan rasmiy matn: ta'riflar, belgilar, ustuvorlik, tezlik, to'xtash va turish va h.k. U:
- **Modda raqami** va aniq ta'rif manbai sifatida ishlatiladi (3.3, 3.2 uchun).
- Savol izohlarining asosi (1-rubrika, har savolga izoh).

**Muhim:** kitob 2020-yil nashri. Qoidalar, jarimalar va raqamlar o'zgargan bo'lishi mumkin (tahlilda 2026 yilgi yangi qonun loyihalari tilga olingan). Shuning uchun **har bir fakt videoga chiqishidan oldin joriy qoidalarga solishtiriladi**; kitobdagi sana bilan eskirgan bo'limlar ishlatilmaydi.

---

## 6. 30 kunlik reja

| Hafta | Nima chiqadi | Maqsad |
|---|---|---|
| 1 | Brend "imtihon ekrani" shabloni + 3.1 "Ommaga qarshi" (3 ta reel) + bio/pin/highlight tuzatish | Yangi yuzni o'rnatish |
| 2 | 3.2 "Kim birinchi o'tadi?" (3 ta) + 3.3 "Afsona yoki qoida?" (2 ta) | Formatlarni sinash |
| 3 | 3.4 statistika (real ma'lumot olinsa) + 3.5 tuzoq juftlik; "0 dan pravagacha" 1-kun | Seriyani boshlash |
| 4 | Eng yaxshi 2 formatni ko'paytirish, yomonini to'xtatish; 1–2 o'rta bloger bilan collab | Masshtab |

Ko'rsatkichlar (tahlildagi maqsadga mos): median ko'rish 4.9K → 20K+, 1 ta 100K+ reel, har formatga alohida 24/72 soatlik ko'rish, saqlash, repost, komment soni. **2 hafta ichida median o'smagan format to'xtatiladi.**

---

## 7. Keyingi qadam

Ustuvorlik: **3.1 → 3.2 → 3.3**. Tasdiqlansa, birinchi 10 ta reel uchun tayyorlayman: hook, kadrlar ketma-ketligi, ekrandagi matn, caption va CTA.

**Sizdan kerak:**
1. Qaysi formatlardan boshlaymiz (yuqoridagi ustuvorlik mosmi)?
2. ptest foydalanuvchi statistikasini (3.4) eksport qilish mumkinmi?
3. Ball kartasi (3.7) uchun ilova jamoasi bilan gaplashamizmi?
