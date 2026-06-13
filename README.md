# ⚖️ Meezan Legal — Official Website Under-Production

> *Champions of Justice • Defenders of Truth*

A premium, dark-themed static website for **Meezan Legal**, a boutique law firm based in **Mumbai, India**, founded by **Adv. Sohail**. Built with HTML, Tailwind CSS, and vanilla JavaScript — featuring smooth animations, a typed hero section, EmailJS-powered contact form, and a fully responsive layout.

🌐 **Live Site:** *(add your deployed URL here)*

---

## 🏛️ About the Firm

Meezan Legal  is a senior-led boutique practice offering fearless legal representation across Mumbai's High Courts, Tribunals, and the Supreme Court of India.

---

## 📋 Pages & Sections

| Section | Description |
|---|---|
| **Hero** | Animated typed text showcasing practice areas, gold branding |
| **About** | Firm story, founding partner profile — Adv. Sohail |
| **Practice Areas** | 12 areas of law displayed in a responsive card grid |
| **Team** | Legal team profiles |
| **Our Approach** | Firm methodology and values |
| **Contact** | EmailJS-powered contact/consultation form |

### ⚖️ Areas of Practice Covered

- Civil Litigation
- Property & Real Estate Law
- Arbitration & ADR
- White-Collar Defense & Police Law Interface
- Maintenance & Family Law
- Criminal Litigation & Cyber Crime
- NDPS — Narcotic Drugs and Psychotropic Substances Act
- EOW — Economic Offences Wing
- ED — Enforcement Directorate
- PMLA — Prevention of Money Laundering Act
- CBI — Central Bureau of Investigation
- CID — Crime Investigation Department

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure |
| **Tailwind CSS** (CDN) | Utility-first styling |
| **Vanilla JavaScript** | Animations, typed effect, navbar scroll, hamburger menu |
| **EmailJS** | Contact form email delivery (no backend needed) |
| **Custom CSS** (`style.css`) | Gold theme, reveal animations, hero background |

---

## 🗂️ Project Structure

```
lawsuit/
├── index.html          # Main single-page website
├── style.css           # Custom styles (gold theme, animations)
├── images/
│   ├── MainLogo.png    # Firm logo (circular)
│   └── docIcon.png     # Browser favicon
└── README.md
```
<img width="1882" height="951" alt="image" src="https://github.com/user-attachments/assets/02c1275b-52ba-42d3-8024-fdcfc9d28101" />

<img width="1877" height="947" alt="image" src="https://github.com/user-attachments/assets/950379d6-7092-4615-9a9b-9d7a94364d04" />

---

## 🚀 Running Locally

No build step needed — it's a pure static site right now later will be deployed using Netlify with GoDaddy domain name.

### 1. Clone the Repository

```bash
git clone git@github.com:NateRiver-N/lawsuit.git
cd lawsuit
```

### 2. Open in Browser

```bash
# Simply open the file
open index.html       # Mac
start index.html      # Windows
```

Or use the **VS Code Live Server** extension for hot reload during development.

---

## 📧 EmailJS Setup

The contact form uses [EmailJS](https://www.emailjs.com/) to send emails without a backend.

### To configure it:

1. Create a free account at [emailjs.com](https://www.emailjs.com/)
2. Create an **Email Service** (Gmail, Outlook, etc.)
3. Create an **Email Template**
4. Replace the placeholder in `index.html`:

```js
// Find this line and replace with your actual Public Key
emailjs.init("------");
```

5. Also update your **Service ID** and **Template ID** in the form submission handler.

> ⚠️ Never commit your real EmailJS keys to a public repository.

---

☁️ Deployment
This site is deployed via Netlify with a custom domain registered on GoDaddy. Click "Add new project" or "Add new site" Click "Deploy manually"

Add Your GoDaddy Domain

In Netlify → click your new law firm site Go to Project Configuration → Domain Management Click "Add domain alias"

Update GoDaddy DNS Go to GoDaddy → DNS Management for your new domain: Edit A Record: FieldValueTypeAName@Value75.2.60.5 Add CNAME Record: FieldValueTypeCNAMENamewwwValueyour-netlify-site.netlify.app

Enable SSL

In Netlify → Domain Management → HTTPS Click "Verify DNS configuration" SSL certificate generates automatically in 5–10 minutes 



## 📄 License

This project is private and intended solely for business use.  
All rights reserved © **Meezan Legal**, Mumbai, India.

🍂 Author

Ayaan shafique shaikh

🧑‍⚕️ Sponsered Project created for (Customers)

Adv.Sohail.R Syed & Adv.Shafiqul Shaikh
