# 💸 UPI Payment Simulator — 

A complete full-stack UPI payment simulation project.
**Backend:** Python · Flask · SQLite (standard libraries)
**Frontend:** Responsive webpage  — HTML · CSS 


---

## 📁 Project Structure

```
🏦 Neo-banks-project / Team 6
│
├── 📂 backend/
│   ├── 🐍 app.py                ← Flask app, all REST routes
│   ├── 🐍 database.py           ← SQLite connection & query helpers
│   ├── 🗄️  neobank.db            ← Persistent SQLite database
│   └── 📋 requirements.txt      ← pip dependencies
│
├── 📂 frontend/
│   ├── 🌐 index.html            ← Login / UPI auth screen
│   ├── 🌐 dashboard.html        ← Main dashboard (balance + actions)
│   ├── 🌐 register.html         ← New account registration
│   ├── 🌐 send_money.html       ← Payment initiation screen
│   ├── 🌐 transactions.html     ← Full transaction history view
│   └── 🎨 style.css             ← Global responsive styles
│
├── 📄 README.md
├── 📄 .gitignore
```
---

## ⚙️ Setup

### 1. Install dependencies
```bash
cd backend
pip install -r requirements.txt
```

### 2. Run Flask API
```bash
python app.py
# API: http://localhost:5000
```

### 3. Open the web demo
```
Double-click  frontend/index.html  in your file manager
```
The green "API Connected" badge confirms the backend is reachable.



---

