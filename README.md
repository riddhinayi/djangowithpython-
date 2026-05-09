# Django Interior Design Management System

Whitespace Studio is a Final Year Python Django Project for Interior Design and Furniture Management.


# 🏠 Whitespace Studio

Whitespace Studio is a full-stack **interior solutions and furniture e-commerce platform** built using **Python-Django**. It enables users to explore, rate, and purchase modern interior and furniture items while providing sellers and admins with dedicated management dashboards.

## 📌 Project Overview

Whitespace Studio aims to offer an AI-enhanced, user-friendly experience for customers looking for interior design inspiration and furniture purchases. This platform also allows interior designers and sellers to showcase products, manage inventory, and engage with users directly.

## 🚀 Features

### ✅ User Module
- Register/login/logout with secure authentication
- Browse furniture & interior categories
- View product details, images, and reviews
- Add products to cart and place orders
- Make payments via **COD** or integrated **online gateways (e.g., Razorpay/Stripe/PayPal)**
- Track order status
- AI-powered design suggestions (upload room image)

### ✅ Seller Module
- Secure seller login
- Upload & manage products with descriptions and images
- Track orders and inventory
- View customer inquiries and reviews

### ✅ Admin Module
- Manage users, sellers, and products
- Handle orders and disputes
- View analytics (orders, payments, ratings)
- Secure dashboard with filters and search
- Data privacy & validation logic

### ✅ Other Modules
- Ratings & Reviews
- Inquiry/contact system with tracking
- Email notification support
- Dynamic home and category pages
- Responsive frontend UI using HTML, CSS, JS, Bootstrap
- Django SimpleUI admin theme

---

## 🛠️ Tech Stack

| Frontend       | Backend       | Database    | AI Integration | Payment Gateways |
|----------------|---------------|-------------|----------------|------------------|
| HTML, CSS, JS  | Django, Python| SQLite      | OpenAI API     | Razorpay / PayPal|

---

## 📁 Project Structure

whitespace_studio/
│
├── manage.py
├── db.sqlite3
├── templates/
├── static/
├── media/
├── accounts/ # user auth & profiles
├── products/ # product listings, views
├── orders/ # cart, checkout, order mgmt
├── ai_design/ # AI-based design suggestion logic
├── contact/ # contact/inquiry form
└── admin_panel/ # admin configurations

---
🔐 Environment Variables

Create a .env file for secret keys (if used):
      SECRET_KEY=your_secret_key
      DEBUG=True
      OPENAI_API_KEY=your_openai_key
      PAYMENT_API_KEY=your_payment_key

      
## 🔧 Setup Instructions

1. Clone the Repository
   ```bash
   git clone https://github.com/your-username/whitespace-studio.git
   cd whitespace-studio
   
2.Create a Virtual Environment
  #python -m venv env
  #source env/bin/activate  # On Windows: env\Scripts\activate

3.Install Dependencies
  #pip install -r requirements.txt

4.Run Migrations
   #python manage.py makemigrations
   #python manage.py migrate

5.Create Superuser
  #python manage.py createsuperuser

6.Run the Server
  #python manage.py runserver

7.Visit the Site
  Frontend: http://localhost:8000/
  Admin: http://localhost:8000/admin/

## Screenshots 
---> home page
<img width="1179" height="876" alt="image" src="https://github.com/user-attachments/assets/d06eee1a-aea2-4573-bab3-6735381bd3cb" />
---> product page
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/3450d1eb-108f-41c1-b42a-1255b70362ee" />
-->seller page
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/6e9669d4-e41f-403a-839c-adf33cdf62cb" />



