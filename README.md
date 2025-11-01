

# 🧠 AI Article Summarizer – Chrome Extension

### ✨ Overview

**AI Article Summarizer** is a Chrome Extension that allows you to **summarize any article or webpage instantly** into **three different formats**:

1. 🟢 **Bullet Points** – Get quick key takeaways.
2. 🟡 **Brief Summary** – A concise overview in a few sentences.
3. 🔵 **Detailed Summary** – A deeper, paragraph-level explanation of the full article.

This extension is powered by the **Gemini API** from Google, ensuring **accurate**, **context-aware**, and **human-like summaries**.

---

## 🚀 Features

* 🔹 Summarize any web article with one click.
* 🔹 Three summary modes: *Bullet Points, Brief, Detailed.*
* 🔹 Clean, minimal popup UI.
* 🔹 Fast and reliable using Gemini AI.
* 🔹 Works on almost any article or blog page.

---

## 🧩 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Chrome APIs:** ` `scripting`, `activeTab`, `storage`
* **Backend/AI:** Gemini API (Google Generative AI)

---

## 🛠️ Installation

### 1. Clone the repository

bash
git clone https://github.com/<your-username>/ai-article-summarizer.git
cd ai-article-summarizer


### 2. Add your Gemini API Key

Create a file named .env or directly replace the placeholder in your popup.js or background.js with your Gemini API key:

js
const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY_HERE";


> ⚠️ **Note:** Never expose your API key publicly. Use environment variables or secure storage if possible.

### 3. Load the extension in Chrome

1. Open **chrome://extensions/**
2. Turn on **Developer Mode** (top-right corner)
3. Click **Load unpacked**
4. Select your project folder

---

## 🧠 How It Works

1. Open any article or webpage.
2. Click on the **AI Summary for Articles** icon in the Chrome toolbar.
3. Choose your preferred summary type:

   * **Bullet Points**
   * **Brief Summary**
   * **Detailed Summary**
4. The Gemini API processes the content and displays the result in the popup.



## 📁 Project Structure


ai-article-summarizer/
│
├── manifest.json
├── popup.html
├── popup.js
├── popup.css
├── icon.png
└── README.md


## 🧩 Future Improvements

* 🗣️ Voice summary output (text-to-speech).
* 📋 Copy summary button.
* 🌙 Dark mode UI.
* 🌐 Multi-language support.
* 🧠 Custom summary length slider.


## 📜 License

This project is licensed under the **MIT License** — you’re free to use, modify, and distribute it.

![Extension Screenshot](screenshot.png)


## 💡 Author

**👨‍💻 Tanmay Bhadauria**




