# 🛒 HarzDM — Global Digital Marketplace

> Sell digital products to the world. Multi-seller. Global. Automated.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stripe](https://img.shields.io/badge/Stripe-Integrated-635BFF.svg)](https://stripe.com/)
[![Base44](https://img.shields.io/badge/Base44-Powered-FF4757.svg)](https://base44.com/)
[![AI Images](https://img.shields.io/badge/AI%20Cover%20Images-Generated-ff6b6b.svg)](https://github.com/rabiuhamza11/harzdm-marketplace)
[![Multi-Seller](https://img.shields.io/badge/Multi-Seller-Supported-success.svg)](https://github.com/rabiuhamza11/harzdm-marketplace)

![GitHub last commit](https://img.shields.io/github/last-commit/rabiuhamza11/harzdm-marketplace)
![GitHub repo size](https://img.shields.io/github/repo-size/rabiuhamza11/harzdm-marketplace)

---

## 🌟 Overview

HarzDM is a global digital marketplace hosted at **www.harzdm.com** that enables sellers worldwide to list and sell digital products — ebooks, courses, software, templates, music, and more. Built with automated Stripe payments, real-time seller dashboards, and AI-generated product cover images.

## ✨ Features

- **Multi-Seller Platform** — Multiple sellers with individual stores and profiles
- **Stripe Payments** — Secure checkout with automatic order processing
- **Real-Time Seller Dashboard** — Live revenue, sales counts, and order tracking
- **AI Cover Images** — Auto-generated professional cover art for products
- **Automated Webhooks** — Order status, sales counts, and revenue auto-update on payment
- **Seller Signup** — Onboard new sellers via live signup form
- **90/10 Revenue Split** — 90% to seller, 10% platform fee
- **8 Product Categories** — Ebooks, Courses, Software, Templates, Music, Design, Photography, AI Tools

## 🏗️ Architecture

```
harzdm-marketplace/
├── functions/
│   ├── harzDM.ts              # Main marketplace website
│   ├── harzDMDashboard.ts     # Seller analytics dashboard
│   ├── harzDMCheckout.ts      # Stripe checkout integration
│   ├── harzDMCatalog.ts       # Product catalog API
│   ├── harzDMSellerSignup.ts  # New seller onboarding
│   └── harzDMWebhook.ts       # Stripe webhook handler
├── entities/
│   ├── Product.json           # Product schema
│   ├── Seller.json            # Seller schema
│   └── Order.json             # Order schema
└── README.md
```

## 📊 Current Stats

| Metric | Value |
|--------|-------|
| Products | 19 |
| Sellers | 9 |
| Categories | 8 |
| Revenue Model | 90/10 split |
| Payment Provider | Stripe |

## 🔗 Live URLs

- **Marketplace:** https://superagent-2286fb2f.base44.app/functions/harzDM
- **Dashboard:** https://superagent-2286fb2f.base44.app/functions/harzDMDashboard
- **Domain:** www.harzdm.com

## 💳 Payment Flow

1. Buyer clicks "Buy Now" on product page
2. Redirected to Stripe Checkout (secure, hosted by Stripe)
3. Payment processed → Stripe webhook fires
4. Webhook auto-updates: order status → paid, product sales_count++, seller total_revenue++
5. Buyer receives download link

## 👤 Owner

**Rabiu Hamza Mohammed** — HARZ Digital Marketplace
- Email: harzco.business@gmail.com
- GitHub: [@rabiuhamza11](https://github.com/rabiuhamza11)

## 📄 License

MIT License
