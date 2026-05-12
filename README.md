# AstroDecode ♈✨

AstroDecode is a modern Flask-based Zodiac Sign Finder web application that predicts a user's zodiac sign based on their birth date and displays personality insights with zodiac symbols.

Built using Python, Flask, and SQLite, this project is simple, fast, and beginner-friendly.

---

## 🌟 Features

✅ Find zodiac sign instantly using birth date  
✅ Displays zodiac symbol and personality traits  
✅ SQLite database integration  
✅ Clean and responsive UI  
✅ Beginner-friendly Flask project  
✅ Lightweight and easy to run locally  

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Backend Logic |
| Flask | Web Framework |
| SQLite3 | Database |
| HTML/CSS | Frontend UI |

---

## 📂 Project Structure

```bash
astrodecode/
│
├── app.py                # Main Flask Application
├── create_db.py          # Database Creation Script
├── zodiac.db             # SQLite Database
│
├── templates/
│   ├── index.html        # Home Page
│   └── result.html       # Result Page
│
├── static/
│   └── style.css         # Styling
│
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/astrodecode.git
cd astrodecode
```

---

## 2️⃣ Install Dependencies

```bash
pip install flask
```

---

## 3️⃣ Create Database

```bash
python create_db.py
```

---

## 4️⃣ Run Application

```bash
python app.py
```

---

## 5️⃣ Open in Browser

```bash
http://127.0.0.1:5000
```

---

# 🚀 How It Works

1. User enters their birth date  
2. Flask receives the form input  
3. SQLite database checks zodiac date ranges  
4. Matching zodiac sign is found  
5. Zodiac symbol and personality description are displayed  

---

# ♈ Zodiac Signs Included

| Zodiac | Symbol |
|--------|---------|
| Aries | ♈ |
| Taurus | ♉ |
| Gemini | ♊ |
| Cancer | ♋ |
| Leo | ♌ |
| Virgo | ♍ |
| Libra | ♎ |
| Scorpio | ♏ |
| Sagittarius | ♐ |
| Capricorn | ♑ |
| Aquarius | ♒ |
| Pisces | ♓ |

---

# 📸 Preview

### Home Page
- User selects birth date

### Result Page
- Displays:
  - Zodiac Sign
  - Zodiac Symbol
  - Personality Traits

---

# 🔮 Future Improvements

- 🌌 Daily Horoscope API
- 💖 Zodiac Compatibility Checker
- 🎨 Better UI/Animations
- 🌙 Dark Mode
- ☁️ Online Deployment
- 📱 Mobile Optimization

---

# 👨‍💻 Author

### Sai Shewale

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

# 📄 License

This project is licensed under the MIT License.
