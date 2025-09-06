# 🛒 Add to Cart App using React Router

This project is a **ReactJS shopping cart application** built with **React Router** for navigation.  
It fetches products from the **Fake Store API** and allows users to add/remove items from the cart, adjust quantities, and view the total price with discounts applied.  

---

## 🚀 Features
- Fetch products from [Fake Store API](https://fakestoreapi.com/).
- Display products with **image, title, price, and description**.
- **Responsive product layout** using Tailwind CSS.
- Add or Remove products from the cart.
- If a product is already in the cart → shows **"Remove from Cart"** button.
- Cart page includes:
  - Product name, price, and quantity controls.
  - Increase/Decrease product quantity.
  - Show total price for each item (price × quantity).
  - Show **cart total price** dynamically.
  - Apply **10% discount** on the final total.
- Navigation between **Product Page** and **Cart Page** using React Router.
- Clean and well-documented code.

---

## 🛠️ Tech Stack
- **ReactJS**
- **React Router DOM**
- **Tailwind CSS** (for styling)
- **JavaScript (ES6+)**
- **HTML5 / CSS3**

---

## 📂 Project Structure# Shopping-cart

add-to-cart-react/
│── public/
│   └── index.html
│
│── src/
│   │── components/
│   │   ├── Navbar.jsx
│   │   ├── ProductCard.jsx
│   │   └── CartItem.jsx
│   │
│   │── pages/
│   │   ├── ProductsPage.jsx
│   │   └── CartPage.jsx
│   │
│   │── context/
│   │   └── CartContext.jsx
│   │
│   ├── App.jsx
│   ├── index.js
│   ├── styles.css   # Tailwind & custom styles
│
│── package.json
│── README.md
│── tailwind.config.js
│── postcss.config.js
