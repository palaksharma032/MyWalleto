# MyWalleto

MyWalleto is a sleek personal finance dashboard built with React and Vite. It helps users track income and expenses, monitor budget health, view recent activity, and manage their financial records in a clean, modern interface.

## Features

- Dashboard overview with total income, total expenses, and net balance
- Add, edit, and delete transactions
- Budget tracking with monthly spending progress
- Expense analytics via a pie chart
- Recent transaction activity feed
- Light/dark theme toggle
- Local persistence using browser storage
- Responsive, polished UI for personal finance management

## Tech Stack

- React
- Vite
- React Router
- Chart.js and react-chartjs-2
- CSS modules/styles for custom UI

## Project Structure

```bash
MyWalleto/
├── public/
├── src/
│   ├── components/
│   ├── context/
│   ├── data/
│   ├── pages/
│   ├── services/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
├── index.html
├── eslint.config.js
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm or yarn

### Installation

```bash
npm install
```

### Run the app locally

```bash
npm run dev
```

Then open the local URL shown in the terminal, usually:

```bash
http://localhost:5173
```

### Production build

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## Usage

1. Open the dashboard and view your key financial metrics.
2. Add a new transaction from the dashboard or transactions page.
3. Edit or remove entries from the transaction history.
4. Update the monthly budget from the settings page.
5. Toggle between light and dark theme based on preference.

## Data Storage

This app stores transaction and budget data in the browser using localStorage, so it remains available across refreshes without a backend.

## License

This project is for educational and personal use.

## Author

Built as a personal finance dashboard project for managing spending, budgeting, and financial insights.
