# Taj Al Smou Invoice Generator

A lightweight, standalone, single-file web application for generating official contracting invoices with automated timesheet parsing and single-page A4 PDF printing.

## 🚀 Features

- **Single-File Architecture (`index.html`)**: 100% self-contained client-side web application. Runs directly in any web browser, on GitHub Pages, Netlify, or Vercel with zero backend dependencies.
- **Excel Timesheet Auto-Import**: Drag & drop or select `.xlsx` / `.xls` / `.csv` timesheets to instantly parse worker names, total hours, trade rates (Labour vs. Welder), and food deductions (`المطعم`).
- **Dynamic Dual-Calendar Conversion**: Real-time conversion and synchronization between English Gregorian dates (`DD/MM/YYYY`) and Saudi Umm al-Qura Hijri dates (`هـ`).
- **Dynamic Subject Line**: Automatically syncs the invoice month name based on the invoice date.
- **Dynamic Financial Calculations**:
  - Gross Total calculation
  - Net Total after food deduction
  - 15% VAT calculation
  - Automatic English text amount conversion (e.g. *"Fifty Thousand Four Hundred..."*)
- **Mobile Friendly**: Responsive dual-mode UI with a convenient mobile card editor and full A4 print preview.
- **Pixel-Perfect A4 Print / PDF Export**: Strictly fitted for single-page A4 output with authentic company emblem, dual QR codes, and official company stamp & signature.

## 📂 Project Structure

```
├── index.html           # Complete single-file web application (HTML, CSS, JS, embedded assets)
├── assets/              # High-resolution logos, stamps, and QR assets
│   ├── logo_exact.png
│   ├── stamp_official.png
│   ├── qr_code_main.png
│   └── qr_code_footer.png
├── .gitignore           # Git ignore rules
└── README.md            # Documentation
```

## 💻 How to Use

1. Simply open `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox).
2. Upload your monthly timesheet (`.xlsx`) to auto-fill the workers and hours.
3. Review or adjust invoice details (Date, Invoice No, Client details).
4. Click **Download / Print PDF** to generate a clean, single-page A4 PDF.
