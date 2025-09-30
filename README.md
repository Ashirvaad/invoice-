# Kalakaar Invoice Generator

A simple, professional invoice generator for art commissions, built with HTML, JavaScript, and TailwindCSS. Generate, download, and auto-increment invoices for your art business.

## Features
- Add artwork items with type, size, quantity, and rate
- Auto-fill rates for common artwork types and sizes
- Custom size and manual rate entry support
- Professional PDF invoice generation (with jsPDF & jsPDF-AutoTable)
- Auto-incrementing invoice numbers (stored in browser)
- Responsive, modern UI (TailwindCSS)
- No backend required; runs fully in the browser

## Usage
1. **Clone or download this repository.**
2. Place all files (`index.html`, `main.js` if present, `logo.jpeg`/`icon.ico`, etc.) in the same folder.
3. Open `index.html` in your web browser.
4. Fill in customer and artwork details, add items, and click **Download Invoice** to generate a PDF.

## Project Structure
```
index.html        # Main app (UI and logic)
main.js           # (If present) Additional JS logic
logo.jpeg         # (Optional) Logo for UI
icon.ico          # (Optional) App icon
readme.txt        # (Optional) Additional notes
package.json      # (If present) For dependency management
```

## Development
- All logic is in `index.html` (and `main.js` if used).
- No build step required; just open in browser.
- To change the logo in the PDF, update the base64 string in the script section.

## Do Not Upload
- `release-build/` or `dist/` folders (build outputs)
- System or temporary files

## License
MIT
