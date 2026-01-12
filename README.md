## 1. Project Description

This project is a **Secure E-Commerce Web Application** developed using the **Django framework**. The system allows users to browse products, manage a shopping cart, and place orders in a secure web environment.

The main goal of this project is to apply **Secure Software Development (SSD)** practices. The application uses Django’s built-in security mechanisms to protect against common web vulnerabilities such as **SQL Injection, Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF)**.

Sensitive information such as secret keys and database credentials is handled securely using environment variables instead of being hardcoded in the source code.

---

## 2. Installation Steps

Follow the steps below to set up the project locally.

1. Clone the repository:
```bash
git clone https://github.com/your-username/django-secure-ecommerce-SSD.git
```
2. Navigate into the project directory:
```bash
cd django-secure-ecommerce-SSD
```
3. Create and activate a virtual environment:
```bash
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate    # Linux / macOS
```
4. Install required dependencies:
```bash
pip install -r requirements.txt
```
5. Create a .env file using .env.example as a reference.
6. Apply database migrations:
```bash
python manage.py migrate
```

## 3. Security Features Summary
* Django built-in authentication and authorization
* Secure password hashing
* CSRF protection enabled by default
* Secure session management
* Use of environment variables for sensitive data
* ORM-based database queries to prevent SQL Injection
* Input validation and form sanitization

## 4. How to Run the App

1. Start the Django development server:
```bash
python manage.py runserver
```
2. Open your browser and access the application at:
```cpp
http://127.0.0.1:8000/
```

## 5. Dependencies
- Login page
- Product listing page
- Shopping cart page
- Admin dashboard
- README.md file on GitHub
