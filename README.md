# 🛒 Flipkart Clone – E-Commerce Web Application

## 💡 Overview
This is a fully functional e-commerce web application inspired by Flipkart. It includes features like product listings, shopping cart, checkout, user authentication, and an admin dashboard.

## ⚙️ Tech Stack

- **Frontend**: React, Bootstrap
- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL
- **Authentication**: JWT / Django Auth
- **Payment Integration**: Stripe (Test Mode)
- **Deployment**: Coming Soon

---

## 🚀 Features

- ✅ User registration & login  
- ✅ Product browsing and search  
- ✅ Add to cart and checkout  
- ✅ Stripe payment gateway integration  
- ✅ Admin dashboard to manage products and orders  
- ✅ Responsive UI (mobile + desktop)

---

## 📸 Screenshots

_Add screenshots of your app UI here_  
Example:
- `screenshots/homepage.png`
- `screenshots/cart.png`
- `screenshots/admin-panel.png`

---

## 🛠️ Local Setup Instructions

### Backend (Django)

```bash
# Clone the repo
git clone https://github.com/07Raunak/flipkart-clone.git
cd flipkart-clone/backend

# Create virtual environment
python -m venv env
env\Scripts\activate     # For Windows
# source env/bin/activate (Linux/Mac)

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver

