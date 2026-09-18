# 🍱 MealNexa

### Smart Surplus Food Redistribution Platform

MealNexa is a Python-Django based web application designed to connect **surplus food donors** with **NGOs and volunteers**. The platform helps redistribute safe, usable surplus food to people in need instead of allowing it to go to waste.

---

## 🎯 Project Objective

The main goal of MealNexa is to provide a digital platform where:

* Restaurants, hotels, event organizers, and individuals can list surplus food.
* NGOs can discover and request available food.
* Volunteers can manage food pickup and delivery.
* Administrators can monitor and manage the entire platform.

---

## 🚀 Key Features

### 👤 User Authentication

* User registration
* Login and logout
* Role-based access
* Secure authentication

### 🍽️ Donor Module

* Add surplus food
* Upload food images
* Enter food quantity and type
* Add pickup location
* Set food availability/expiry time
* Track donation status

### 🏢 NGO Module

* View available food
* Search and filter donations
* Request available food
* Track request status
* View donation history

### 🚚 Volunteer Module

* View assigned pickups
* Accept pickup tasks
* Update pickup status
* Update delivery status
* Track completed deliveries

### 🛠️ Admin Module

* Manage users
* Verify donors and NGOs
* Manage food donations
* Manage requests
* Manage volunteers
* Monitor platform activity

### 🧠 Smart Food Priority System

MealNexa can prioritize food based on factors such as:

* Remaining freshness time
* Quantity
* Distance
* Pickup urgency

This helps ensure food that needs immediate collection is handled first.

---

## 🔄 Application Workflow

```text
Donor
  ↓
Register / Login
  ↓
Post Surplus Food
  ↓
Food Verification
  ↓
NGO Finds Available Food
  ↓
Request Food
  ↓
Volunteer Assigned
  ↓
Food Pickup
  ↓
Food Delivered
  ↓
Donation Completed
```

---

## 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend

* Python
* Django
* Django REST Framework

### Database

* MySQL

### Development Tools

* Visual Studio Code
* Git
* GitHub

---

## 📂 Project Structure

```text
MealNexa/
│
├── .venv/
│
├── accounts/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── donations/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── requests/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── mealnexa/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── .gitignore
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/MealNexa.git
```

### 2. Open the project

```bash
cd MealNexa
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply migrations

```bash
python manage.py migrate
```

### 7. Create an admin user

```bash
python manage.py createsuperuser
```

### 8. Start the development server

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

---

## 🔐 Security

MealNexa is designed with basic web application security practices, including:

* Django authentication
* CSRF protection
* Role-based permissions
* Se
