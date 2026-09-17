STREET FOOD — Arkalyk

A modern bilingual QR menu and online ordering interface for STREET FOOD, Arkalyk, Kazakhstan.

The project is designed for restaurant customers who access the menu by scanning a QR code. It provides a fast, mobile-first experience for browsing the menu, adding items to a cart, selecting an order type, and sending the order via WhatsApp.

Features

* 🇷🇺 Russian / 🇰🇿 Kazakh language support
* 📱 Mobile-first responsive design
* 🍔 Digital restaurant menu
* 🛒 Shopping cart with item management
* 🏠 Multiple order modes:
    * Dine-in
    * Takeaway
    * Delivery
* 📍 Customer location support for delivery
* 💬 WhatsApp order submission
* 🧾 Automatic order summary
* 🗂️ Menu categories with smooth navigation
* ✨ UI animations and interactive elements
* 🌙 Dark, warm restaurant-oriented interface
* ⚡ No framework required

Technologies

* HTML5
* CSS3
* Vanilla JavaScript
* SVG
* Web Geolocation API
* WhatsApp wa.me
* Google Fonts
* tsParticles

Project Structure

/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md

The current version contains the main application interface, styles, menu data, and application logic in index.html.

How It Works

1. A customer scans the restaurant QR code.
2. The digital menu opens in the browser.
3. The customer selects Russian or Kazakh.
4. The customer browses menu categories.
5. Items are added to the shopping cart.
6. The customer selects the order type.
7. Required order information is entered.
8. The generated order is sent through WhatsApp.

For delivery orders, the interface can use the browser’s geolocation functionality to help determine the customer’s location.

Menu Management

Menu items are stored directly in the project code.

To update the menu, edit the corresponding menu data while preserving the existing data structure and language fields.

No backend database is required for the current version.

Deployment

The project can be deployed as a static website using services such as:

* GitHub Pages
* Netlify
* Vercel
* Any standard web server

A public HTTPS address is recommended, especially for browser geolocation functionality.

Privacy

The website may request access to the customer’s browser geolocation when the customer chooses to use location-based delivery functionality.

Location access is controlled by the browser and requires the customer’s permission.

The project itself does not provide a separate backend database for storing customer location data.

License

This project is proprietary software.

The source code is publicly available on GitHub for portfolio, demonstration, and reference purposes only.

It is NOT open source.

See the LICENSE file for the full terms and restrictions.

Copyright

All rights reserved.

Unauthorized copying, redistribution, modification, publication, commercial use, or creation of derivative works is prohibited without prior written permission from the copyright holder.
