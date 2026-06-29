# 💰 FinTrack Pro

FinTrack Pro is a minimalist, browser-based personal finance tracking web application designed to help you see exactly where your money goes instantly. Built entirely using vanilla technologies, it requires no backend installation, no database setup, and zero configuration.

---

## ✨ Core Features

* **Live Balance Engine:** Current balance, total income, and total expenses recalculate instantly as transactions are added.
* **Cash Flow Chart:** An interactive bar chart tracking spending versus earnings over time, powered by Chart.js.
* **Smart Storage Integration:** All data, currency preferences, and theme configurations persist securely in local browser storage.
* **Currency Switcher:** Seamlessly shift display formatting between USD, EUR, GBP, INR, or JPY instantly without reloading.
* **Adaptive Dark Mode:** A toggleable light/dark interface utilizing CSS variables that remembers user preferences for your next visit.
* **Transaction Controls:** Quickly filter recent transactions by type (All, Income, Expense) or delete entries with a single click.

---

## 🛠️ Architecture & Tech Stack

* **Frontend Foundation:** Semantic HTML5 & Modern CSS Grid / Flexbox.
* **Dynamic Control Layer:** Plain JavaScript (ES6+) for structural DOM manipulation and state management.
* **Visual Analytics:** Chart.js integration fetched securely via CDN.
* **Data Layer:** Browser localStorage API for instant, serverless persistence.

---

## 🚀 Running Locally

Because FinTrack Pro is designed around a clean, decoupled file structure with zero external compilation dependencies, testing it locally takes seconds:

1. Clone or download this project directory.
2. Open `index.html` directly by double-clicking it or dragging it into any modern web browser.
3. *Alternative:* For precise environment simulation, launch it using the VS Code Live Server extension to host it via localhost.

---

## 📈 Planned Roadmap

Future iterations of the application intend to explore structural expansions such as:
* Exporting transactions as a downloadable CSV file.
* Setting localized spending limits and budget warnings per category.
* Migrating to a cloud database with email/password authentication interfaces.
