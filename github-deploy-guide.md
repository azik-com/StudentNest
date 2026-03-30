# StudentNest — GitHub Pages Deploy Qo'llanmasi

## 📁 Fayl strukturasi

```
studentnest/              ← repository nomi
├── index.html            ← studentnest-user.html ni rename qiling
├── admin.html            ← studentnest-admin.html
├── manifest.json
├── sw.js
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## 🚀 Qadamba-qadam

### 1. GitHub repository yaratish
1. github.com ga kiring
2. **New repository** → nom: `studentnest`
3. **Public** tanlang (Pages bepul ishlashi uchun)
4. **Create repository**

### 2. Fayllarni yuklash
```
studentnest-user.html  →  index.html  deb saqlang
studentnest-admin.html →  admin.html  deb saqlang
```

### 3. GitHub Pages yoqish
1. Repository → **Settings**
2. Chapda **Pages** bo'limi
3. Source: **Deploy from a branch**
4. Branch: **main** → **/ (root)**
5. **Save**

### 4. URL
```
https://YOUR_USERNAME.github.io/studentnest/
https://YOUR_USERNAME.github.io/studentnest/admin.html
```
5-10 daqiqada tayyor bo'ladi ✅

---

## 📱 PWA — "Ekranga qo'shish"

### Android (Chrome)
1. Saytni oching
2. Chrome menyu (⋮) → **"Bosh ekranga qo'shish"**
3. **Qo'shish** → tayyor!

### iPhone (Safari)
1. Saytni Safari da oching
2. Pastdagi **Share** tugmasi (⬆️)
3. **"Add to Home Screen"**
4. **Add** → tayyor!

---

## ⚠️ Muhim eslatmalar

| Muammo | Yechim |
|--------|--------|
| Admin sahifa ochiq ko'rinadi | `.htaccess` yoki URL ni yashirish kerak |
| Rasmlar saqlanmaydi | Firebase Storage kerak |
| Login ma'lumotlari saqlanmaydi | Firebase Auth kerak |
| E'lonlar yo'qoladi | Firebase Firestore kerak |

---

## 🔥 Firebase ulash (keyingi qadam)

```
1. console.firebase.google.com
2. New project → "studentnest-uz"
3. Authentication → Email/Phone yoqish
4. Firestore Database yaratish
5. config kodni HTML ga qo'shish
```
