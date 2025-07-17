# online-shopping-clone
# TulsiShop – various online shopping inspired E‑Commerce Prototype


TulsiShop is a **front-end e‑commerce web app** i built with **HTML, CSS, and JavaScript**.  
The project demonstrates **modular JavaScript architecture**, **DOM manipulation**, **cart persistence with localStorage**, and **dynamic price calculation**.

---

## Features
✔ **Product Catalog** – Loaded from a modular `items.js` file  
✔ **Add to Bag** – Users can add items to a shopping cart  
✔ **Persistent Cart** – Cart state stored in `localStorage` using JSON  
✔ **Dynamic Price Calculation** – Computes MRP, discounts, and total amount  
✔ **Separate Cart Page** – Displays added items and price breakdown  
✔ **Modular Code Structure** – Product data separated from UI logic  
✔ **Basic Myntra-Like UI** – Header, navigation, and product grid  

---

## 🛠 Tech Stack
- **HTML5**
- **CSS3** (Flexbox, custom theme)
- **Vanilla JavaScript** (DOM manipulation, localStorage)
- **JSON** (for data persistence)


## How It Works
- **Product Data** – All products are stored in `data/items.js` as an array of objects.
- **Rendering** – JavaScript loops over the product list and injects DOM elements dynamically.
- **Cart Logic** –  
  - When “Add to Bag” is clicked, the product `id` is saved in `localStorage`.
  - Cart page (`bag.html`) retrieves IDs, maps them back to product objects, and calculates:
    - **Total MRP**
    - **Total Discount**
    - **Final Payable Amount**
- **Persistence** – Cart remains intact after page refresh (via `localStorage`).

---

## Current Functionality
- Add items to cart
- View cart with price details
- Remove item (if implemented)
- Persistent cart between sessions

- **This is a basic clone with core features only.**
---

## 🔮 Future Enhancements
- [ ] **Responsive Design** – Optimize for mobile & tablet
- [ ] **Quantity Update** – Increment/decrement items in cart
- [ ] **Category Filter** – Make Men/Women nav links functional
- [ ] **Toast Notifications** – “Added to Bag” alerts
- [ ] **Deployment** – Host on GitHub Pages or Netlify
- [ ] **API Simulation** – Fetch product data from a JSON file or mock API



