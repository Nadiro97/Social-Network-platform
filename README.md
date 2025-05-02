# 🌐 Django Social Network

A mini social network web app built with Django that supports posting, following other users, liking posts, and pagination — all with a dynamic frontend powered by JavaScript.

---

## 📌 Features

- 🧾 User authentication: Register, login, logout
- ✍️ Create new posts
- 👀 View all posts or posts by specific users
- ❤️ Like and unlike posts
- ✏️ Edit your own posts in-place using JavaScript
- 🔁 Follow/unfollow users
- 📄 “Following” feed showing posts from followed users
- 🔢 Pagination for better user experience

---

## ⚙️ Technologies Used

- **Python 3.x**
- **Django Web Framework**
- **HTML / CSS**
- **JavaScript (Fetch API)**
- **SQLite** (for development)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Set up a virtual environment (optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install django
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Run the development server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000` in your browser.

---

## 📁 Project Structure

```
project4/                 # Django settings & project config
network/                  # Social network app
  ├── models.py           # Post and User following models
  ├── views.py            # Core views
  ├── urls.py             # App-specific routing
  ├── static/network/     # JavaScript and CSS files
  ├── templates/network/  # HTML templates
  └── migrations/         # Database schema

manage.py                 # Django management script
```

---

## ✍️ Author

Developed by **Nadiro97**

