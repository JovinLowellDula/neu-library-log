# 📚 NEU Library Visitor Log

A web-based library visitor logging system for **New Era University**.  
Built with pure HTML, CSS, and JavaScript — no backend required. Hosted on GitHub Pages.

---

## 🌐 Live Application

👉 **https://jovinlowelldula.github.io/neu-library-log/**

---

## ✨ Features

- **Google Sign-In** using official `@neu.edu.ph` Google accounts
- **Auto admin detection** — admin accounts are redirected to the dashboard automatically upon sign-in, no password needed
- **Role-based logging** — Student (with course + student ID), Faculty, and Visitor
- **Purpose of visit** — Reading, Research, Computer Use, Group Study, Borrowing Books, Returning Books, Printing, Other
- **Admin Dashboard** with visitor statistics by Day, Week, Month, Year, or custom date range
- **Purpose Breakdown** bar chart showing most common visit reasons
- **Filters** by purpose, role, and course/department
- **Universal search bar** — search by name, student ID, email, date, or purpose
- **Export to CSV** — download all records as a spreadsheet
- All data stored locally in the browser (localStorage)

---

## 👤 Account Roles

| Role | Email | Access |
|------|-------|--------|
| Admin | `jcesperanza@neu.edu.ph` | Full dashboard — stats, records, filters, export |
| Regular User | Any `@neu.edu.ph` account | Visitor log form + personal visit summary |

> Admins are detected **automatically** when signing in with Google. No separate login or password needed.

---

## 🛠️ Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Google Identity Services (OAuth 2.0)
- GitHub Pages (hosting)
- localStorage (data persistence)

---

## 📁 Project Structure

```
neu-library-log/
└── index.html    ← entire application in one file
└── README.md     ← this file
```

---

*New Era University — Library Visitor Log System*
