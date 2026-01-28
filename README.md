# Personal Expense Tracker

![Expense Tracker UI](https://github.com/hemantshirsath/Expensetracker/assets/102463335/f31d97f4-4841-44cb-b2af-62286c60a0c9)
![Forecast Expense UI](https://github.com/hemantshirsath/Expensetracker/assets/102463335/c1188567-39c5-4cc1-8916-24f3d3712ee8)
![Forecast Expense UI 2](https://github.com/hemantshirsath/Expensetracker/assets/102463335/a2088949-c4f6-4d18-ba23-308ce3ad19f4)
![Expense-wise Report UI](https://github.com/hemantshirsath/Expensetracker/assets/102463335/c3271340-d3ea-4171-9618-04c8c0a98759)

### Django · Machine Learning · Forecasting · Web Application

A **personal expense tracker web application** built using **Django** that helps users record, analyze, and predict their expenses. The system supports intelligent expense categorization and future expense forecasting using machine learning techniques, enabling better budgeting and financial planning.

This project demonstrates practical skills in **backend web development, data modeling, ML integration, and user authentication**, making it suitable for **Software Development Engineer (SDE)** and **Full-Stack Developer** roles.

---

## 🚀 Key Features

### 💸 Expense Logging

* Log daily expenses with:

  * Date
  * Description
  * Amount
  * Category
* Simple and intuitive expense entry workflow

### 🤖 Automated Expense Categorization

* Uses **machine learning algorithms** to classify expenses based on descriptions
* Reduces manual categorization effort
* Improves tracking accuracy over time

### 📈 Future Expense Prediction

* Predicts future expenses based on historical spending patterns
* Helps users plan budgets and manage finances proactively

### 🔐 User Authentication

* Secure user registration and login system
* Each user can manage their own expense data privately

---

## 🛠 Tech Stack

### Backend

* Python
* Django

### Machine Learning

* Automated expense classification
* Expense forecasting models

### Database

* SQLite (default, easily configurable)

### Frontend

* HTML
* CSS
* Django Templates

---

## ⚙️ Setup & Installation

Follow the steps below to run the application locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/varunn912/personal-expense-tracker.git
cd personal-expense-tracker
```

### 2️⃣ Create and Activate Virtual Environment (Recommended)

```bash
python -m venv venv
```

**Activate the environment:**

* Windows:

```bash
venv\\Scripts\\activate
```

* macOS / Linux:

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Database Migrations

```bash
python manage.py migrate
```

### 5️⃣ Create Superuser (Admin Access)

```bash
python manage.py createsuperuser
```

### 6️⃣ Start Development Server

```bash
python manage.py runserver
```

Open your browser and navigate to:

```
http://localhost:8000
```

---

## 📊 Usage

1. Create a new account or log in
2. Click **Add Expense** to log daily spending
3. Enter expense details (category can be left empty for auto-categorization)
4. View:

   * Expense history
   * Category-wise breakdown
   * Future expense predictions on the dashboard

### Admin Panel

* Access: `http://localhost:8000/admin/`
* Manage users, categories, and application data

---

## 🤝 Contributing

Contributions are welcome! Follow the steps below:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your fork

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 🙌 Acknowledgments

* Thanks to the **Django community** for the powerful and flexible web framework
* Machine learning features built using open-source libraries and datasets

---

## 👨‍💻 Author

**Kamshetty Varun**
B.Tech – Computer Science & Engineering (AI & ML)


---

Happy budgeting! 💰
