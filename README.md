# 🛒 Django E-Commerce Website

**Python | Django | Bootstrap | JavaScript | jQuery | PostgreSQL | Razorpay**

A full-stack E-Commerce web application built using **Django** and **Python**. The application provides a complete online shopping experience, including user authentication, product management, shopping cart, wishlist, coupon system, secure online payments, and an administrative dashboard.

🎯 **Built as a portfolio project to demonstrate full-stack Django web development skills.**

---

# 🚀 Features

## 🛍️ Shopping Experience

* User registration and secure authentication
* Product catalog with categories and subcategories
* Product search functionality
* Product detail page with image gallery
* Featured and latest products
* Responsive user interface
* Pagination
* Wishlist functionality

---

## 🛒 Shopping Cart

* Add, update and remove cart items
* Session-based cart for guest users
* Database-backed cart for logged-in users
* Automatic cart total calculation
* AJAX-powered cart updates

---

## 💳 Checkout & Payments

* Multiple shipping addresses
* Coupon and discount system
* Razorpay payment gateway integration
* Cash on Delivery (COD)
* Secure order placement
* Payment verification

---

## 📦 Order Management

* Order history
* Order tracking
* Order status updates
* Invoice generation
* Order cancellation

---

## 👤 User Accounts

* Registration
* Login & Logout
* Password reset
* Profile management
* Address management

---

## 🧑‍💼 Admin Dashboard

Custom admin dashboard for managing:

* Products
* Categories
* Users
* Orders
* Coupons
* Product Images
* Sales Reports
* Dashboard Statistics

---

# 🛠️ Tech Stack

| Layer           | Technology             |
| --------------- | ---------------------- |
| Backend         | Python, Django         |
| Database        | PostgreSQL / SQLite    |
| Frontend        | HTML5, CSS3, Bootstrap |
| Scripting       | JavaScript, jQuery     |
| Payment Gateway | Razorpay               |
| Authentication  | Django Authentication  |
| Version Control | Git & GitHub           |

---

# 📁 Project Structure

```
django-ecommerce/

├── ecommerce_project/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── products/
├── customers/
├── cart/
├── checkout/
├── orders/
├── payments/
├── templates/
├── static/
├── media/
├── manage.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/shifanapp/django-ecommerce.git

cd django-ecommerce
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Apply Migrations

```bash
python manage.py migrate
```

---

## Create Superuser

```bash
python manage.py createsuperuser
```

---

## Run Server

```bash
python manage.py runserver
```

Visit:

```
http://127.0.0.1:8000/
```

---

# 📸 Screenshots

* 🏠 Home Page
* 🛍️ Product Listing
* 📄 Product Details
* ❤️ Wishlist
* 🛒 Shopping Cart
* 💳 Checkout
* 📦 Order History
* 📊 Admin Dashboard

(Add screenshots inside the `screenshots/` folder.)

---

# 🔒 Environment Variables

Create a `.env` file:

```
SECRET_KEY=your_secret_key

DEBUG=True

DATABASE_NAME=your_database

DATABASE_USER=your_username

DATABASE_PASSWORD=your_password

RAZORPAY_KEY_ID=your_key

RAZORPAY_KEY_SECRET=your_secret
```

---

# 🚀 Future Improvements

* Email verification
* Product reviews & ratings
* REST API using Django REST Framework
* Docker support
* AWS S3 media storage
* Elasticsearch integration
* Stripe payment gateway
* Recommendation system

---

# 👨‍💻 Author

**Shifana PP**

Python | Django Developer

GitHub:
https://github.com/shifanapp

---

# 📄 License

This project is licensed under the MIT License.
