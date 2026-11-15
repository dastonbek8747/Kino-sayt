# 🎬 Kino Sayt (Django)

**Django** asosida qurilgan kino ko'rish sayti. Kinolar, animelar, multfilmlar va seriallar bo'limlari, foydalanuvchi autentifikatsiyasi.

---

## ✨ Imkoniyatlar

- 🎥 **Kinolar, anime, multfilm, serial** bo'limlari
- 👤 **Ro'yxatdan o'tish va kirish** (`users` app)
- 🔍 **Kino tafsilotlari**
- 🎨 **Shablonlar:** Bootstrap asosidagi sahifalar
- 🖼 **Media fayllar** (rasmlar)

---

## 🛠 Texnologiyalar

| Texnologiya | Maqsad |
|---|---|
| **Python 3.10+** | Asosiy til |
| **Django** | Veb-framework |
| **SQLite** | Ma'lumotlar bazasi |
| **Pipenv** | Bog'liqliklar boshqaruvi |

---

## ⚙️ O'rnatish

```bash
git clone https://github.com/dastonbek8747/Kino-sayt.git
cd Kino-sayt
pipenv install
pipenv shell
```

---

## ▶️ Ishga tushirish

```bash
python manage.py migrate
python manage.py createsuperuser    # admin uchun
python manage.py runserver
```

Brauzerda: `http://127.0.0.1:8000`

---

## 📁 Loyiha tuzilishi

```
Kino-sayt/
├── config/            # Django sozlamalari
├── movies/            # Kino app
├── users/             # Foydalanuvchi app
├── templates/         # HTML shablonlar
├── static/            # CSS/JS
├── manage.py
└── Pipfile
```

---

## 📄 Litsenziya

Litsenziya ko'rsatilmagan.
