# e-plantShopping 🌿 | Paradise Nursery

A sophisticated e-commerce web application for plant lovers, built with **React** and **Redux Toolkit**. This project showcases a seamless shopping experience from browsing diverse plant categories to managing a dynamic shopping cart.


## 🚀 Demo
You can see the live demo here: [(e-plantShopping)](https://soran-mirzaei.github.io/e-plantShopping/)
---

## 👤 Author
**Soran Mirzaei** *React Developer & Plant Enthusiast*

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Technologies Used](#-technologies-used)
- [Core Logic (Redux Toolkit)](#-core-logic-redux-toolkit)
- [Installation & Setup](#-installation--setup)
- [Folder Structure](#-folder-structure)

---

## 📋 Project Overview
**Paradise Nursery (e-plantShopping)** is more than just a store; it's a digital sanctuary for gardeners. The app provides a specialized landing page, a categorized product listing (Air Purifying, Aromatic, Medicinal, etc.), and a real-time shopping cart.



---

## ✨ Key Features

### 1. Landing Page
- Professional business introduction with a "Where Green Meets Serenity" theme.
- Interactive "Get Started" transition to the shop.

### 2. Categorized Product Listing
- Plants are organized by functionality (e.g., Low Maintenance, Insect Repellent).
- **Smart "Add to Cart" Buttons:** Buttons automatically disable and change text once an item is added, preventing duplicates.
- **Live Cart Badge:** The navbar displays the total quantity of items in the cart in real-time.

### 3. Advanced Shopping Cart
- **Dynamic Updates:** Increase or decrease item quantities directly within the cart.
- **Automatic Removal:** If an item's quantity reaches zero, it is automatically removed from the state.
- **Price Calculation:** Instant calculation of sub-totals for each plant and the grand total for the entire order.

---

## 🛠 Technologies Used
- **React.js** (Hooks: `useState`, `useEffect`, `useSelector`, `useDispatch`)
- **Redux Toolkit** (State Management: `createSlice`, `configureStore`)
- **CSS3** (Responsive Design & Custom Grid Layouts)
- **Vite** (Next-generation frontend tooling)

---

## 🧠 Core Logic (Redux Toolkit)
The project utilizes **Redux Toolkit** to handle complex states.
- **`addItem`**: Checks if the plant exists in the cart; if so, increments quantity, otherwise adds a new object.
- **`updateQuantity`**: Uses **Immer** logic to safely update state without manual cloning.
- **`removeItem`**: Filters the state to remove specific products by name.



---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Soran-Mirzaei/e-plantShopping.git](https://github.com/Soran-Mirzaei/e-plantShopping.git)


   
