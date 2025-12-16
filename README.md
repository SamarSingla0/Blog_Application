# 📝 Blog Application (Django)

A **beginner-friendly Blog Application** built using **Django**, designed to be simple, clean, and easy to use while still supporting essential real-world blogging features like roles, categories, comments, and dashboards.

---

## 🚀 Features

### 🔐 Authentication

* Simple and secure **Django authentication system**
* User signup, login, and logout

### 👥 User Roles

* **Manager** – Full access (manage users, posts, categories)
* **Editor** – Create, edit, and manage blog posts
* **Staff** – Limited administrative access
* **User** – Write blogs and post comments

### 🗂️ Categories

* Blogs organized into **different categories**
* Easy navigation and filtering by category

### ✍️ Blogging System

* Easy-to-use blog editor for writing posts
* Create, edit, and delete blogs
* Clean and readable UI for beginners

### 💬 Comment Section

* Users can comment on blog posts
* Encourages interaction and discussion

### 📊 Dashboard

* Role-based dashboard access
* Higher roles can:

  * Edit or delete posts
  * Manage users
  * Control content visibility

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS (Beginner-friendly UI)
* **Database:** SQLite (default, can be changed)
* **Authentication:** Django Auth System

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. **Create and activate virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Apply migrations**

```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Create superuser**

```bash
python manage.py createsuperuser
```

6. **Run the development server**

```bash
python manage.py runserver
```

Open browser and visit: **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

## 📂 Project Structure (Simplified)

```
blog_project/
│── blog_app/
│── templates/
│── static/
│── manage.py
│── db.sqlite3
```

---

## 🎯 Who Is This Project For?

* Beginners learning **Django**
* Students building academic projects
* Anyone wanting to understand **role-based access** in web apps

---

## 🌱 Future Improvements

* Like & bookmark blogs
* Rich text editor
* Profile management
* REST API integration

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, create a branch, and submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

⭐ If you found this project helpful, don’t forget to star the repository!
