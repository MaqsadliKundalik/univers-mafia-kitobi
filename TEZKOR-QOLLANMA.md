# TEZKOR QOLLANMA - Univers Mafia Kitob

## YANGI SAHIFA QOSHISH (5 QADAM)

### 1. Shablonni tanlang
```
templates/template-text.html     - Oddiy matn
templates/template-roles.html    - Rollar
templates/template-table.html    - Jadvallar
templates/template-columns.html  - Ikki ustun
```

### 2. Shablonni oching va nusxalang (Ctrl+C)

### 3. index.html ga o'ting

### 4. Oxirgi sahifadan keyin qo'ying (</body> dan oldin)

### 5. Sahifa raqamini yangilang
```html
<div class="page-number">XX</div>
```

---

## ENG KOʻP ISHLATILADIGAN KODLAR

### Rol qo'shish:
```html
<div class="role-box">
    <div class="flex justify-between items-center mb-2">
        <h3>ROL NOMI</h3>
        <span class="badge badge-red">KATEGORIYA</span>
    </div>
    <p>Tavsif...</p>
</div>
```

### Ogohlantirish qo'shish:
```html
<div class="info-box warning">
    <p>Eslatma matni</p>
</div>
```

### Jadval qo'shish:
```html
<table>
    <thead>
        <tr>
            <th>Sarlavha 1</th>
            <th>Sarlavha 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Ma'lumot 1</td>
            <td>Ma'lumot 2</td>
        </tr>
    </tbody>
</table>
```

---

## BADGE RANGLARI

```html
badge-red     - Qizil (Mafiya)
badge-blue    - Kok (Shahar)
badge-green   - Yashil (Himoya)
badge-purple  - Binafsha (Mustaqil)
badge-gold    - Oltin (Maxsus)
```

---

## INFO-BOX TURLARI

```html
info-box warning  - Sariq (Ogohlantirish)
info-box danger   - Qizil (Xavfli)
info-box success  - Yashil (Muvaffaqiyat)
```

---

## FAYLNI OCHISH

1. `index.html` ni ikki marta bosing
2. Yoki brauzerga sudrab tashlang
3. Ctrl + P - Print qilish

---

**TUGADI! Ish boshlashingiz mumkin! ✅**
