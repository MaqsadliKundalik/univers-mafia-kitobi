# 📚 UNIVERS MAFIA - KITOB TEMPLATE

Premium dizayndagi Univers Mafia o'yin qo'llanmasi uchun to'liq template loyihasi.

---

## 📁 LOYIHA STRUKTURASI

```
Univers mafia kitobi/
│
├── index.html              # Asosiy HTML fayl (boshlang'ich sahifalar bilan)
├── css/
│   └── style.css           # Barcha stillar (modular va izohli)
│
├── templates/              # Turli xil sahifa shablonlari
│   ├── template-text.html      # Oddiy matn sahifasi
│   ├── template-roles.html     # Rollar sahifasi
│   ├── template-table.html     # Jadval sahifasi
│   └── template-columns.html   # Ikki ustunli sahifa
│
└── assets/                 # Rasmlar, PDF va boshqa fayllar uchun
```

---

## 🚀 ISHLATISH BO'YICHA QO'LLANMA

### 1️⃣ YANGI SAHIFA QO'SHISH

**Qadam 1:** Templates papkasidan kerakli shablonni tanlang
**Qadam 2:** Shablonni nusxalang
**Qadam 3:** `index.html` fayliga qo'shing (oxirgi `</body>` tegidan oldin)
**Qadam 4:** Sahifa raqamini yangilang

Misol:
```html
<!-- templates/template-text.html dan kontent nusxalash -->
<div class="page">
    <div class="gold-border"></div>
    <div class="content-area">
        <!-- Sizning kontentingiz -->
    </div>
    <div class="page-number">08</div>  <!-- Raqamni yangilang! -->
</div>
```

---

### 2️⃣ MAVJUD SHABLONLAR

#### 📄 **template-text.html**
- Oddiy matnli sahifalar uchun
- Paragraflar, sarlavhalar, ro'yxatlar
- Eng ko'p ishlatiladigan shablon

#### 🎭 **template-roles.html**
- Rollarni tavsiflash uchun
- `.role-box` konteynerlar
- Badge'lar bilan kategoriyalash

#### 📊 **template-table.html**
- Bot buyruqlari
- Statistik ma'lumotlar
- Qiyosiy jadvallar

#### 📑 **template-columns.html**
- Ikki ustunli layout
- Qiyoslash uchun
- Kecha/Kunduz, Mafiya/Shahar va hokazo

---

## 🎨 MUHIM KLASSLAR

### 📦 BADGE'LAR (Belgilar)
```html
<span class="badge badge-red">QORA KLAN</span>
<span class="badge badge-blue">SHAHAR</span>
<span class="badge badge-green">HIMOYACHI</span>
<span class="badge badge-purple">MUSTAQIL</span>
<span class="badge badge-gold">MAXSUS</span>
```

### 💬 INFO BOXLAR
```html
<!-- Ogohlantirish -->
<div class="info-box warning">
    <p>Muhim eslatma</p>
</div>

<!-- Xavfli -->
<div class="info-box danger">
    <p>Diqqat!</p>
</div>

<!-- Muvaffaqiyat -->
<div class="info-box success">
    <p>Yaxshi maslahat</p>
</div>
```

### 📐 MASOFA KLASSLAR
```html
<div class="mt-5">   <!-- Yuqoridan 3rem masofa -->
<div class="mb-3">   <!-- Pastdan 1.5rem masofa -->
<div class="text-center">  <!-- Markazlash -->
```

### ✏️ MATN STILLARI
```html
<p class="light">     <!-- Yupqa matn -->
<p class="bold">      <!-- Qalin matn -->
<p class="italic">    <!-- Qiyshiq matn -->
<p class="text-sm">   <!-- Kichik matn -->
<p class="text-lg">   <!-- Katta matn -->
```

---

## 🖼️ RANGLAR VA DIZAYN

### Asosiy ranglar (CSS Variables):
- `--primary-green`: #003d1c (Asosiy yashil)
- `--deep-green`: #002411 (To'q yashil)
- `--gold`: #c5a059 (Oltin)
- `--gold-light`: #e8d5a7 (Och oltin)
- `--text-gray`: #d1d5db (Kulrang matn)

### Rang ishlatish:
```html
<span class="text-[#c5a059]">Oltin rang</span>
<div class="bg-black/30">Shaffof qora fon</div>
```

---

## 📄 SAHIFA RAQAMLASH

Har bir sahifada raqam qo'shishni unutmang:
```html
<div class="page-number">08</div>
```

---

## 🖨️ PRINT QILISH

Brauzerda faylni ochib, `Ctrl + P` bosing:
- **A4 format** avtomatik o'rnatilgan
- **Ranglar** saqlanadi
- **Sahifa bo'yicha** ajratiladi

Sozlamalar:
- Margins: Default
- Background graphics: ✅ On
- Page size: A4

---

## 💡 MASLAHATLAR

### ✅ Yaxshi amaliyotlar:
1. Har bir yangi sahifada `<div class="gold-border"></div>` qo'shing
2. Sahifa raqamlarini ketma-ket tartibda saqlang
3. Shablonlardan foydalaning - g'ildirakni qayta ixtiro qilmang
4. Info-box'lardan muhim ma'lumotlarni ajratish uchun foydalaning

### ⚠️ Qochish kerak:
1. `style.css` faylini o'zgartirmasdan turib ishlang
2. Har bir sahifaga `<div class="page">` konteynerini qo'shishni unutmang
3. Juda ko'p matn bir sahifaga sig'masligi mumkin - taqsimlang

---

## 🔧 KENGAYTIRISH

### Yangi shablon yaratish:
1. `templates/` papkasida yangi fayl yarating
2. Asosiy strukturani nusxalang:
```html
<div class="page">
    <div class="gold-border"></div>
    <div class="content-area">
        <!-- Yangi dizayningiz -->
    </div>
    <div class="page-number">XX</div>
</div>
```

### CSS'ga yangi stil qo'shish:
`css/style.css` fayliga qo'shing va izoh qoldiring:
```css
/* ========== YANGI STIL ========== */
.my-custom-class {
    /* ... */
}
```

---

## 📞 YORDAM

Agar muammo yuzaga kelsa:
1. ✅ Barcha fayllar to'g'ri joyda ekanligini tekshiring
2. ✅ HTML teglar to'g'ri yopilganligini tekshiring
3. ✅ Shablondan to'liq nusxa olganingizni tekshiring

---

## 📝 VERSIYA

**V1.0** - Dastlabki release (2024)

---

**Omad tilayman! Ajoyib kitob yarating! 🎭✨**
