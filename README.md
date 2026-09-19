# e-plantShopping

**Paradise Nursery — Plant Shopping Cart Application**

The **e-plantShopping** repository contains a React-based e-commerce application for an online plant shop called *Paradise Nursery*. Users can browse a variety of houseplants, view details such as name, image, and price, and manage their purchases through a fully functional shopping cart.

## Overview

This application demonstrates a shopping cart workflow built with React and Redux Toolkit:

- **Landing Page** — Welcome page with an introduction to Paradise Nursery and a "Get Started" button that navigates to the product listing.
- **Product Listing** — Plants organized by category (e.g., aromatic, medicinal, air-purifying), each with an image, price, and an "Add to Cart" button.
- **Shopping Cart** — View items added to the cart, increase or decrease item quantities, remove items, and see the total cost update dynamically.
- **About Us** — Information about Paradise Nursery.

## Tech Stack

- [React 18](https://react.dev/) — UI library
- [Redux Toolkit](https://redux-toolkit.js.org/) & [React Redux](https://react-redux.js.org/) — State management for the shopping cart
- [Vite](https://vitejs.dev/) — Build tool and development server

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Build for production:

   ```bash
   npm run build
   ```

## Project Structure

```
e-plantShopping/
├── src/
│   ├── App.jsx           # Main app component with landing page
│   ├── ProductList.jsx   # Plant listing with add-to-cart functionality
│   ├── CartItem.jsx      # Shopping cart view and quantity management
│   ├── CartSlice.jsx     # Redux slice for cart state (add, remove, update quantity)
│   ├── AboutUs.jsx       # About Paradise Nursery
│   ├── store.js          # Redux store configuration
│   └── main.jsx          # Application entry point
├── public/
├── index.html
└── vite.config.js
```

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file included in the repository.
