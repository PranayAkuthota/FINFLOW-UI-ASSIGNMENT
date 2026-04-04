# FINFLOW-UI-ASSIGNMENT


# FinFlow – Finance Dashboard UI

A clean, interactive finance dashboard built as part of the Zorvyn Frontend Developer Intern assessment.

## 🔗 Live Demo
[Click here to view the live dashboard](https://pranayakuthota.github.io/FINFLOW-UI-ASSIGNMENT/)

## 📁 Repository
[https://github.com/PranayAkuthota/FINFLOW-UI-ASSIGNMENT](https://github.com/PranayAkuthota/FINFLOW-UI-ASSIGNMENT)


##  Overview

FinFlow is a single-page finance dashboard that allows users to track income, expenses, and understand their spending patterns through visual charts and insights. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools, just open and run.


## Features Implemented

### Core Requirements
- **Dashboard Overview** — Summary cards for Total Balance, Income, Expenses, and Savings Rate with live calculations
- **Balance Trend Chart** — Line chart showing monthly balance, income, and expense trends
- **Spending Breakdown** — Doughnut chart showing categorical spending distribution
- **Income vs Expenses** — Monthly bar chart comparison
- **Transactions Section** — Full transaction list with search, filter by type and category, and sort by date or amount
- **Role-Based UI** — Admin can add, edit, and delete transactions. Viewer has read-only access. Switch roles via dropdown
- **Insights Section** — Top spending category, average monthly spend, month-over-month comparison, savings rate, category progress bars
- **State Management** — All application state managed cleanly in vanilla JS with localStorage persistence

### Optional Enhancements
- **Dark Mode** — Deep space dark theme with ambient glow orbs (default), fully toggleable to light mode
- **Local Storage Persistence** — Transactions, role, and theme preference all persist across sessions
- **CSV & JSON Export** — Export all transaction data in one click
- **Animations & Transitions** — Glassmorphism cards, hover lift effects, smooth fade-up section transitions, floating ambient orbs



##  Design Decisions

- **Dark-first design** with a deep space aesthetic using glassmorphism cards and ambient background orbs
- **Color system** — Purple accent (#6C63FF), Green for income (#00D68F), Red for expenses (#FF5C7C)
- **Typography** — Outfit (headings) + Space Grotesk (body) for a modern financial feel
- **Fully responsive** — works on mobile, tablet, and desktop


## How to Run Locally

No installation or setup required.

```bash
# Option 1 — Just open the file
Double-click index.html in your file explorer

# Option 2 — Using VS Code Live Server
Right-click index.html → Open with Live Server
```



## 📁 Project Structure

```
FINFLOW-UI-ASSIGNMENT/
└── index.html        # Complete app — HTML + CSS + JS in one file
└── README.md         # This file
```



##  Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Vanilla CSS (custom design system, CSS variables, glassmorphism) |
| Logic | Vanilla JavaScript (ES6+) |
| Charts | Chart.js 4.4.1 |
| Fonts | Google Fonts — Outfit + Space Grotesk |
| Persistence | localStorage API |



## Role-Based UI

| Feature | Admin | Viewer |
|---|---|---|
| View dashboard | ✅ | ✅ |
| View transactions | ✅ | ✅ |
| Add transaction | ✅ | ❌ |
| Edit transaction | ✅ | ❌ |
| Delete transaction | ✅ | ❌ |
| Export CSV / JSON | ✅ | ✅ |

Switch roles using the dropdown in the top-right corner.


## Mock Data

The app ships with 52 realistic mock transactions spanning 6 months (Oct 2025 – Mar 2026), covering categories like Salary, Freelance, Food, Housing, Transport, Entertainment, Health, Shopping, and Utilities.



## About

Built by **Pranay Kumar Akuthota** as part of the Zorvyn Frontend Developer Intern screening assessment.

- 📧 akuthotapranaykumar@gmail.com
- 🌐 [Live Site](https://pranayakuthota.github.io/FINFLOW-UI-ASSIGNMENT/)
- 💻 [GitHub](https://github.com/PranayAkuthota/FINFLOW-UI-ASSIGNMENT)

