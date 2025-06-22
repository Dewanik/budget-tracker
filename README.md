# Budget Tracker

A simple, mobile-friendly, and installable budget tracker web app with the following features:

- **Add/Delete Categories:** Organize your budget by category, add new ones, or delete existing ones.
- **Track Spending:** Add transactions for each category, see how much you've spent, and how much remains.
- **Overspending Alerts:** If you try to overspend, you'll get a motivational message and a confirmation prompt.
- **Remaining/Overspent Display:** See the remaining balance for each category, or how much you've overspent.
- **Drag & Drop Reordering:** Rearrange your budget categories by dragging and dropping the cards.
- **Reset Options:** Reset all spent amounts to $0, or remove all categories entirely.
- **Export Data:** Download your budget data as a JSON file or a PDF.
- **Installable PWA:** Add the app to your home screen for a native-like experience.
- **Mobile Friendly:** Responsive design works great on phones and tablets.

---

## 🚀 Getting Started



### 1. Open and start using 
https://dewanik.github.io/budget-tracker/
Visit the GitHub Pages URL and use the app directly in your browser or download as mobile app!


### 1. Deploy via GitHub Pages

1. **Create a new repository** (or use your own).
2. **Upload the files:**
    - [`index.html`](./index.html)
    - [`manifest.json`](./manifest.json)
    - [`README.md`](./README.md)
3. **Enable GitHub Pages:**
    - Go to repository **Settings** > **Pages**
    - Select branch `main` (or `master`) and set `/ (root)` as the folder
    - Save and get your live URL (usually `https://<username>.github.io/<repo>/`)
#or 
---

## 🧑‍💻 Usage

### Add Categories

- Enter a category name and budget, click **Add Category**.

### Add Transaction

- Click the "+" button on any category to add a transaction.

### Delete Category

- Click the 🗑️ (trash) button on a category to delete it.

### Rearranging Categories

- Drag and drop a category card to reposition it.
- The order is saved and preserved across reloads.

### Reset Budgets

- **Reset Budgets:** Sets all "Spent" values to $0, keeps categories.
- **Remove All Categories:** Deletes all categories and resets everything.

### Export Data

- **Download JSON:** Save your budget data for backup.
- **Download PDF:** Get a printable summary of your budgets.

### Overspending

- If you try to add a transaction that would overspend a category, you'll see a **random motivational message** and be asked for confirmation.
- If confirmed, the transaction is added and the overspent amount is shown.

### Install as App

- If your browser supports PWAs, click "Add to Home Screen" for a native-like experience.

---

## 📱 Mobile Friendly

- The interface is designed to work well on both mobile and desktop.
- All features are accessible and easy to use on touch devices.

---

## 🗂️ File Structure

```
index.html         # Main application file (all logic, styles, and markup)
manifest.json      # Web app manifest for PWA support
README.md          # This documentation
```

---

## 🛡️ Privacy

- All your data is stored **locally in your browser** using `localStorage`.
- No data is sent to any server. You control your information.

---

## 📝 Customization

Feel free to fork, modify, and expand this project!

---

## 📄 License

MIT License

---

## ✨ Credits

- [jsPDF](https://github.com/parallax/jsPDF) for PDF export
- [Twemoji](https://github.com/twitter/twemoji) for the app icon

---

Enjoy budgeting and take control of your finances!  
