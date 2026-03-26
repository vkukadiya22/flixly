# Flixly - Premium Movie & Series Streaming Platform

Flixly is a modern, responsive streaming web application built with Flask and Bootstrap 5. It provides a premium viewing experience with a dark-themed interface, movie/series categorization, watchlist management, and an interactive video streaming experience.

## 🌟 Key Features

### 🎬 Interactive Content Discovery
- **Dynamic Home Page:** Featuring a hero section with auto-playing video trailers and customizable posters.
- **Categorized Sections:** Browse through "New Releases," "Top Picks," "Because you watched," and genre-specific collections like Marvel, Horror, Anime, Action, and Sci-Fi.
- **Smart Recommendations:** Personalized movie and series suggestions based on user viewing history.
- **Advanced Search:** Real-time search functionality available on both desktop and mobile devices.

### 🎥 Premium Viewing Experience
- **Interactive Details Modal:** View detailed information, cast, rating, and watch trailers before starting the full content.
- **TV Series Episodes List:** Easily navigate through different seasons and episodes with a clean, organized list.
- **Resume Watching:** Progress tracking for movies and series to continue exactly where you left off.
- **High-Quality Streaming:** Integrated video player with volume controls, mute/unmute, and responsive playback.

### 👤 User Account & Personalization
- **Account Management:** Custom sign-in and sign-up pages with error handling.
- **Personal Watchlist:** Add your favorite contents to a personalized list for easy access.
- **Profile Customization:** Choose from a variety of avatars, update your name, and manage your password.
- **Secure Authentication:** Session-based authentication to keep your data and watchlist safe.

### 📱 Fully Responsive Design
- Optimized for all screen sizes, from mobile phones to large desktop monitors.
- Mobile-friendly sidebar navigation and horizontal/vertical poster management for different screen orientations.

## 🛠️ Technology Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
- **UI Framework:** Bootstrap 5.3.2
- **Icons:** Bootstrap Icons 1.11.3
- **Templating Engine:** Jinja2
- **Styling:** Custom Vanilla CSS with glassmorphism effects and modern typography.

## 📦 Project Structure

```text
flixly/
├── app.py              # Main Flask application (Backend logic)
├── templates/          # Jinja2 HTML templates
│   ├── index.html      # Home page
│   ├── watch.html      # Video player page
│   ├── movies.html     # Movies collection
│   ├── series.html     # TV Series collection
│   ├── categories.html # Genre & category browse
│   ├── watchlist.html  # User watchlist
│   ├── signin.html     # Authentication
│   └── macros.html     # Reusable UI components
└── static/             # Static assets
    ├── css/            # Stylesheets (style.css)
    ├── js/             # Frontend logic (main.js)
    ├── images/         # Logo, default avatars, and posters
    └── videos/         # Movie/Series trailers and content
```

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/flixly.git
   cd flixly
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Database Setup:**
   The application uses a database for user accounts, watchlist, and movie data. Ensure your database is initialized:
   ```bash
   python init_db.py
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```
   Open your browser and navigate to `http://localhost:5000`.

## 🎨 UI/UX Design

Flixly follows a modern design language:
- **Dark Mode:** Deep charcoal and black backgrounds for a premium cinematic feel.
- **Glassmorphism:** Subtle transparent backgrounds for modals and dropdowns.
- **Dynamic Overlays:** Smooth hover effects and info-reveal animations on movie cards.
- **Intuitive Navigation:** Fixed navbar with easy access to all core features.

## 🤝 Contribution

Contributions are welcome! If you'd like to improve Flixly, please open a Pull Request.

---
Built with ❤️ for movie lovers.
