# StockPilot — Inventory Management Demo

A Persian RTL, responsive inventory-management portfolio project built with HTML, CSS and vanilla JavaScript.

## Features
- Add, edit and delete products with unique SKU
- Product categories, unit price, quantity and low-stock threshold
- Stock-in / stock-out movements with quantity validation and history
- Dashboard: total SKUs, units, inventory value, low-stock alerts
- Search and stock-status/category filters
- CSV export for products and movements (UTF-8 BOM for Excel)
- Printable Code 39 barcode labels for compatible SKU values (A–Z, 0–9 and hyphen)
- localStorage persistence

## Demo
https://khandanian.github.io/stockpilot-inventory/

## Notes
This is a **single-browser portfolio demo**, not a production inventory system. No backend, multi-user synchronization, authentication, or real-time stock locking. Sample products are fictional. Browser data deletion removes locally saved changes. Barcode generation supports Code 39-compatible SKU characters only; underscores are permitted as SKU identifiers but cannot be rendered as Code 39 in this demo.

## Deploy
Go to **Settings → Pages** and set **Source: GitHub Actions**. Workflow deploys `main` to GitHub Pages without attempting to enable Pages automatically.

## Local run
Open `index.html` in a browser.
