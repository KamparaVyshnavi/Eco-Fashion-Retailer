# Eco Fashion Retailer

Eco Fashion Retailer is a frontend-based sustainable e-commerce website designed for eco-friendly fashion shopping. The project focuses on product browsing, sustainability impact tracking, cart management, checkout flow, payment simulation, order confirmation, invoice generation, and basic user authentication.

## Project Overview

The main goal of this project is to promote conscious shopping by showing sustainability-related information for each product. Each product includes details such as eco score, water saved, CO₂ reduced, green reward points, material information, and certifications.

This is a frontend-only project built using HTML, CSS, and JavaScript. It uses browser `localStorage` to manage cart items, user login/register data, orders, and invoice information.

## Tech Stack

- HTML
- CSS
- JavaScript
- Font Awesome
- Browser localStorage

## Features

- Responsive homepage
- Product listing
- Category pages for clothing, accessories, and beauty
- Product search
- Product impact modal
- Add to cart functionality
- Cart quantity update
- Remove item from cart
- Clear cart option
- Cart total calculation
- Shipping and tax calculation
- Eco impact calculation
- Checkout form
- Payment method selection
- Payment simulation
- Order confirmation page
- Invoice generation
- Print invoice option
- Login and registration using localStorage
- Sustainability impact tracking
- Green reward points

## Folder Structure

```text
eco-fashion-retailer/
│
├── assets/
│   └── images/
│       ├── banners/
│       ├── categories/
│       ├── logo/
│       └── products/
│
├── css/
│   ├── auth.css
│   ├── cart.css
│   ├── checkout.css
│   ├── responsive.css
│   └── style.css
│
├── data/
│   └── products.js
│
├── docs/
│   ├── features.md
│   ├── future_scope.md
│   └── project_overview.md
│
├── js/
│   ├── auth.js
│   ├── cart.js
│   ├── checkout.js
│   ├── invoice.js
│   ├── main.js
│   ├── order_conf.js
│   ├── payment.js
│   ├── products.js
│   └── search.js
│
├── pages/
│   ├── accessories.html
│   ├── beauty.html
│   ├── cart.html
│   ├── checkout.html
│   ├── clothing.html
│   ├── invoice.html
│   ├── login.html
│   ├── order_conf.html
│   ├── payment.html
│   └── register.html
│
├── screenshots/
│
├── index.html
└── README.md
```

## Screenshots

### Homepage

![Homepage](screenshots/homepage.png)

### Products

![Products](screenshots/products.png)

### Product Impact

![Product Impact](screenshots/product-impact.png)

### Cart

![Cart](screenshots/cart.png)

### Checkout

![Checkout](screenshots/checkout.png)

### Payment

![Payment](screenshots/payment.png)

### Order Confirmation

![Order Confirmation](screenshots/order-confirmation.png)

### Invoice

![Invoice](screenshots/invoice.png)

### Login

![Login](screenshots/login.png)



## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/KamparaVyshnavi/Eco-Fashion-Retailer-.git
```

2. Open the project folder in VS Code.

3. Install the Live Server extension.

4. Right-click on `index.html`.

5. Click **Open with Live Server**.

## How the Project Works

The project stores product information in `data/products.js`.

JavaScript files dynamically render products, handle search, manage cart operations, save checkout details, simulate payment, generate order confirmation, and display invoice details.

The project uses `localStorage` for storing:

- Cart data
- Registered users
- Current logged-in user
- Current order
- Past orders

## Main Pages

- `index.html` - Homepage
- `pages/clothing.html` - Clothing products
- `pages/accessories.html` - Accessories products
- `pages/beauty.html` - Beauty products
- `pages/cart.html` - Shopping cart
- `pages/checkout.html` - Checkout form
- `pages/payment.html` - Payment simulation
- `pages/order_conf.html` - Order confirmation
- `pages/invoice.html` - Invoice page
- `pages/login.html` - Login page
- `pages/register.html` - Register page

## Limitations

- This is a frontend-only project.
- There is no real backend.
- There is no real database.
- Payment is only simulated.
- Login/register data is stored in browser localStorage.
- Data is stored only in the user's browser.

## Future Scope

- Convert the project to React
- Add backend using Node.js, Express, or FastAPI
- Add a real database using MongoDB or MySQL
- Add real authentication
- Add admin dashboard
- Add seller dashboard
- Add wishlist feature
- Add product filters and sorting
- Add real payment gateway integration
- Add order tracking system
- Add product reviews and ratings
- Improve recommendation system

