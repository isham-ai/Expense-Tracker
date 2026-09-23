# 💰 Expense Tracker

A clean, responsive Expense Tracker web app built with **vanilla JavaScript**, **HTML**, and **CSS**. Track your income and expenses, view your balance at a glance, and see where your money goes with a category-wise spending chart.

## ✨ Features

- **Add income & expenses** with description, amount, category, and date
- **Live summary cards** — total income, total expenses, and current balance
- **Category filter** — view transactions by category (Food, Travel, Shopping, Bills, etc.)
- **Spending chart** — interactive doughnut chart (Chart.js) showing expenses by category
- **Persistent storage** — all data is saved in the browser via `localStorage`, so nothing is lost on refresh
- **Delete individual transactions** or clear everything at once
- **Fully responsive** dark-mode UI that works on mobile, tablet, and desktop
- Amounts formatted in Indian Rupees (₹) using `Intl.NumberFormat`

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- JavaScript (ES6+, DOM, localStorage)
- [Chart.js](https://www.chartjs.org/) via CDN for the doughnut chart

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/expense-tracker.git
   ```
2. Open `index.html` in your browser — that's it. No build step, no dependencies to install.

Or try it live: [GitHub Pages Demo](https://<your-username>.github.io/expense-tracker/)

## 📸 Screenshots

*(Add screenshots of the app here — Home, Add Transaction, Chart view)*

## 📁 Project Structure

```
expense-tracker/
├── index.html   # Page structure and sections
├── style.css    # Dark theme styling and responsive layout
├── script.js    # App logic: CRUD, storage, filtering, chart
└── README.md
```

## 🔮 Future Improvements

- [ ] Edit existing transactions
- [ ] Monthly budgets with progress bars
- [ ] Export data to CSV
- [ ] Dark / light theme toggle

## 🤝 Contributing

Issues and pull requests are welcome!

## 📄 License

MIT — free to use, modify, and share.
