<div align="center">

# 🍿 Netflix Clone Experience
**A dynamic, fully client-side streaming UI with themes, ratings, and authentication.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![LocalStorage](https://img.shields.io/badge/Local_Storage-0052CC?style=for-the-badge&logo=icloud&logoColor=white)](#)

*Experience a feature-rich UI clone featuring smart movie filtering, watchlist management, interactive modals, and localized session handling.*

<br>

[✨ Features](#-interactive-features) • 
[🚀 Quick Start](#-getting-started) • 
[🧪 Demo Account](#-demo-credentials) • 
[📂 Architecture](#-project-structure)

</div>

---

## ✨ Interactive Features

Click on the sections below to explore the robust features built into this platform!

<details open>
<summary><b>🔐 Authentication & Security</b></summary>
<br>

- **Client-Side Auth:** Secure login portal with form validation and error handling (`auth.js`).
- **Session Management:** Uses browser `localStorage` to keep users logged in across page reloads.
- **Protected Routes:** Automatically redirects unauthenticated users to the login screen.
</details>

<details>
<summary><b>🎬 Dynamic Content Engine</b></summary>
<br>

- **Smart Search:** Real-time search bar that filters movies by title and description.
- **Genre Filtering:** Dropdown filter to instantly sort movies by Action, Drama, Comedy, Thriller, etc.
- **Auto-Sliding Hero:** A dynamic featured slider that cycles through top movies every 5 seconds.
- **Categorized Grids:** Automatically sorts the movie database into *Trending*, *Top 10*, *Popular*, and *Top Rated*.
</details>

<details>
<summary><b>🎨 UI/UX & Gamification</b></summary>
<br>

- **Theme Toggle (🌙/☀️):** Seamlessly switch between Dark Mode and Light Mode with persistent user preference.
- **Interactive Modals:** Click any movie poster to open a rich modal containing metadata, descriptions, and action buttons.
- **My List / Watchlist:** Add and remove movies to a localized watchlist.
- **5-Star Rating System:** Rate your favorite movies and save your scores directly to local storage!
</details>

---

## 🎬 Current Movie Database

The platform is pre-loaded with high-octane 2024 blockbusters. 

| Poster Emoji | Movie Title | Genre | Rating |
| :---: | :--- | :--- | :---: |
| ⚖️ | **Jolly LL.B 3** | Comedy | ⭐ 8.2 |
| 🦁 | **Mahaavatar Narsimha** | Action | ⭐ 8.5 |
| 💥 | **War 2** | Action | ⭐ 8.7 |
| 🕵️ | **Hit: The Third Case** | Thriller | ⭐ 8.4 |
| 🥋 | **Karate Kid Legends** | Action | ⭐ 8.6 |
| 🎬 | **Dude** | Action | ⭐ 7.9 |

---

## 🚀 Getting Started

No database configuration or backend setup is required. The app runs entirely in your browser!

1. **Clone/Download** the repository to your local machine.
2. **Open the App:** Double-click `login.html` (or `index_3.html` which will auto-redirect you if you aren't logged in).
3. **Login:** Use the demo credentials provided below.
4. **Explore:** Browse movies, toggle the theme to Light mode, rate a movie, and add items to your Watchlist!

### 🧪 Demo Credentials

To bypass the login screen and access the main dashboard, use the built-in demo account:

- **Email:** `farhanfawad007@gmail.com`
- **Password:** `1234567`

---

## 📂 Project Structure

<details>
<summary><b>👀 Click to expand the interactive folder tree</b></summary>

```text
Netflix-Clone/
├── index_3.html               # Main streaming dashboard
├── login.html                 # Authentication page
├── README.md                  # Project documentation
│
├── css/                       # Stylesheets
│   ├── styles.css             # Global styles, grids, and components
│   ├── auth.css               # Specific styling for the login portal
│   └── theme.css              # Light/Dark mode override variables
│
└── js/                        # JavaScript Modules
    ├── app.js / main.js       # App initialization, slider, and modal logic
    ├── auth.js                # Login, logout, and session validation
    ├── movies.js              # Movie database and sorting/filtering algorithms
    ├── search.js              # Search bar event handlers
    ├── watchlist.js           # "My List" local storage management
    └── rating.js              # 5-star rating system logic
