# Inventory Management System

A simple, modern, browser-based inventory management system for small businesses.

## Features

- **Dashboard:** View total products, out-of-stock items, total revenue, and low stock alerts.
- **Product Management:** Add, edit, delete, and search products. Manage categories.
- **Stock Management:** Add stock, sell products, and track sales.
- **Barcode/QR Scanning:** Scan items using your device camera (requires camera access).
- **Audit Log:** Track all inventory actions for accountability.
- **Reports:** Print and export inventory data as CSV.
- **Backup/Restore:** Backup and restore your inventory data.
- **Theme:** Light/Dark mode toggle.
- **Calculator:** Built-in calculator for quick calculations.

## Requirements

- A modern web browser (Chrome, Edge, Firefox, etc.)
- (Optional) Python 3.x for running a local server:  
  `python -m http.server`
- No backend or database required. All data is stored in your browser's localStorage.

## How to Use

1. **Download or clone this repository.**
2. Open `Index.html` in your browser.
3. Use the menu to navigate between Dashboard, Products, Audit Log, and Settings.
4. Add new products, manage stock, and use the scanner as needed.
5. Use Settings to backup, restore, or export your data.

## Notes

- All data is stored locally in your browser. Clearing browser data will erase your inventory.
- For best experience, use a local server (see Requirements).
- The system is designed for small to medium inventory needs.

## Credits

- [Chart.js](https://www.chartjs.org/) for charts.
- [jsQR](https://github.com/cozmo/jsQR) for QR/barcode scanning.

---

**For any issues or