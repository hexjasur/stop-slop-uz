# Stop Slop UZ

O'zbek tilidagi (lotin yozuvi) matnlardan AI yozuv izlarini olib tashlash uchun skill.

Bu repo [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) (MIT) asosida yaratilgan, ammo faqat o'zbek tili uchun. Ingliz tili uchun asl skill'dan foydalaning.

## Nima qiladi

- Kirish va xulosa iboralarini olib tashlaydi ("Bugungi kunda", "Shuni alohida ta'kidlash joizki")
- Ortiqcha bog'lovchilarni kamaytiradi ("shuningdek", "bundan tashqari", "o'z navbatida")
- Noaniq baholash so'zlarini aniq fakt bilan almashtirishga undaydi ("samarali", "innovatsion")
- Tarjima uslubidagi iboralarni tuzatadi ("amalga oshirmoq", "ushbu")
- Tuzilma naqshlarini topadi (qarama-qarshilik, uchlik ro'yxat, savol-javob)
- Har bir o'zgarishni qayta tekshiradi

## O'rnatish

### Claude Code

```
git clone https://github.com/hexjasur/stop-slop-uz
```

Yoki repo papkasini `.claude/skills/stop-slop-uz` ichiga ko'chiring.

### Claude Projects yoki chat

`SKILL.md` va `references/` papkasidagi fayllarni proyekt bilimlariga yuklang.

### API

`SKILL.md` ni tizim promptiga kiriting. `references/` fayllari kerak bo'lganda o'qiladi.

## Tuzilma

```
stop-slop-uz/
├── SKILL.md              # Asosiy ko'rsatmalar va tekshiruv tartibi
├── references/
│   ├── phrases.md        # Iboralar va almashtirish jadvali
│   ├── structures.md     # Tuzilma naqshlari
│   ├── examples.md       # Oldin/keyin misollari va mashq
│   └── sources.md        # Manbalar va qoida asoslari
├── CHANGELOG.md
├── LICENSE
└── README.md
```

## Ishlatish misoli

Matnni skill bilan tahrirlashni so'rang:

> Quyidagi matnni stop-slop-uz qoidalari bo'yicha tahrirlang. Faqat tahrirlangan matnni qaytaring.

## Cheklovlar

- O'zbek tilidagi AI matnlari bo'yicha katta tadqiqot hali yo'q. Ro'yxatlar amaliy tajribaga asoslangan.
- Qoidalar katta matn to'plamida sinovdan o'tkazilmagan.
- Tekshiruv qo'lda bajariladi. Avtomatik vosita emas.

## Hissa qo'shish

Yangi qoida qo'shishdan oldin `references/sources.md` dagi shartlarga qarang. Manba yoki haqiqiy misol bo'lishi kerak.

## Litsenziya

MIT. Asl stop-slop qismlari uchun Hardik Pandya mualliflik huquqi saqlanadi.

## Minnatdorchilik

- [Hardik Pandya](https://hvpandya.com) asl `stop-slop` skill uchun.
- George Orwell "Politics and the English Language" uchun.
