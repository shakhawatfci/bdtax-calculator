# Bangladesh Income Tax Calculator (AY 2025-26 & 2026-27)

A simple, responsive, and accurate **income tax calculator** for salaried individuals in Bangladesh, based on the tax rules for **Assessment Years 2025-26** and **2026-27**.

Live Demo: https://yourusername.github.io/tax-calculator

---

## Features

- Auto-selects **2026-27** for current and upcoming year , you can choose 25-26 for last year  and **Permanent Employee** by default  
- Calculates **exempted salary**, **non-taxable limit**, **slab-wise tax**  
- **Investment rebate** with auto-cap & warning  
- **Download result as PNG or PDF**  
- Fully responsive (mobile-friendly)  
- No backend — 100% client-side  

---

## How to Use

1. Open the [live demo](https://shakhawatfci.github.io/bdtax-calculator/)  
2. Fill in your details  
3. Click **"Calculate Tax"**  
4. View result + download as **image** or **PDF**  

---

## Disclaimer

> **This tool is for informational and educational purposes only.**  
> Tax laws are subject to change. The calculations are based on rules observed in the provided tax sheet for **AY 2025-26 and 2026-27**.  
> **No liability is accepted** for any mismatch, error, or loss arising from using this calculator.  
> Always verify with a **qualified tax professional** or the **National Board of Revenue (NBR)** before making financial decisions.

---

## Contribute

Tax rules change every year. **Your help keeps this tool accurate!**

### How to Contribute

1. **Fork** this repository  
2. Make your changes (update slabs, limits, logic, UI, etc.)  
3. Test thoroughly  
4. Open a **Pull Request** with a clear description  

> Example: *"Updated non-taxable limit for females in 2027-28"*  
> Or: *"Fixed investment cap logic for zero salary"*

We welcome:
- Bug fixes  
- New tax years  
- UI improvements  
- Accessibility enhancements  
- Localization (Bangla)

---

## Tech Stack

- HTML5  
- Bootstrap 5  
- JavaScript (ES6)  
- [html2canvas](https://html2canvas.hertzen.com/) – for PNG export  
- [jsPDF](https://github.com/parallax/jsPDF) – for PDF export  

---

## License

[MIT License](LICENSE) – Free to use, modify, and distribute.

---

## Footer (Add to your HTML)

```html
<footer class="text-center mt-5 py-3 text-muted small">
  <p>
    <strong>Disclaimer:</strong> This tool is for reference only. Tax laws may change. 
    We are not liable for any discrepancies. Always consult a tax professional.
  </p>
  <p>
    Made with ❤️ | 
    <a href="https://github.com/shakhawatfci/bdtax-calculator/fork" target="_blank">Fork & Improve</a> | 
    <a href="https://github.com/shakhawatfci/bdtax-calculator/issues" target="_blank">Report Issue</a>
  </p>
</footer>
