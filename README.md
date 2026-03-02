# Tweet App 🐦

A Django-based Tweet application built as part of the learning journey through Hitesh Choudhary's Django series. 

## 🚀 Features
* **User Authentication:** Registration, Login, and Logout functionality.
* **CRUD Operations:** Create, Read, Update, and Delete tweets.
* **User Authorization:** Users can only edit or delete their own tweets.
* **Media Handling:** Support for text and image uploads in tweets.

## 🛠️ Tech Stack
* **Backend:** Python, Django
* **Frontend:** HTML, CSS
* **Database:** SQLite (Default)

## ⚙️ Local Setup & Installation

1. **Clone the repository:**

   git clone https://github.com/yourusername/TweetChai.git
   cd cd TweetChai

2. **Create and activate a virtual environment:**

- python -m venv venv

# Windows:
- venv\Scripts\activate

# macOS/Linux:
- source venv/bin/activate

3. **Install Requirements:**

- pip install django pillow

4. **Run Migrations:**

- python manage.py makemigrations
- python manage.py migrate

5. **Start the server:**

- python manage.py runserver
- Navigate to http://127.0.0.1:8000/tweet in your browser.

📚 Acknowledgments

Based on the Django tutorials by Hitesh Choudhary on YouTube.