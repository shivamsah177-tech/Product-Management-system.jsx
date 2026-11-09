# Product Management System

## 1. Project Overview
The Product Management System is a React-based web application designed to manage product details for a small shopping store. It allows users to add, view, and delete products easily.

## 2. Features
- Add new products.
- Enter Product Name, Product ID, and Price.
- Display all products dynamically.
- Reusable Product Card component using Props.
- Manage product records using React useState Hook.
- Delete products from the list.
- Display a message when no products are available.

## 3. Technologies Used
- **Frontend:** React.js
- **Programming Language:** JavaScript
- **Styling:** CSS
- **Build Tool:** Vite
- **Concepts:** Components, Props, useState Hook

## 4. Project Structure

```text
product-management-system/
│
├── public/
├── src/
│   ├── components/
│   │   └── ProductCard.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── index.html
├── package.json
└── README.md
```

## 5. Installation and Setup

### Step 1: Clone the Repository
```bash
git clone <your-repository-link>
```

### Step 2: Open Project Folder
```bash
cd product-management-system
```

### Step 3: Install Dependencies
```bash
npm install
```

### Step 4: Run the Application
```bash
npm run dev
```

### Step 5: Open in Browser
Open the local URL displayed in the terminal, usually:

```text
http://localhost:5173
```

## 6. Working of the Application

1. Enter the Product Name.
2. Enter the Product ID.
3. Enter the Product Price.
4. Click the **Add Product** button.
5. The product will appear as a Product Card.
6. Click the **Delete** button to remove a product.
7. If no products are available, an appropriate message is displayed.

## 7. React Concepts Used

| Concept | Purpose |
|---|---|
| Components | Divide the application into reusable parts |
| Props | Pass product details to Product Card |
| useState | Store and update product records |
| Event Handling | Handle Add and Delete operations |
| Conditional Rendering | Display an empty-product message |
| map() | Display products dynamically |

## 8. Expected Output

The application displays a product form containing:
- Product Name
- Product ID
- Price
- Add Product Button

Added products are displayed in individual cards with their details and a Delete button.

When the product list is empty, the message **"No products available."** is displayed.

## 9. Conclusion

The Product Management System provides a simple and effective way to maintain product records. This project demonstrates the use of React components, Props, useState, event handling, and conditional rendering. It helps understand the development of dynamic and reusable React applications.

## 10. Author

**Name:** Shivam Sah

**Project:** Product Management System

**Technology:** React.js
