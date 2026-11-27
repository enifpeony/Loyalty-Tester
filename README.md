# Loyalty Tester — Instant Relationship & Alignment Intelligence

**Loyalty Tester** is a zero-friction, single-page web application built for a US audience to evaluate loyalty, trust stability, and behavioral compatibility across dating, marriage, business partnerships, and friendships.

## Key Features

- **Zero-Friction User Flow:** No account sign-ups, emails, or personal contact forms required to run a compatibility scan.
- **US-Localized UX:** Built with American English copy, `MM/DD/YYYY` date inputs, `12-hour AM/PM` time formatting, and dark-mode glassmorphism styling.
- **Adaptive Precision Engine:** Works seamlessly even when a user does not know their own or their partner's exact birth time or birth city.
- **Freemium + 3-Tier Pay-As-You-Go Pricing:**
  - **First Scan Free:** Displays the overall Loyalty Score, Core Dynamic Verdict, primary Green Flag, and primary Friction Risk.
  - **$2 USD (Single Deep Dive):** Unlocks the full Temptation & Trust Index, Emotional Pacing analysis, and hidden behavioral insights.
  - **$5 USD (3-Check Pack):** Unlocks 3 full compatibility reports.
  - **$10 USD (Unlimited Pass):** Unlocks unlimited checks for 30 days.
- **Razorpay International USD Integration:** Uses Razorpay Payment Links with automatic URL parameter credit unlocking (`?tier=2`, `?tier=5`, `?tier=10`).
- **Built-In Compliance Modals:** Includes interactive footer modals for Privacy Policy, Terms & Conditions, Refund & Cancellation Policy, and Contact Support.

## Tech Stack

- **Frontend:** HTML5, Tailwind CSS (via CDN), Vanilla JavaScript (ES6+)
- **State & Credit Tracking:** Browser `localStorage`
- **Payments:** Razorpay International Payment Links (USD)
- **Hosting:** Static hosting via GitHub Pages / Netlify

## Project Structure

```text
loyalty-tester/
├── index.html      # Complete single-file application (UI, alignment logic, Razorpay handler, legal modals)
└── README.md       # Project documentation
