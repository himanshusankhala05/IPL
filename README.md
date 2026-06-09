# 🏏 IPL Auction Simulation System

A web-based **IPL Auction Simulation System** that allows users to experience a realistic Indian Premier League player auction. This application provides a platform for bidding on players, managing team compositions, tracking budgets, and visualizing auction results in real-time.

---

## 🚀 Features

* **Interactive Bidding System:** Intuitive and user-friendly interface to browse available players and place live bids.
* **Dynamic Team Management:** Real-time tracking of team rosters, player counts, and remaining purse/budget restrictions.
* **Real-Time Simulation Updates:** Instant UI refreshes reflecting updated bids and ownership changes.
* **Robust Backend Logic:** Powered by Flask to securely process bidding rules, budget validations, and data persistence.
* **Responsive Frontend:** Optimized using modern HTML, CSS, and JavaScript for a seamless desktop or mobile experience.

---

## 🛠️ Technologies Used

### Frontend
* **HTML5:** Semantic structure of the web layout.
* **CSS3:** Custom styles, responsive design, and cricketing themes.
* **JavaScript (ES6):** Dynamic DOM updates, event handling, and real-time frontend calculations.

### Backend & Database
* **Flask:** Light-weight Python framework managing server-side routing and business logic.
* **SQLite / Flask-SQLAlchemy:** Lightweight relational database management and Object-Relational Mapping (ORM).

### Libraries & Extensions
* **Flask-WTF:** Secure and structured form handling for placing bids.
* **Bootstrap (Optional):** For rapid, responsive grid layouts.

---

## 📁 Project Folder Structure

```plaintext
ipl-auction/
│
├── app.py                 # Main application entry point & Flask configuration
├── models.py              # Database schemas (Players, Teams, Users)
├── forms.py               # Form validation logic (Bidding & User inputs)
│
├── static/                # Static assets
│   ├── css/
│   │   └── style.css      # Core application stylesheets
│   └── js/
│       └── main.js        # Script handling frontend interactivity
│
├── templates/             # HTML Templates
│   ├── base.html          # Main boilerplate layout
│   ├── index.html         # Auction dashboard / Live bidding page
│   ├── teams.html         # Team management & roster viewer
│   └── summary.html       # Final auction results sheet
│
├── instance/
│   └── auction.db         # Local SQLite Database file
│
├── requirements.txt       # Project dependencies and libraries
└── README.md              # Project documentation
