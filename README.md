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
<img width="1920" height="920" alt="image" src="https://github.com/user-attachments/assets/97743932-2e04-4f10-9878-962dd9a83c63" />
<img width="1907" height="909" alt="image" src="https://github.com/user-attachments/assets/df8a99f9-41be-4167-9e91-f8077da5b14b" />


* 🛍️ Product Listing
* <img width="1912" height="915" alt="image" src="https://github.com/user-attachments/assets/875a8125-a3f6-4858-8373-1fe8fc0125bc" />
<img width="1901" height="920" alt="image" src="https://github.com/user-attachments/assets/bbd21b17-e52c-4a39-ab08-6b72a43e2f6f" />


* 📄 Product Details
* <img width="1914" height="914" alt="image" src="https://github.com/user-attachments/assets/14cbe0f4-ac55-4316-9bef-1aac8438e7b0" />

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
