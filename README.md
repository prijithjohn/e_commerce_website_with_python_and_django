# 🛒 Trivian - E-commerce Website (Django Project)

Trivian is a fully functional e-commerce platform built using **Django**. It supports product browsing, cart functionality, and mock payment integration via Razorpay. The project is developed as part of a college capstone and showcases practical skills in backend, frontend, and payment gateway integration.

---

## 🚀 Features

- Clean and responsive UI using Bootstrap
- Product catalog with descriptions and images
- Add to cart, update, and remove functionality
- Checkout with Razorpay test mode integration
- Admin panel with enhanced UI using Jazzmin
- MySQL database connectivity
- Modular app structure using Django best practices

---

## 🖥️ Technologies Used

| Layer       | Tools/Technologies                    |
|------------|----------------------------------------|
| Backend     | Python, Django                        |
| Frontend    | HTML, CSS, Bootstrap, FontAwesome     |
| Payment     | Razorpay (Mock/Test Mode)             |
| Database    | MySQL                                 |
| Admin UI    | Jazzmin                               |
| Others      | Django Templates, ORM, Sessions       |

---

## 📁 Project Structure

trivian/ ├── prijith_project/ # Django project settings ├── shop/ # Core app for e-commerce logic │ ├── models.py # Models for product, cart, etc. │ ├── views.py # Views and payment logic │ ├── templates/ # HTML templates │ ├── static/ # Static assets ├── static/ # Global static files ├── manage.py # Django project runner

yaml
Copy
Edit

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   git clone https://github.com/yourusername/trivian.git
   cd trivian
 
 2. **Create and activate a virtual environment**
   python -m venv venv
   venv\Scripts\activate     # Windows
   source venv/bin/activate  # macOS/Linux

  3. **Install the dependencies**
    pip install -r requirements.txt
    Update MySQL credentials in settings.py

  4. **Run migrations**
     python manage.py makemigrations
     python manage.py migrate

  5. **Create superuser for admin access**
     python manage.py createsuperuser

  6. **Start the development server**
    python manage.py runserver

---

## 💳 Razorpay Mock Payment Setup

1.**Add Razorpay test credentials to settings.py:**
RAZORPAY_KEY_ID = 'your_test_key_id'
RAZORPAY_KEY_SECRET = 'your_test_key_secret'

2.**Implement payment logic in your checkout_view and handle success in payment_success_view.**

---

## 📸 Screenshots

1. **Home page**
![Screenshot 2025-04-21 202232](https://github.com/user-attachments/assets/b0ca3884-46db-4907-a291-5269c3a97b63)

2. **Registration page**
![Screenshot 2025-04-21 202301](https://github.com/user-attachments/assets/cbf8d236-af8d-4283-9f41-b2e33d349871)

3. **Login page**
![Screenshot 2025-04-21 202327](https://github.com/user-attachments/assets/302eb5ae-b05c-46ba-aca5-f5f432894ac9)

4. **Collection page**
![Screenshot 2025-04-21 202358](https://github.com/user-attachments/assets/71d10313-c05f-4413-be5f-ea77885dbf58)

5. **Cart page**
![Screenshot 2025-04-21 202439](https://github.com/user-attachments/assets/f11c6c66-2a4a-4531-b996-2444201e9f73)

6. **Favourite page**
![Screenshot 2025-04-21 202459](https://github.com/user-attachments/assets/9e45cdde-4037-4b6c-a6c9-2d2a12a1704c)

---

## 👨‍💻 Project Contributors

Prijith – Final Year CSE Student

tutorejose-Stanley – Project Guide and Mentor

---

💡 Feel free to fork, contribute, or customize this project for your own learning and development!  

Let me know if you want help generating a `requirements.txt` or adding a clickable demo section with deployment tips.




