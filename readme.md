# Rohan Graphics

A responsive, single-page website for a commercial printing business. It presents print products and services, helps visitors estimate order costs, and provides ways to contact the print desk.

## Features

- Filterable product catalog covering business stationery, marketing and signage, packaging and labels, and education printing.
- Interactive price estimator with product and finish options, quantity-based discounts, optional artwork setup and express service, and GST calculation.
- Quote actions that open a prefilled WhatsApp message or copy estimate details into the inquiry form.
- Mobile navigation, print-order workflow, and contact information.

## Run locally

This is a static website; there is no build step or package installation.

1. Open `index.html` in a browser, or start a local server from the project directory:

   ```bash
   python -m http.server 8000
   ```

2. Visit <http://localhost:8000>.

## Technologies

- HTML, CSS, and vanilla JavaScript
- Tailwind CSS via CDN
- Google Fonts (Inter and JetBrains Mono) and Phosphor Icons via CDN

An internet connection is needed to load the CDN-hosted styles, fonts, and icons.

## Notes

- The inquiry form currently displays an on-page confirmation only; it does not send or store submissions. Connect it to a backend or form service before using it to receive customer inquiries.
- Calculator results are estimates based on the rates and rules in `index.html`. Confirm final pricing, specifications, taxes, and availability with the print desk.
- Contact details, WhatsApp number, product rates, discount tiers, and other business information are hard-coded in `index.html`; update them there when needed.
