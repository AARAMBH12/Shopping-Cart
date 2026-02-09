Live-Link->https://grand-mermaid-b40d0a.netlify.app/

# Shopping Cart

A modern, responsive shopping cart application built with React, Redux Toolkit, and Vite. This project allows users to browse products, add them to a cart, and manage their shopping experience seamlessly.

## Features

- **Product Listing**: Browse a curated list of products across categories like mobiles, laptops, and tablets.
- **Add to Cart**: Easily add products to your shopping cart with quantity management.
- **Cart Management**: View, update, and remove items from your cart.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **State Management**: Efficient state handling using Redux Toolkit.
- **Routing**: Smooth navigation between product list and cart pages using React Router.
- **Notifications**: User-friendly toast notifications for actions like adding/removing items.

## Tech Stack

- **Frontend**: React 19
- **Build Tool**: Vite
- **State Management**: Redux Toolkit, React Redux
- **Routing**: React Router DOM
- **Notifications**: React Toastify
- **Styling**: CSS (with potential for CSS frameworks)
- **Linting**: ESLint

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd shopping-cart
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in the terminal).

## Usage

- **Home Page**: View the list of available products. Click "Add to Cart" to add items.
- **Cart Page**: Navigate to `/cart` to view your cart, adjust quantities, or remove items.
- **Navigation**: Use the navbar to switch between the home and cart pages.

## Scripts

- `npm run dev`: Start the development server
- `npm run build`: Build the project for production
- `npm run lint`: Run ESLint for code quality checks
- `npm run preview`: Preview the production build locally

## Project Structure

```
shopping-cart/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── Components/
│   │   ├── Cart.jsx
│   │   ├── Counter.jsx
│   │   ├── Navbar.jsx
│   │   └── Product.jsx
│   ├── redux/
│   │   ├── cartSlice/
│   │   │   └── index.jsx
│   │   ├── counterSlice/
│   │   │   └── index.jsx
│   │   └── store/
│   │       └── index.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── data.js
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js
```
