# Expense Tracker

A lightweight, responsive expense tracker built with HTML, CSS, and browser storage.

## Website preview

![Screenshot of the Expense Tracker website homepage](./website-screenshot.png)

## Features

- Record income and expenses in Indian rupees.
- Review totals and current balance; deleting a transaction recalculates the summary.
- Keep transactions and your name in the current browser using local storage.
- Use the app on desktop or mobile without installing dependencies.

## Run locally

From the repository folder, start a static server:

```powershell
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## Deploy

The GitHub Actions workflow deploys the static site to GitHub Pages when changes are pushed to `main`. The repository's Pages source must be set to **GitHub Actions**. After deployment, open [Expense Tracker on GitHub Pages](https://srisaikumar6.github.io/Expense-Tracker/).

Transactions are stored only in the browser where they were entered; they are not synced between devices.
