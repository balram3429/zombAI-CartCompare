# 🛒 zombAI‑CartCompare

![Status](https://img.shields.io/badge/status-active-success)
![HTML](https://img.shields.io/badge/stack-vanilla%20HTML%20%7C%20JS-blue)
![Responsive](https://img.shields.io/badge/mobile-responsive-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

```
███████╗ ██████╗ ███╗   ███╗██████╗       █████╗ ██╗
╚══███╔╝██╔═══██╗████╗ ████║██╔══██╗     ██╔══██╗██║
  ███╔╝ ██║   ██║██╔████╔██║██████╔╝     ███████║██║
 ███╔╝  ██║   ██║██║╚██╔╝██║██╔══██╗     ██╔══██║██║
███████╗╚██████╔╝██║ ╚═╝ ██║██████╔╝     ██║  ██║██║
╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚═════╝      ╚═╝  ╚═╝╚═╝
         IPL ORACLE · POWERED BY ZOMBAI · @balram3429
```

---
**zombAI‑CartCompare** is a lightweight **quick‑commerce price
comparison web app** that simulates comparing grocery prices across
India's leading delivery platforms.

It demonstrates how a modern **cart comparison experience** could work
across:

-   Blinkit
-   Zepto
-   Swiggy Instamart

The entire project runs from **a single self‑contained HTML file** with
**no frameworks or dependencies**.

------------------------------------------------------------------------

# 🚀 Demo Concept

The app mimics how a **real quick‑commerce comparison engine** would
work:

1.  Add products to your cart
2.  Select your city
3.  Compare prices across platforms
4.  Instantly see the **cheapest platform and savings**

------------------------------------------------------------------------

# ⚠️ Why Real Web Scraping Is Not Used

Scraping Blinkit, Zepto, and Instamart directly from the browser **is
not technically feasible** because:

-   These platforms block **Cross-Origin Requests (CORS)**
-   They require **authenticated sessions and login tokens**
-   They rely on **location cookies created by their mobile apps**
-   They actively **detect and block scraping activity**

A real production solution would require:

-   Server‑side proxy services
-   Official partner APIs
-   Authenticated request handling

This project therefore **simulates real pricing behaviour instead**.

------------------------------------------------------------------------

# 🧠 Smart Simulation Engine

Instead of scraping live prices, the app uses a **realistic pricing
simulation system** that includes:

-   Platform-specific price variance
-   City cost‑of‑living adjustments
-   Delivery fee logic
-   Free delivery thresholds
-   Availability by city

This creates a **very realistic quick‑commerce comparison experience**.

------------------------------------------------------------------------

# ✨ Key Features

## 🥕 Product Catalog

-   **31 grocery products**
-   Categories include:
    -   Vegetables
    -   Fruits
    -   Staples
    -   Dairy

Includes:

-   Search functionality
-   Quick‑add product chips
-   Quantity controls

------------------------------------------------------------------------

## 🏙 Multi‑City Support

Supports **18 cities across India** with accurate platform availability.

Example:

  City         Blinkit   Zepto   Instamart
  ------------ --------- ------- -----------
  Bangalore    ✓         ✓       ✓
  Chennai      ✓         ✓       ✓
  Madurai      ✗         ✗       ✓
  Coimbatore   ✗         ✓       ✓

Platform availability changes based on the selected city.

------------------------------------------------------------------------

## ⚡ Live Comparison Engine

The comparison system calculates:

-   Platform product pricing
-   Delivery charges
-   City multipliers
-   Free delivery eligibility

It then determines the **best overall platform for the cart**.

------------------------------------------------------------------------

## 🏆 Winner Banner

Displays the **best platform for the current cart** including:

-   Total price
-   Savings amount
-   Platform logo

------------------------------------------------------------------------

## 📊 Summary Cards

Three cards compare:

-   Blinkit
-   Zepto
-   Instamart

Each card shows:

-   Total cart cost
-   Delivery fee
-   Availability status
-   Animated price comparison bar

------------------------------------------------------------------------

## 📋 Item‑Wise Price Table

Every product is compared across platforms.

Badges include:

-   [x] **Best Price**
-   ↑ **Highest Price**

This allows users to easily identify pricing differences.

------------------------------------------------------------------------

## 🤖 Smart AI Suggestions

The system provides **smart recommendation text** explaining:

-   Which platform is cheapest
-   Whether delivery fees apply
-   If splitting the order saves money

The architecture allows this logic to be powered by **AI APIs such as
Claude**.

------------------------------------------------------------------------

# 📱 Mobile‑First Design

The interface is designed to feel like a **real quick‑commerce app**.

Features include:

-   Fully responsive layout
-   Mobile‑friendly controls
-   Smooth cart interaction
-   Clean modern UI

Works across:

-   Mobile phones
-   Tablets
-   Desktop browsers

------------------------------------------------------------------------

# 🧩 Tech Stack

This project intentionally uses a **minimal technology stack**.

  Layer     Technology
  --------- --------------------------
  UI        HTML5
  Logic     Vanilla JavaScript
  Styling   CSS3
  Data      Simulated pricing engine

No frameworks. No build tools. No dependencies.

------------------------------------------------------------------------

# 📦 Project Structure

The entire project lives in a single file:

    cartcompare.html

This file contains:

-   UI
-   product data
-   pricing logic
-   city availability logic
-   comparison engine

------------------------------------------------------------------------

# 🚀 How to Use

1.  Download the repository
2.  Open the HTML file in any browser

```{=html}
<!-- -->
```
    cartcompare.html

No installation required.

------------------------------------------------------------------------

# 🔮 Future Improvements

Possible production upgrades:

-   Real pricing APIs
-   Server-side proxy scraping
-   User location detection
-   Saved carts
-   Historical price tracking
-   AI‑powered shopping optimization

------------------------------------------------------------------------

# 💡 Use Cases

This project demonstrates how to build:

-   Grocery price comparison apps
-   Quick‑commerce aggregators
-   Shopping optimization tools
-   AI‑assisted purchasing platforms

------------------------------------------------------------------------

# 👨‍💻 Author

**Powered by Zomb‑AI**\
Created by **balram3429**

------------------------------------------------------------------------

# ⭐ Support

If you find this project useful:

-   ⭐ Star the repository
-   🍴 Fork it
-   🧠 Build your own version

Happy coding 🚀
