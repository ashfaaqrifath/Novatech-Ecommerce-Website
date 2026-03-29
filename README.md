# Novatech Ecommerce Website

A full-stack ecommerce website for a tech store — **Novatech** — built with PHP, MySQL, HTML, CSS, and JavaScript. Features a modern design with a shopping cart, user profiles, wishlist, inventory management, order handling, and a full admin panel.

🌐 [Live Demo](https://novatechfront.netlify.app)

---

## ✨ Features

### Customer Side
- 🏠 **Home / Landing Page** — Modern storefront with product showcase
- 🛍️ **Shop Page** — Browse and filter all products
- 🛒 **Shopping Cart** — Add, update, and remove items
- ❤️ **Wishlist** — Save products for later
- 👤 **User Profiles** — Register, login, view and edit profile
- 📦 **Order Management** — Place and track orders
- 📄 **About & Contact Pages** — Static info pages

### Admin Side
- 🔧 **Admin Panel** — Full dashboard for managing the store
- ➕ **Add Products** — Upload new products with images
- ✏️ **Edit Products** — Update product details
- 🗑️ **Delete Products** — Remove listings
- 📋 **Inventory Management** — Monitor stock
- 🚀 **Publish Handler** — Control product visibility
- 👥 **User Management** — Handle customer accounts

---

## 📁 Project Structure

```
Novatech-Ecommerce-Website/
├── CSS/                    # Stylesheets
├── js/                     # JavaScript files
├── img/                    # Static images & assets
├── uploads/                # User-uploaded product images
├── Docs/                   # Project documentation
│
├── index.php               # Home page
├── shop.php                # Product listing page
├── cart.php                # Shopping cart
├── wishlist.php            # Wishlist page
├── profile.php             # User profile
├── login.php               # Login page
├── logout.php              # Logout handler
├── admin.php               # Admin dashboard
├── about.html              # About page
├── contact.html            # Contact page
│
├── AccountHandler.php      # Registration & login logic
├── CartHandler.php         # Cart add/remove/update logic
├── OrderHandler.php        # Order placement logic
├── AddProduct.php          # Admin: add new product
├── EditProduct.php         # Admin: edit product page
├── EditHandler.php         # Admin: edit product logic
├── DeleteHandler.php       # Admin: delete product logic
├── PublishHandler.php      # Admin: publish/unpublish product
├── EditProfile.php         # User profile edit logic
│
└── LICENSE
```

---

## ⚙️ Requirements

- **PHP 7.4+**
- **MySQL** database
- **Apache** web server (XAMPP / WAMP / LAMP recommended)

---

## 🚀 Setup & Running

1. Clone the repo:
   ```bash
   git clone https://github.com/ashfaaqrifath/Novatech-Ecommerce-Website.git
   ```

2. Move the project folder to your server's root directory:
   - XAMPP → `htdocs/`
   - WAMP → `www/`

3. Create the database:
   - Open **phpMyAdmin**
   - Create a new database (e.g., `novatech_db`)
   - Import the SQL file from the `Docs/` folder

4. Configure the DB connection in the PHP files (look for a `db_connect.php` or connection block):
   ```php
   $host = "localhost";
   $user = "root";
   $password = "";
   $database = "novatech_db";
   ```

5. Start Apache and MySQL via XAMPP/WAMP, then visit:
   ```
   http://localhost/Novatech-Ecommerce-Website/
   ```

---

## 🗂️ Key File Roles

| File | Role |
|------|------|
| `index.php` | Home/landing page |
| `shop.php` | Product browsing |
| `cart.php` + `CartHandler.php` | Cart UI + backend logic |
| `wishlist.php` | Wishlist management |
| `login.php` + `AccountHandler.php` | Auth UI + login/register logic |
| `profile.php` + `EditProfile.php` | Profile view + edit |
| `admin.php` | Admin dashboard |
| `AddProduct.php` | Admin product upload |
| `EditProduct.php` + `EditHandler.php` | Admin product edit |
| `DeleteHandler.php` | Admin product delete |
| `OrderHandler.php` | Order processing |
| `PublishHandler.php` | Product visibility toggle |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Server | Apache (XAMPP/WAMP) |

---

## 📄 License

MIT — © Ashfaaq Rifath
