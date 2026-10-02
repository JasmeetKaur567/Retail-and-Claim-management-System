# Retail & Claim Management System

A Django-based **Retail & Claim Management System (RCMS)** designed to streamline and manage product returns, quality control, claim processing, inventory recovery, reconciliation, and operational cost tracking.

## 🚀 Features

* 📦 **Return Management** – Manage customer return records and product details.
* 🔍 **Quality Control (QC)** – Record product inspection results and resale decisions.
* 💰 **Claim Management** – Track claim status and claim recovery.
* 📊 **Dashboard** – View important return, claim, inventory, and cost statistics.
* 📋 **Inventory Management** – Track products waiting for QC, ready for restocking, and repair/quarantine.
* 💵 **Cost & Reconciliation** – Monitor expected costs, actual costs, and operational leakage.
* 🖼️ **Product Image Upload** – Store and manage product images associated with returns.
* 🗃️ **Database Management** – Uses Django ORM for efficient database operations.

## 🛠️ Technologies Used

* **Python**
* **Django**
* **HTML5**
* **CSS3**
* **JavaScript**
* **SQLite** (development database)
* **Django ORM**
* **Git & GitHub**

## 📁 Project Structure

```text
Retail-Claim-Management-System/
│
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── App_Retail_Claim_Management_System/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── ...
│
├── Pro_Retail_Claim_Management_System/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── templates/
├── static/
└── media/
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Retail-Claim-Management-System.git
```

### 2. Open the project

```bash
cd Retail-Claim-Management-System
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply migrations

```bash
python manage.py migrate
```

### 7. Run the development server

```bash
python manage.py runserver
```

Open the application at:

```text
http://127.0.0.1:8000/
```

## 🔐 Security Note

Sensitive information such as secret keys, passwords, environment variables, and production database credentials should not be committed to the repository.

## 📌 Project Status

**Under Development**

The system is being developed with additional dashboard functionality, QC workflows, claim recovery, inventory tracking, and operational analytics.

## 👨‍💻 Author

**Prit Pal Singh**

BBA Student | Django & Business Management Project

---

⭐ If you find this project useful, feel free to explore the repository.
