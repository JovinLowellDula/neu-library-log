# 📚 NEU Library Visitor Log

A web-based library visitor logging system for **New Era University**.  
Built with pure HTML, CSS, and JavaScript — hosted free on GitHub Pages.  
All visitor records are saved to **Google Sheets** and shared across every device in real time.

---

## 🌐 Live Application

👉 **https://jovinlowelldula.github.io/neu-library-log/**

---

## ✨ Features

| Feature | Details |
|---|---|
| 🏛️ Splash screen | Animated NEU library building with welcome screen |
| 🔑 Google Sign-In | One-click sign-in with `@neu.edu.ph` Google accounts |
| 🛡️ Auto admin detection | Admin accounts go straight to dashboard — no password |
| 🎓 Student log | Course dropdown + Student ID number |
| 👨‍🏫 Faculty / Staff log | Name + Department |
| 🚶 Walk-in Visitor | No email needed — just name + purpose |
| 📊 Admin dashboard | Stats by Today / Week / Month / Year / Date Range |
| 📈 Purpose breakdown | Visual bar chart of most common visit reasons |
| 🔍 Universal search | Search by name, ID, email, date, purpose |
| 🔽 Filters | Filter by purpose, role, or course/department |
| ☁️ Shared database | All logs saved to Google Sheets — visible from any device |
| 📤 Export CSV | Download all records as a spreadsheet |

---

## 👤 Account Roles

| Role | Email | Access |
|------|-------|--------|
| Admin | `LibrarianAcc@neu.edu.ph` | Full dashboard — stats, records, filters, export |
| NEU Member | Any `@neu.edu.ph` account | Visitor log form + personal visit summary |
| Walk-in Visitor | No account needed | Enter name + purpose directly |

> Admins are detected **automatically** on Google Sign-In. No password needed.  
> When an admin signs in, they choose: **Open Dashboard** or **Log a Visit as Regular User**.

---

## ☁️ Google Sheets Database

All visitor records are stored in:  
**[NEU Library Visitor Log Sheet](https://docs.google.com/spreadsheets/d/1hUnk0kQcRt7-5KPPNpvNg8x5hJF5ZfieuAi063IxJO4/edit)**

Every log from every device automatically appears in this shared sheet.  
The admin dashboard reads directly from this sheet in real time.

---

## 🛠️ Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Google Identity Services (OAuth 2.0)
- Google Apps Script (free serverless API)
- Google Sheets (shared database)
- GitHub Pages (hosting)

---

## 📁 Project Structure

```
neu-library-log/
├── index.html   ← entire application (HTML + CSS + JS in one file)
└── README.md    ← this file
```

---

*New Era University — Library Management System · 2026*
