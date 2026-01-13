## 1. Project Description

This project is a **Secure E-Commerce Web Application** developed using the **Django framework**. The system allows users to browse products, manage a shopping cart, and place orders in a secure web environment.

The main goal of this project is to apply **Secure Software Development (SSD)** practices. The application uses Django’s built-in security mechanisms to protect against common web vulnerabilities such as **SQL Injection, Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF)**.

Sensitive information such as secret keys and database credentials is handled securely using environment variables instead of being hardcoded in the source code.

<div id="user-content-toc">
  <ul style="list-style: none;">
    <summary>
      <h1>MAKE SURE TO INSTALL PYTHON AND DJANGO BEFORE PROCEED</h1>
    </summary>
  </ul>
</div>

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

1. Open the Project Folder
   Ensure you are inside the folder that contains the manage.py file.\
   Example path: C:\Users\user\Desktop\django-secure-ecommerce-SSD

2. Open the Terminal in the Project Folder
   The easiest ways:\
   - In VS Code: Press Ctrl + ` (backtick). The terminal will open automatically in the project directory.
   - Alternatively: Right-click the folder in File Explorer → Select Open in Terminal.

3. Activate the Virtual Environment (REQUIRED)
   In the terminal, type:\
   ```bash
   venv\Scripts\activate
   ```
   If successful, you will see (venv) appear at the beginning of the command line.\
📌 Note: If you aren't sure of your virtual environment's name, type dir to list the folders and look for the environment folder (usually named venv or .venv).

4. Run the Django Server
   ```bash
   python manage.py runserver
   ```
   Once it starts, you should see: Starting development server at http://127.0.0.1:8000/

5. Open Your Browser
   - Main Site: http://127.0.0.1:8000/
   - Login Page: http://127.0.0.1:8000/login
## 5. Dependencies
- Login page
- Product listing page
- Shopping cart page
- Admin dashboard
- README.md file on GitHub

<img width="1905" height="945" alt="Homepage" src="https://github.com/user-attachments/assets/eb9c057d-f7c6-48b0-988d-da5abc2afa46" />
<img width="1916" height="951" alt="search" src="https://github.com/user-attachments/assets/fee55677-b8fc-43f3-9275-a771bf0fe6f4" />
<img width="1918" height="950" alt="Screenshot 2026-01-13 213133" src="https://github.com/user-attachments/assets/072f3248-8c5c-42d7-b42d-c5bb7b4cef19" />
<img width="1919" height="952" alt="Screenshot 2026-01-13 213147" src="https://github.com/user-attachments/assets/508ae038-e41d-4bc5-818e-37723fa93249" />
<img width="1907" height="946" alt="Screenshot 2026-01-13 213228" src="https://github.com/user-attachments/assets/21feb767-b4d1-4465-9995-27be470e5f9f" />
<img width="1914" height="951" alt="Screenshot 2026-01-13 213248" src="https://github.com/user-attachments/assets/90364538-a7df-475e-acef-fc47edace8e4" />
<img width="1903" height="950" alt="Screenshot 2026-01-13 213306" src="https://github.com/user-attachments/assets/a375ee40-8df1-4d4e-8cfc-015faeecfe38" />

