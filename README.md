#  Librarium — The Modern Reading Universe

**Librarium** is a high-performance, full-stack management ecosystem designed to bridge the gap between digital lending and e-commerce. Built with a **"Vanilla-First"** philosophy, it provides a premium SaaS experience with zero framework overhead, achieving near-instantaneous load times and granular UI control.

---

##  Key Features

### 🎭 Dual-Portal Ecosystem
*   **Member Universe:** A discovery-focused interface featuring horizontal carousels, glassmorphic book cards, and a native E-book reader.
*   **Admin SaaS Portal:** A high-density Obsidian-themed (`#0F111A`) environment for inventory management, user auditing, and real-time transaction monitoring.

### 💳 Hybrid Transaction Logic
*   **Borrow Engine:** Implements a 7-day lending cycle with an automated backend **Fine Engine** that calculates penalties ($0.50/day) for overdue books.
*   **Buy Engine:** Permanent digital acquisition model that adds titles to the user's personal collection and updates system-wide stock levels.

### ⌨️ Command+K Global Palette
*   A keyboard-centric navigation center for rapid searching across the platform.
*   Supports **Administrative Shortcuts** (e.g., typing `/add` instantly triggers the book management modal) to maximize workflow efficiency.

### 📊 High-Density Data Visualization
*   **SVG Sparklines:** Native SVG paths used to visualize 7-day revenue and user trends without external charting libraries.
*   **Circular Gauges:** Visualizes reading goals and inventory capacity using dynamic SVG stroke-animations.

---

## 🛠️ Technical Stack

*   **Backend:** Python **Flask** (RESTful API Design).
*   **Database:** Atomic **JSON-based storage** logic ensuring data integrity during concurrent write operations.
*   **Frontend:** Strictly Vanilla **HTML5, CSS3** (Custom Variables), and **ES6+ JavaScript**.
*   **Security:** Role-Based Access Control (RBAC) with **SHA-256** password hashing.
*   **Performance:** Integrated **Skeleton Shimmer Loaders** for non-blocking asynchronous data fetching.

---

## 📂 Project Structure

```text
LIBRARY-SYSTEM/
├── data/                 # Persistent JSON Storage (Atomic Writes)
│   ├── authors.json
│   ├── books.json
│   ├── transactions.json
│   └── users.json
├── static/               # Frontend Assets
│   ├── script.js         # Core UI Logic & API Handshake
│   └── style.css         # "Modern Universe" Design System
├── templates/            # HTML Structure
│   └── index.html        # Main Single-Page Interface
├── app.py                # Flask Backend & REST API Routes
├── db_init.py            # Dataset Generator (Initial Data Seed)
├── Procfile              # Deployment Instructions (Railway/Heroku)
├── requirements.txt      # Python Dependencies
└── README.md             # Project Documentation
```



## 📜 License
Developed by **Jainish Khatkar**. This project is a benchmark in Vanilla Full-Stack Engineering. All rights reserved.

