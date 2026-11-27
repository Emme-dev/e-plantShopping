# Paradise Nursery

**Paradise Nursery** is an online plant shop built with React and Redux Toolkit.
Shoppers can browse houseplants by category, add them to a shopping cart, adjust
quantities, remove items and see the total cost update instantly.

## Features

- **Landing page** with a background image, the company name, a short company
  description and a **Get Started** button.
- **Product listing page** with 18 unique houseplants grouped into three
  categories (Air Purifying, Aromatic & Fragrant, Low Maintenance). Each plant
  shows a thumbnail, name, description and price.
- **Add to Cart** buttons that add the plant to the cart, disable once the plant
  is added, and increment the cart icon count.
- **Navbar** on the Product Listing and Cart pages with links to Home, Plants and Cart,
  plus a cart icon showing the total number of items.
- **Shopping cart page** showing each plant's thumbnail, name, unit price and
  subtotal, buttons to increase/decrease quantity, a delete button, the total
  number of plants, the total cart amount, a **Checkout** button (Coming Soon)
  and a **Continue Shopping** button.

## Tech stack

- React 18 (Vite)
- Redux Toolkit + React Redux

## Project structure

```
src/
  App.jsx          Landing page and page switching
  App.css          Landing page styles (background image)
  AboutUs.jsx      About the company
  ProductList.jsx  Plant catalogue, navbar, Add to Cart
  CartItem.jsx     Shopping cart page
  CartSlice.jsx    Redux slice: addItem, removeItem, updateQuantity
  store.js         Redux store
  main.jsx         App entry point
```

## Run locally

```bash
npm install
npm run dev
```

## Deploy to GitHub Pages

```bash
npm run build
npm run deploy
```
