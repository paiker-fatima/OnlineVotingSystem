# OnlineVotingSystem

A secure and modular **Online Voting System** built using Django. This system allows for seamless digital voting management where an **Admin** can manage candidates, positions, vote casting, real-time results, and graphical poll representations.

---

## 🚀 Features

- 🔐 **Admin Panel**
  - Manage candidates and positions
  - View and verify voter details
  - Generate and view election results
  - Visual poll representation using charts
- 🧑‍💼 **Candidate Management**
  - Add/edit/delete candidate profiles
  - Assign positions
- 📊 **Poll Representation**
  - Real-time charts displaying votes per candidate/position
- 📥 **Secure Voting**
  - One vote per user per election
  - Authentication protected
- 📄 **Results**
  - Automatic winner declaration based on votes
  - Position-wise result display

---

## 🛠️ Tech Stack

- **Framework**: Django (Python)
- **Frontend**: HTML5, CSS3, Bootstrap
- **Database**: SQLite (default), easily switchable to PostgreSQL/MySQL
- **Visualization**: Chart.js or Django-Plotly-Dash (optional)

---

## 📁 Project Structure
online-voting-system/
│
├── account/               # Handles user authentication and profiles
├── administrator/         # Admin dashboard and management views
├── e_voting/              # Main Django project settings and configurations
├── voting/                # Voting logic (casting, tallying, etc.)
├── static/                # Static files (CSS, JS, images)
├── media/                 # Uploaded media (candidate images, etc.)
│
├── election_title.txt     # Election configuration/title
├── db.sqlite3             # SQLite database file
├── manage.py              # Django management script
├── requirements.txt       # Python dependencies
│
├── .venv/                 # Virtual environment (auto-generated)
├── venv/                  # (Duplicate or secondary virtual environment)
├── my_venv/               # (Another virtual environment, possibly backup)


