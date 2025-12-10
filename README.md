# Quiz-2 API 🎮

one simple, ready-to-use quiz API Goat Bot / Node.js of
for Mixed **Easy + Hard** questions, multiple categories।  

---

---

## 📝 Features

- ✅ 6 categories: History, Science, Math, Islamic, Geography, Literature  
- ✅ Total 48 questions (A/B/C/D options)  
- ✅ Mixed difficulty: Easy + Hard  
- ✅ Goat Bot V2 compatible  
- ✅ Direct JSON fetch for quiz commands  
- ✅ Automatic random quiz selection  

---

## 📂 JSON Structure

```json
[
  {
    "id": "1",
    "title": "History Quiz",
    "questions": [
      {
        "text": "Question text here",
        "options": { "a": "Option A", "b": "Option B", "c": "Option C", "d": "Option D" },
        "answer": "a"
      }
    ]
  }
]
