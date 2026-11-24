# SpendWise – Smart Student Expense Tracker

## Run it
Double-click `index.html` (any modern browser). No install, no internet, no API keys.
Optional local server: `python3 -m http.server 8000` then open http://localhost:8000

## Tech
HTML + CSS + vanilla JavaScript in a single file, inline SVG charts, LocalStorage persistence (key: `spendwise1`).
(Not React/Vite/Tailwind – chosen so the project runs with zero setup.)

## Features
Dashboard, Transactions (add/edit/delete, search, filters, sort), Budgets, Savings Goals,
Analytics (6-month chart, payment methods, spending calendar), Smart Insights (rule-based),
"Can I afford this?" checker, dark mode, reset to sample data / clear all data.

## Manual test checklist
1. Add a Rs 200 Food expense -> balance, charts, Food total and budget update.
2. Edit it -> everything recalculates. 3. Delete it -> recalculates.
4. Refresh the page -> data persists. 5. Try search/filters/sorting.
6. Add a savings goal and add savings. 7. Use "Can I afford this?" in Smart Insights.
8. Resize to mobile width. 9. Settings -> Clear all / Reset sample data.

## Prompt Book
Add your own real prompts and results here (do not fabricate).
