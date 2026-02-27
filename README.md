# 🏪 Mini Mart POS System

A lightweight, browser-based Point of Sale (POS) system built with vanilla HTML, CSS, and JavaScript — no frameworks, no backend, no dependencies.
---

📋 Overview

Mini Mart POS is a fully functional retail management interface designed for small convenience stores or mini marts. It runs entirely in the browser using `localStorage` for data persistence, making it easy to deploy on any device without a server setup.

✨ Features

| Module | Description |
|---|---|
| 🖥️ **Point of Sale** | Add products to cart, adjust quantities, and process checkouts |
| 📦 **Inventory** | Add, view, and manage store products with pricing and stock levels |
| 🚚 **Product in Stock** | Log supplier deliveries and track incoming stock |
| 📊 **Reports** | View daily sales, transactions, profit, and low stock alerts |
| ⚙️ **Settings** | Configure store name, address, tax rate, currency, and stock alert thresholds |


 🛠️ Tech Stack

- HTML5 — semantic page structure across multiple pages
- CSS3 — responsive layout with CSS Grid and Flexbox, custom animations
- JavaScript (ES6) — DOM manipulation, localStorage for data persistence, modular page logic

No frameworks. No libraries. No build tools required.



🚀 Getting Started

### Option 1 — Open directly in browser

```bash
git clone https://github.com/your-username/mini-mart-pos.git
cd mini-mart-pos/HTML
open index.html
```

Or simply double-click `index.html` in your file manager.

### Option 2 — Local dev server (recommended)

Using VS Code Live Server, or:

```bash
# Python
python -m http.server 5500

# Node.js
npx serve .
```

Then visit `http://localhost:5500/HTML/index.html`

---

## 📁 Project Structure

```
mini-mart-pos/
├── HTML/
│   ├── index.html        # Point of Sale
│   ├── inventory.html    # Inventory management
│   ├── stock.html        # Supplier stock intake
│   ├── report.html       # Sales reports & analytics
│   └── setting.html      # Store settings
├── CSS/
│   └── styles.css        # Global stylesheet
├── JS/
│   ├── pos.js            # POS logic & cart management
│   ├── inventory.js      # Product CRUD operations
│   ├── stock.js          # Supplier stock logic
│   ├── report.js         # Report calculations
│   └── setting.js        # Settings persistence
└── README.md
```

## 💾 Data Persistence

All data is stored in the browser's `localStorage`. This means:
- ✅ Data persists across page refreshes and browser restarts
- ✅ No internet connection required
- ⚠️ Data is device/browser specific — clearing browser data will reset the system
- ⚠️ Not suitable for multi-device or multi-user environments without a backend


## 📌 Limitations

- Single-user, single-device only (no database or server)
- No user authentication or access control
- No receipt printing (browser print can be used as a workaround)
- Data is not encrypted in localStorage


## 🔮 Future Improvements

- [ ] Add barcode scanner support
- [ ] Export reports to CSV/PDF
- [ ] Receipt generation and print functionality
- [ ] Backend integration (Node.js + MongoDB or Firebase)
- [ ] Multi-user authentication

---

## 👤 Author

**[Srors Muyyi]**
- GitHub: [@azureohizone](https://github.com/azureohizone)
- LinkedIn: [Muyyi Srors](https://www.linkedin.com/in/muyyi-srors-8a8128290/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).