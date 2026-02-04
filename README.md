# Automated Google News Search

A simple, modern web-based tool to search and open the latest news from **Google News** automatically.  
This project allows users to search news by keyword or within a specific date range, with support for **Light/Dark Mode** and keyboard shortcuts.

## ✨ Features

- 🔍 Search the **latest Google News** by keyword
- 📅 Search news within a **custom date range**
- 🌙 Light & Dark mode toggle (saved in localStorage)
- ⌨️ Press **Enter** to submit searches
- 🎨 Clean, responsive UI with modern styling
- 🚀 No backend required — pure HTML, CSS, and JavaScript

## 📁 Project Structure
```bash
/automated-google-news-search
├── index.html
└── README.md
```

This project is fully contained in a single HTML file.

## 🖥️ How It Works

### 1. Latest News Search
- Enter a keyword (e.g. *"AI technology"*)
- Click **"Open Latest News"**
- The app opens Google News results sorted by **most recent**

Google search parameter used:
```text
tbm=nws&tbs=sbd:1
```

### 2. Date Range News Search
- Enter a keyword
- Select **start date** and **end date**
- Click **"Open News by Date Range"**
- Google News opens filtered by the selected dates

Google search parameter used:
```text
tbs=cdr:1,cd_min:MM/DD/YYYY,cd_max:MM/DD/YYYY,sbd:1
```

## ⌨️ Keyboard Support

- Press **Enter** while typing:
  - Keyword field → latest news search
  - Date range fields → date range search

## 🌗 Theme Mode

- Click **🌙 Dark Mode / ☀️ Light Mode**
- Theme preference is saved using `localStorage`
- Automatically restored on page reload

## 🛠️ Technologies Used

- HTML5
- CSS3 (CSS Variables + Grid Layout)
- Vanilla JavaScript
- Google Fonts (Inter)
- Google Search / Google News

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in any modern browser
3. Start searching for news instantly

No installation, build tools, or dependencies required.

## 📌 Notes

- This project uses **Google Search URLs**, not the Google News API
- Results depend on Google’s current search behavior
- Best used for quick manual research and news monitoring

## 📄 License

Free to use for personal or educational purposes.

---

Made with ❤️ for fast news research
