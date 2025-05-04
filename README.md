# 🍽️ Django Food App

This is my **first Django project**, built with enthusiasm, curiosity, and lots of learning! 🎉  
The app is a simple food management system with user authentication, built using the Django framework and organized into two main apps: `food` and `users`.

---

## 🧩 What's Included

- 📦 **Django 5.2 project** with standard project structure
- 👥 User system (`users` app) with registration, login, and profile features
- 🍕 CRUD functionality for food items (`food` app)
- 🛠️ Well-structured models, views, and forms
- 🔒 Basic access control and clean separation of concerns
- 📡 **Django Signals** are planned (and will be added soon) to automate model-related actions

---

## 🛠 Tech Stack

- Python 3.13
- Django 5.2
- SQLite (default database)
- Bootstrap 5 (for styling)
- HTML/CSS templates
- Git + GitHub for version control

---

## 🚀 Getting Started (Local Setup)

1. Clone the repo:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name/mysite
```

2. Create a virtual environment and activate it:

```bash
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt  # if you have this file
```

4. Run migrations:

```bash
python manage.py migrate
```

5. Start the development server:

```bash
python manage.py runserver
```

6. Visit the app at [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🔮 Roadmap / Coming Soon

- [x] Split features into modular Django apps
- [x] Add `signals.py` for automated model actions (e.g. user profile creation)
- [x] Improve the frontend (Bootstrap)
- [x] Add pagination
- [ ] Write unit tests
- [ ] Add Docker support

---

## 💡 Why This Project?

This is my **first step into Django and backend development**.  
It helped me understand how Django handles routing, views, forms, and user management. I’m continuously improving it as I learn more about Django best practices and features like signals, custom middleware, testing, and deployment.

---

## 📜 License

This project is licensed under the MIT License.

---

**Thanks for checking it out! 🙌**
