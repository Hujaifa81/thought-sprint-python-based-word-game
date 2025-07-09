# 🧠 Thought Sprint – A Python-Based Word Memorization Game

**Thought Sprint** is a console-based Python word game where players test their memory by recalling words from categories like **Books**, **Movies**, and **Famous People** under time pressure.

---

## 🎮 Features

### 👤 User
- Register & login system
- Select difficulty levels: Easy / Medium / Hard
- Score-based gameplay (with time and point penalties/rewards)
- View scores
- Send feedback
- Update password

### 🔐 Admin
- Admin login (default: admin / 1234)
- View all users and their scores
- Search for users
- View feedback
- Delete users

---

## 🧩 Game Mechanics

- **Categories**: Books, Movies, Famous People
- **Game Phases**:
  1. Memorize words (10 seconds)
  2. Guess words (time varies by difficulty)
- **Scoring**:
  - Correct: +5 points and +5 seconds
  - Incorrect: -5 seconds

---

## 💾 File Storage

- `users.txt` – stores user data
- `leaderboard.txt` – stores scores
- `feedback.txt` – stores feedback

---

## 🛠️ Installation

### Prerequisites
- Python 3.x

### Clone Repository

```bash
git clone https://github.com/Hujaifa81/thought-sprint.git
cd thought-sprint
```

### Run the Game

```bash
python main.py
```

> Make sure `main.py` and all data files (`users.txt`, `leaderboard.txt`, `feedback.txt`) are in the same directory.

---

## 📦 Dependencies

This game uses only **built-in Python libraries**, so no extra dependencies are required.

---

## 🗂️ Data Schema (Text File Based)

Since this game is file-based (no DB), the schema is structured as follows:

### `users.txt`
```
username,password,score,feedback
```

### `leaderboard.txt`
```
username,score
```

### `feedback.txt`
```
username: feedback message
```

---

## 🧾 Documentation

[Documentation](https://github.com/Hujaifa81/thought-sprint-python-based-word-game/blob/main/Thought_sprint-python-based-word-game_documentation.pdf)

---

## 🚀 Future Improvements

- Password encryption (e.g., `bcrypt`)
- GUI using `Tkinter` or `PyQt`
- Use a database like SQLite or MySQL
- Unlockable levels and achievements


---

## 📄 License

This project is for academic use only.
