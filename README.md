# Paradise Nursery Shopping Application

Paradise Nursery is an online plant shop built with React and Redux Toolkit. Customers can browse houseplants by category, add them to a shopping cart, and manage their cart before checkout.

## Features

- **Landing page** with the company name, a short "About Us" section and a **Get Started** button
- **Product listing page** with plants grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal and Low Maintenance), each showing a thumbnail, name, description and price
- **Add to Cart** buttons that disable once a plant is in the cart
- **Navbar** on every page with links to Home, Plants and Cart, plus a cart icon showing the live item count
- **Shopping cart page** showing each plant's thumbnail, name, unit price and subtotal, with buttons to increase, decrease or delete items, the total cart amount, a **Continue Shopping** button and a **Checkout** button (coming soon)

## Tech Stack

- React 18 + Vite
- Redux Toolkit and React Redux for cart state

## Run Locally

```bash
npm install
npm run dev
```

## Project Structure

| File | Purpose |
|------|---------|
| `src/App.jsx` | Landing page and switch to the product list |
| `src/AboutUs.jsx` | Company description |
| `src/ProductList.jsx` | Navbar, plant catalog and Add to Cart |
| `src/CartItem.jsx` | Shopping cart page |
| `src/CartSlice.jsx` | Redux slice: `addItem`, `removeItem`, `updateQuantity` |
| `src/store.js` | Redux store |
