# Expense Tracker

A lightweight, responsive expense tracking web application built with vanilla JavaScript. It allows users to track income and expenses, calculate balances in real time, and persist history locally in the browser.

---

## Features

- **Transaction Management:** Add income (positive amounts) and expenses (negative amounts).
- **Real-Time Calculations:** Automatically updates current balance, total income, and total expenses.
- **Visual Categorization:** Color-coded transaction history (green border for income, red border for expenses).
- **Data Persistence:** Uses browser `localStorage` so transactions remain saved across page reloads and sessions.
- **Quick Deletion:** Remove individual transactions on demand.
- **Zero Dependencies:** Pure HTML5, CSS3, and modern JavaScript—no build tools or backend required.

---

## Tech Stack

- **HTML5:** Semantic document structure and user input form.
- **CSS3:** Custom responsive layout, card styling, and dynamic hover actions.
- **JavaScript (ES6+):** DOM manipulation, state calculation, and `localStorage` API integration.

---

## Project Structure

```text
expense-tracker/
│
├── index.html        # Main user interface
├── index.css         # Styling, layout, and colors
├── index.js          # Client-side state, DOM logic, & localStorage
└── README.md         # Project documentation
