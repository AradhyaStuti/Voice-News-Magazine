# 📰 Voice News Magazine

### Live Breaking News Web App with Voice Search & Text-to-Speech

A modern, responsive **real-time news web application** powered by the **GNews API**, featuring:

* 🔴 Live breaking news ticker
* 🎤 Voice-based search (Speech Recognition)
* 🔊 Automatic headline narration (Text-to-Speech)
* 📂 Category filtering
* 📄 Pagination
* 🔄 Auto-refresh updates

Built using **HTML5, Tailwind CSS, and Vanilla JavaScript**.

---

## ✨ Key Features

### 🔴 Breaking News Ticker

* Displays the top 5 headlines in an animated scrolling ticker.
* Clickable headlines open full articles in a new tab.

### 🎤 Voice Search (Web Speech API)

* Click the **Speak** button.
* Say a keyword like *“sports news”*.
* The app fetches related headlines instantly.

### 🔊 Automatic Text-to-Speech

* Top 5 headlines are read aloud automatically.
* Enhances accessibility and user engagement.

### 🔍 Smart Search & Filtering

* Search by keyword.
* Filter by category:

  * General (Current Affairs)
  * Sports
  * Technology
  * Business
  * Entertainment
  * Health
  * Science

### 📄 Pagination Support

* Navigate through multiple pages of news results.
* Smooth content refresh without reloading the page.

### 🔄 Auto Refresh

* Automatically refreshes content every 5 minutes to keep news updated.

### 📱 Fully Responsive

* Mobile-friendly layout.
* Grid-based adaptive card design.

---

## 🛠️ Tech Stack

| Technology          | Purpose                     |
| ------------------- | --------------------------- |
| HTML5               | Structure                   |
| Tailwind CSS        | Styling & Responsive Design |
| JavaScript (ES6)    | Application Logic           |
| Web Speech API      | Voice Recognition           |
| SpeechSynthesis API | Text-to-Speech              |
| GNews API           | Live News Data              |

---

## 🔑 API Configuration

This project uses the **GNews API**.

### 1️⃣ Get a Free API Key

Sign up at:
👉 [https://gnews.io](https://gnews.io)

### 2️⃣ Replace API Key

Inside `index.html`, update:

```javascript
const apiKey = "YOUR_API_KEY";
```

---

## 📂 Project Structure

```
voice-news-magazine/
│
├── index.html
└── README.md
```

---

## ⚙️ Installation & Usage

### Option 1: Run Locally

1. Download or clone the repository:

   ```bash
   git clone https://github.com/your-username/voice-news-magazine.git
   ```

2. Open `index.html` in your browser.

No build tools required ✅
No frameworks required ✅

---

## 🧠 How It Works

1. On page load → Fetches general headlines.
2. Top 5 articles:

   * Added to the ticker.
   * Read aloud automatically.
3. User interactions:

   * Keyword search
   * Category filter
   * Voice search
   * Pagination navigation
4. Content refreshes every 5 minutes.

---

## 📸 UI Highlights

* Animated breaking ticker
* Smooth hover card effects
* Pulse highlight for top article
* Clean Tailwind-based layout
* Accessible voice-enabled interaction

---

## 🌍 Browser Compatibility

| Browser | Support                       |
| ------- | ----------------------------- |
| Chrome  | ✅ Full Support (Recommended)  |
| Edge    | ✅ Supported                   |
| Firefox | ⚠️ Limited Speech API Support |
| Safari  | ⚠️ Partial Support            |

> Voice Recognition works best in Chromium-based browsers.

---


## 🔮 Future Enhancements

* 🌙 Dark Mode Toggle
* 🌍 Multi-language News Support
* 🔖 Bookmark & Save Articles
* 📰 Source Filtering
* ⚡ Loading Skeleton Animations
* 🔐 Secure API key handling via backend proxy

---

## 📌 Why This Project?

This project demonstrates:

* API Integration
* Real-time Data Handling
* Voice Interface Integration
* Modern UI Design Principles
* Responsive Web Development
* Accessibility-focused features

Ideal for:

* Portfolio projects
* Internship showcases
* Frontend practice
* API-based app demonstrations

---

## 📄 License

This project is open-source and available for educational and personal use.

---

## 👩‍💻 Author

Developed with modern web technologies and API integration best practices.

