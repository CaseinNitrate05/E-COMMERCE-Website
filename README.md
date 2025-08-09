# 🛍️ Trendigo E-Commerce

A modern, responsive e-commerce web app built with **Django**, **Tailwind CSS**, and **Font Awesome**.  
Features include category browsing, live product search, product detail pages, and authentication.

## 🌐 Live Demo
[Click here to try Trendigo](YOUR_LIVE_DEMO_URL)

---

## 📌 Features

- **Responsive Design** – Optimized for desktop, tablet, and mobile devices.
- **Dynamic Categories** – Browse products by categories with visually appealing cards.
- **Live Search** – Search for products instantly without reloading the page.
- **User Authentication** – Login, logout, and user dashboard for personalized experience.
- **Shopping Cart** – Add products to the cart with a stylish cart icon in the header.
- **Modern UI** – Styled with Tailwind CSS, dark theme, and smooth hover animations.
- **Django Backend** – Uses Django template tags (`{% static %}`, `{% url %}`) for dynamic content.

---

## 🛠️ Tech Stack

- **Backend:** Django
- **Frontend:** HTML, Tailwind CSS, Font Awesome
- **JavaScript:** Axios for live search requests
- **Templating:** Django Templates with `{% static %}` and `{% url %}` tags
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

E_Commerce/
│
├── cart/         # Shopping cart app
├── core/         # Core settings and main configuration
├── E_Commerce/   # Project settings (Django project root)
├── media/        # Uploaded media files
├── orders/       # Orders app
├── products/     # Product management app
├── users/        # Authentication and user profiles
├── db.sqlite3    # SQLite database

---

## 🚀 Running the Project Locally
# 1️⃣ Navigate to your project folder
cd path/to/your/E_Commerce

# 2️⃣ Create a virtual environment
python -m venv venv

# 3️⃣ Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# 4️⃣ Install required dependencies
pip install -r requirements.txt

# (If you don't have a requirements.txt yet, you can install the basics)
pip install django pillow

# 5️⃣ Run database migrations
python manage.py makemigrations
python manage.py migrate

# 6️⃣ Create an admin superuser
python manage.py createsuperuser

# 7️⃣ Start the development server
python manage.py runserver

