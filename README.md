# Audio to Sign Language Converter

A web-based system that converts spoken audio into animated sign language gestures to support communication for deaf and hard-of-hearing users. Built using Django, Python, and speech-processing libraries, the tool provides a bridge between verbal language and sign language representation.

Features

🎤 Converts speech/audio input into sign language animations

🔠 Text-based input option

👤 User authentication (Login, Signup, Logout)

🎨 Modern UI with responsive front-end

🧩 Modular and extendable architecture

💡 Supports assistive communication and accessibility

| Layer             | Tools Used                              |
| ----------------- | --------------------------------------- |
| Frontend          | HTML, CSS, JavaScript, Django Templates |
| Backend           | Python, Django                          |
| Speech Processing | `nltk`, Python libraries                |
| Database          | SQLite (local development)              |
| Version Control   | Git & GitHub                            |

A2SL/

│ manage.py

│ requirements.txt

├── A2SL/          # Core Django project

├── templates/     # HTML templates

├── assets/        # Media, animations, gesture files

├── db.sqlite3     # Local database (ignored in git)


🏁 Setup Instructions

1️⃣ Clone the Repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

2️⃣ Create Virtual Environment
python -m venv .venv
.venv\Scripts\activate   # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Apply Migrations
python manage.py migrate

5️⃣ Create Superuser (optional)
python manage.py createsuperuser

6️⃣ Run Server
python manage.py runserver


Open in browser:

http://127.0.0.1:8000/

👥 Team Members

T R VISMAYA

LIYA JOJO

MERIN XAVIER

NANDANA K S

📜 License

This project is for educational purposes.
If reused, please provide proper credit to the contributors.


📌 Future Enhancements

Add more sign gestures

Integrate Indian Sign Language dataset

Real-time camera gesture recognition

Mobile application version


⭐ Contributions Welcome

Fork this repository and submit pull requests to improve features, UI, animations, or language support.


🌐 Project Status

🟢 Active development
