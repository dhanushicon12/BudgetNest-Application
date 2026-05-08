# 💰 BudgetNest - Family Expense Management System

BudgetNest is a Django-based web application designed to help users manage family expenses efficiently. The application allows users to add family members, track expenses, and generate monthly and yearly expense reports securely.

---

# 🚀 Features

## 🔐 Authentication System
- User Registration
- Login & Logout
- Session Management
- Secure Access using `@login_required`

## 👨‍👩‍👧 Family Member Management
- Add Family Members
- Update Member Details
- Delete Members
- Store Income & Age Details

## 💸 Expense Management
- Add Expenses
- Update Expenses
- Delete Expenses
- Track Expenses by Family Member

## 📊 Reports
- Monthly Expense Reports
- Yearly Expense Reports
- Total Expense Calculation

## 🔒 Security
- User-specific data access
- CSRF protection
- Authentication & authorization

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend Language |
| Django | Web Framework |
| SQLite | Database |
| HTML | Frontend Structure |
| CSS | Styling |
| Bootstrap | Responsive Design |
| Django ORM | Database Operations |
| Git & GitHub | Version Control |

---

# 📂 Project Structure

```bash
BudgetNest/
│
├── BudgetNest/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── family/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── migrations/
│
├── static/
├── templates/
├── manage.py
└── db.sqlite3
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/dhanushicon12/BudgetNest-Application.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd BudgetNest-Application
```

## 3️⃣ Create Virtual Environment

```bash
python -m venv env
```

## 4️⃣ Activate Virtual Environment

### Windows
```bash
env\Scripts\activate
```

### Mac/Linux
```bash
source env/bin/activate
```

## 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 6️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

## 7️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

## 8️⃣ Run Server

```bash
python manage.py runserver
```

---

# 🔑 Admin Panel

Access Django Admin Panel:

```bash
http://127.0.0.1:8000/admin/
```

---

# 📸 Main Modules

- Authentication Module
- Family Management Module
- Expense Tracking Module
- Monthly Reports
- Yearly Reports

---

# 🧠 Django Concepts Used

- MVT Architecture
- Django ORM
- CRUD Operations
- Authentication System
- ForeignKey Relationships
- Template Inheritance
- Static Files Handling
- Form Handling

---

# 🗄️ Database Models

## FamilyMembers Model
Stores:
- Member Name
- Age
- Income
- Linked User

## Expenses Model
Stores:
- Expense Purpose
- Expense Amount
- Date
- Related Family Member

---

# 📈 Future Enhancements

- Charts & Graphs
- PDF/Excel Export
- REST API Integration
- Mobile Responsive Dashboard
- Email Notifications
- AI-based Expense Prediction

---

# ❗ Challenges Faced

- ForeignKey relationship handling
- User authentication
- User-based data filtering
- Report generation logic

---

# 🎯 Learning Outcomes

Through this project, I learned:
- Django MVT Architecture
- CRUD Operations
- Authentication & Authorization
- Database Relationships
- ORM Queries
- Debugging & Problem Solving

---

# 👨‍💻 Author

## Dhanush Anumalasetty

- GitHub: https://github.com/dhanushicon12
- LinkedIn: https://linkedin.com/in/dhanush-anumalasetty-b7b6b12b6

---

# ⭐ Conclusion

BudgetNest is a secure and efficient expense management system built using Django. It helps users organize financial records and gain insights into monthly and yearly spending while demonstrating core Django development concepts.
