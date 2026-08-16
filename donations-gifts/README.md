# NELMARK TT HUB - Donations & Gifts Platform

## Overview

This is the dedicated donations and gifts platform for the **Global TT Hub Development Division**. It enables clients and individuals to contribute to our strategic development initiatives through a secure CryptoWallet integration.

## Project Structure

```
donations-gifts/
├── index.html          # Main donation page
├── styles.css          # Styling and responsive design
└── README.md           # This file
```

## Features

### 🎯 Purpose
- Accept donations and gifts for global development projects
- Support workforce growth and strategic community investment
- Facilitate secure, transparent transactions
- Build partnerships between countries and communities

### 💳 Payment Integration
- **CryptoWallet Integration** for secure payments
- Widget URL: `https://cwallet.com/t/HCW1NR5Q`
- Customizable button text and styling
- Easy to embed and modify

### 📱 Responsive Design
- Mobile-friendly layout
- Works on all devices (desktop, tablet, mobile)
- Professional, modern design
- Accessible interface

### 🌐 For Clients & Individuals
- Clear information about donation impact
- Secure transaction processing
- Multiple contribution options
- Transparent tracking of initiatives

## How to Use

### 1. View the Page
Open `index.html` in your browser to see the donations platform.

### 2. Customize the Widget
Edit the CryptoWallet widget in `index.html`:

```html
<div class="ccwallet__tipbox__button"
    data-url="https://cwallet.com/t/HCW1NR5Q"
    data-button-type="button"
    data-button-text="Donate Now"
    data-button-style="green"></div>
```

**Customizable Parameters:**
- `data-url` — Target CryptoWallet group/campaign URL
- `data-button-text` — Button label (e.g., "Donate Now", "Support Us")
- `data-button-style` — Button color (e.g., "green", "blue", "red")

### 3. Update Contact Information
Replace placeholder contact details in the HTML:
- Email: `contact@tthubbdev.com`
- Website: `www.tthubbdev.com`

### 4. Customize Styling
Modify `styles.css` to match your brand:
- Colors (primary, secondary, accent)
- Typography
- Layout and spacing
- Responsive breakpoints

## CryptoWallet Integration Details

### Widget Configuration
The widget automatically loads via the `opencc.js` script and identifies elements with the class `ccwallet__tipbox__button`.

### Security
- All transactions processed through CryptoWallet's secure infrastructure
- No sensitive payment data stored locally
- PCI-DSS compliant

### Supported Features
- Real-time transaction processing
- Multiple cryptocurrency options (depends on CryptoWallet setup)
- Donation tracking and receipts
- Donor notifications

## Deployment

### Option 1: GitHub Pages
1. Enable GitHub Pages in repository settings
2. Set source to `main` branch
3. Navigate to `https://flavourablecareeranhobby13-ux.github.io/StarDust/donations-gifts/`

### Option 2: Web Server
1. Copy the `donations-gifts/` directory to your web server
2. Ensure `opencc.js` can load (no CORS issues)
3. Access via your domain

### Option 3: Local Testing
1. Open `index.html` directly in your browser
2. Or use a local server: `python -m http.server 8000`
3. Navigate to `http://localhost:8000/donations-gifts/`

## Customization Guide

### Change Button Color
In `index.html`, modify `data-button-style`:
```html
<div class="ccwallet__tipbox__button"
    data-url="https://cwallet.com/t/HCW1NR5Q"
    data-button-type="button"
    data-button-text="Join Us"
    data-button-style="blue"></div>  <!-- Change to blue, red, etc. -->
```

### Update Content
Edit text in the relevant `<section>` in `index.html`:
- Intro section
- Donation section
- Features section
- Contact section

### Change Brand Colors
In `styles.css`, update CSS variables:
```css
:root {
    --primary-color: #2ecc71;      /* Green */
    --secondary-color: #27ae60;    /* Dark green */
    --accent-color: #3498db;       /* Blue */
    /* ... more colors */
}
```

## Best Practices

1. **Test the Widget** — Verify CryptoWallet integration works before deployment
2. **Update Contact Info** — Ensure donors can reach you
3. **Mobile Testing** — Check responsive design on actual devices
4. **Accessibility** — Use semantic HTML and test with screen readers
5. **Security** — Never store sensitive data in client-side code
6. **SEO** — Add meta tags and descriptive content for search visibility

## Support & Troubleshooting

### Widget Not Appearing
- Ensure `opencc.js` script loads correctly
- Check browser console for errors
- Verify internet connection (script loads from CDN)

### Styling Issues
- Clear browser cache and reload
- Check CSS file is linked correctly
- Test in different browsers

### Payment Issues
- Verify CryptoWallet URL is correct
- Check if group/campaign still exists
- Ensure browser allows third-party scripts

## Future Enhancements

- [ ] Multi-language support
- [ ] Donation history dashboard
- [ ] Email receipts for donors
- [ ] Social sharing integration
- [ ] Analytics and reporting
- [ ] Multiple payment methods
- [ ] Donor testimonials section

## License

This project is part of the StarDust Global Hub and uses the AGPL-3.0 license.

## Contact

**Global TT Hub Development Division**
- Email: contact@tthubbdev.com
- Website: www.tthubbdev.com
- Repository: [StarDust on GitHub](https://github.com/flavourablecareeranhobby13-ux/StarDust)

---

**Last Updated:** August 16, 2026
**Version:** 1.0
