# Budget Tracker

**Budget Tracker** is a lightweight, user-friendly web application for organizing your finances and tracking expenses across custom categories. It is entirely client-side, requires no sign-up, and works offline.

## Features

- **Add Custom Categories:** Define your own spending categories and assign budgets.
- **Record Transactions:** Easily add expenses to any category.
- **Progress Visualization:** Visual progress bars show spending vs. budget, with clear over-budget indicators.
- **Motivational Feedback:** Receive motivational prompts when you attempt to overspend.
- **Export Options:** Download your budget data as JSON or PDF.
- **Total Reset & Cleanup:** Reset all spending or remove all categories with one click.
- **Responsive Design:** Works on desktops and mobile devices.
- **Offline Support:** Use the app without an internet connection (PWA ready).

## How It Works

1. **Add a Category:**  
   Enter a category name and budget, then click "Add Category".
2. **Track Spending:**  
   Click the ➕ button on a category to add a new transaction.
3. **Monitor Budgets:**  
   - Progress bars indicate your spending.
   - Overspending triggers a motivational warning.
4. **Manage Data:**  
   - Download your data as `budget_data.json` or `budget_data.pdf`.
   - Use the reset or remove-all buttons for quick data management.

All data is securely stored in your browser’s localStorage.

## Getting Started

1. **Clone or Download** this repository.
2. **Open** `index.html` in your web browser.
3. **(Optional)** Install as a PWA for offline use.

## Technology

- **HTML5 + CSS3:** Modern, responsive UI.
- **JavaScript:** Handles all logic and localStorage.
- **[jsPDF](https://github.com/parallax/jsPDF):** For PDF export.
- **manifest.json:** PWA support for offline and installable experience.

## Screenshots

![Screenshot](screenshot.png)  
*Example interface showing categories, progress bars, and controls.*

## Contributing

Contributions and suggestions are welcome!  
Open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Start tracking your budget, stay motivated, and take control of your finances!**
