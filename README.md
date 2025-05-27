# ⏱️ Chrome Extension for Time Tracking & Productivity Analytics

> **Project developed during internship at CodTech IT Solutions

This Chrome Extension helps users track the amount of time they spend on different websites and provides productivity insights through analytics dashboards. It runs in the background, monitors website usage in real time, and categorizes sites based on productivity.

---

## 🌟 Project Overview

Built as part of a full-stack web development internship at **CodTech IT Solutions**, this extension was designed to showcase how browser APIs and background scripts can be used to monitor user activity and provide insightful analytics for productivity tracking.

---

## 🔧 Features

- 🕒 Real-time time tracking for active tabs
- 📊 Daily/weekly analytics dashboards
- 🌐 Website categorization (e.g., productive, social, entertainment)
- 🧠 Idle time detection
- 🧩 Clean and intuitive popup UI
- 🔒 Local storage of user data (privacy-focused)

---

## 🧰 Technologies Used

- JavaScript (ES6)
- Chrome Extension APIs (Background, Content Scripts, Alarms, Storage)
- HTML5 & CSS3
- Chart.js (for analytics visualization)

---

## 📁 Folder Structure
Chrome-Extensions-for-Time-Tracking-Productivity-Analytics/
│
├── background.js # Monitors tab activity
├── content.js # Runs in active tab for tracking
├── popup.html # UI shown when clicking extension icon
├── popup.js # Logic for popup UI
├── analytics.html # Dashboard view
├── analytics.js # Handles charts and calculations
├── manifest.json # Extension configuration
├── icons/ # Extension icons
├── styles/ # CSS files
├── README.md

---

## 🧪 How It Works

1. `background.js` runs continuously and tracks tab changes and focus time.
2. When a tab is active, the extension logs the hostname and duration.
3. Activity is saved using `chrome.storage`.
4. `analytics.html` visualizes usage stats using `Chart.js`.
5. The extension distinguishes between **productive** and **non-productive** sites based on predefined categories.

---

## 🧩 How to Install Locally

1. Clone this repository:

```bash
git clone https://github.com/uknation/Chrome-Extensions-for-Time-Tracking-Productivity-Analytics.git

2. Go to chrome://extensions/ in your Chrome browser.

3. Enable Developer Mode (top right).

4. Click "Load unpacked" and select the project folder.

5. The extension will appear in your Chrome toolbar.
