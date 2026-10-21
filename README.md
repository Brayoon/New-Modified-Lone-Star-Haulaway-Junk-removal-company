# 🚛 Lone Star Haulaway

**Junk removal & cleanout services across Dallas–Fort Worth and North Texas.**

A fast, mobile-friendly, single-page website for a junk removal company. It has no frameworks and no build step: just one `index.html` file.

---

## ✨ Features

- **Service showcase:** construction cleaning, backyard cleaning, bulk pickup, bulk transport to storage units, furniture & appliance removal, hoarding cleanup and estate cleanouts
- **Free-estimate focus:** clear calls to action and a "How It Works" section
- **Service areas:** Dallas, Fort Worth, Plano, Richardson, Allen, Melissa, Fairview, McKinney, Princeton and Anna
- **Online booking form:** collects name, phone, city, date, time window and services needed, then sends the request to the owner by text message
- **Payment options:** card, mobile money, PayPal / Cash App / Zelle and cash on completion
- **Chat widget:** a rule-based assistant that answers common questions about pricing, areas, services and payment
- **FAQ:** expandable questions and answers
- **Tips & blog:** short expandable articles
- **Responsive design:** works on phones, tablets and desktops
- **Dark mode:** follows the visitor's device setting
- **Click-to-call:** one-tap calling from the header and hero

---

## 📁 Project Structure

```
lone-star-haulaway/
├── index.html    # The entire website (HTML, CSS and JavaScript)
└── README.md
```

---

## 🚀 Getting Started

### Run locally
1. Download or clone this repository:
```bash
   git clone https://github.com/Brayoon/lone-star-haulaway.git
```
2. Open `index.html` in any web browser.

### Deploy free with GitHub Pages
1. Push the project to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.
4. Your site will be live at `https://Brayoon.github.io/lone-star-haulaway/`.

You can also drag the project folder onto [Netlify Drop](https://app.netlify.com/drop) or [Cloudflare Pages](https://pages.cloudflare.com/).

---

## 💳 Payments: Important Note

The payment section is a **front-end only** interface. It lets customers choose a payment method and shows them instructions. **It does not process or store payments.**

To accept real online payments, connect a payment provider, for example:

- [Stripe Payment Links](https://stripe.com/payments/payment-links) or Stripe Checkout (cards, Apple Pay, Google Pay)
- [PayPal](https://www.paypal.com/business) or [Square](https://squareup.com/) payment links
- [M-Pesa](https://developer.safaricom.co.ke/) or a mobile money aggregator such as Flutterwave or Paystack

> ⚠️ Never collect raw card numbers in your own form. Always use a provider's hosted checkout.

---

## 📅 Booking: How It Works

The booking form has no server behind it. After a customer fills it in, they get a **"Text my request"** button that opens their messaging app with the details already written and addressed to the business number.

To receive bookings by email or store them in a database, connect the form to a service such as [Formspree](https://formspree.io/), [Netlify Forms](https://docs.netlify.com/forms/setup/) or [Google Forms](https://forms.google.com/).

---

## 🛠️ Built With

- HTML5
- CSS3 (custom properties, grid, flexbox, dark mode)
- Vanilla JavaScript

---

## 🗺️ Roadmap Ideas

- [ ] Completed jobs / before-and-after gallery
- [ ] Customer reviews section
- [ ] Individual landing pages for each city (better local SEO)
- [ ] Connected payment checkout (Stripe / M-Pesa)
- [ ] Booking form connected to email or a database
- [ ] Google Business Profile and analytics

---

## 📞 Contact

**Peter Mbugua**
📱 [+1 (302) 250-0862](tel:+13022500862)
📍 Serving Dallas–Fort Worth, Plano, Richardson, Allen, Melissa, Fairview, McKinney, Princeton and Anna, TX

---

## 📄 License

© 2026 Lone Star Haulaway. All rights reserved.
