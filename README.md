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

## 🖥️ How It Works

### 1. Latest News Search

- Enter a keyword (e.g. _"AI technology"_)
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

## 🌗

# 📰 Automated News Search Tool

A lightweight, modern web utility designed to streamline news gathering. This tool allows users to search for the latest news across the web using specific keywords and optional date ranges, leveraging Google's advanced search operators automatically.

## ✨ Features

- **Smart Search:** Automatically redirects to Google News with pre-configured parameters
- **Chronological Sorting:** Results are forced to sort by "Newest" using the sbd:1 parameter.
- **Date Range Filtering:** Advanced filtering allows you to specify "From" and "To" dates for historical research.
- **Dark Mode Support:** A sleek, eye-friendly interface that remembers your preference.
- **Keyboard Shortcuts:**
  - `Enter`: Execute search.
  - `Escape`: Reset the form.
- **Responsive Design:** Fully functional on desktops, tablets, and mobile devices.

## 📁 Project Structure

```bash
/automated-google-news-search
├── index.html
└── README.md
```

This project is fully contained in a single HTML file.

## 🚀 How to Use

1. **Clone or Download:** Save the `index.html` file to your local machine.
2. **Open:** Double-click the file to open it in any modern web browser.
3. **Search:**

- Enter a **Keyword** (e.g., "Quantum Computing").
- _(Optional)_ Click the **Date Range Filter** to set specific time constraints.
- Click **Open News** or press `Enter`.

4. **Results:** A new tab will open directly to the filtered news results.

## 🔍 How it Works (Under the Hood)

The tool constructs a specific Google Search URL using parameters that are often hidden or difficult to type manually:

- `q=`: Your encoded search keyword.
- `tbm=nws`: Sets the search mode to **News**.
- `tbs=sbd:1`: Sorts the results by **date** rather than relevance.
- `tbs=cdr:1,cd_min:MM/DD/YYYY,cd_max:MM/DD/YYYY`: Applies the **Custom Date Range**.

## 📸 Preview

[!TIP]
The interface uses a card-based design with a glassmorphism-inspired background. The "Dark Mode" toggle uses `localStorage` to ensure your settings persist even after you close the browser.

## 📜 License

This project is open-source and free to use for personal or educational purposes.

---

Made with ❤️ for fast news research
