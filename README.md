# 🌍 CodeAlpha – LinguaAI Pro

**LinguaAI Pro** is a premium AI-powered translation web application built with **HTML, CSS, and JavaScript** that integrates the **Microsoft Translator API** to deliver fast, accurate, and reliable translations. With support for **130+ languages**, real-time auto-detection, confidence scoring, and a modern UI, LinguaAI Pro ensures a professional-grade translation experience.  

This project was created as part of the **CodeAlpha AI Internship** to demonstrate **API integration, UI/UX design, and practical AI usage in web development**.  

---

## 📑 Table of Contents
1. [Features](#-features)  
2. [Tech Stack](#-tech-stack)  
3. [Installation & Setup](#-installation--setup)  
4. [API Key Configuration](#-api-key-configuration)  
5. [Usage Guide](#-usage-guide)   
6. [Folder Structure](#-folder-structure)  
7. [Security Notes](#-security-notes)  
8. [Contributing](#-contributing)  
9. [License](#-license)  
10. [Acknowledgments](#-acknowledgments)  

---

## 🚀 Features
- ⚡ **Lightning Fast Translations** – Powered by Microsoft Cognitive Services.  
- 🎯 **High Accuracy** – Neural Machine Translation ensures contextual precision.  
- 🌐 **130+ Languages** – Extensive support for global and regional dialects.  
- 🤖 **Auto Language Detection** – Automatically identifies the source language.  
- 📊 **Confidence Score** – Provides trust levels for translation results.  
- 📝 **Word Counter** – Tracks input size (up to 10,000 characters).  
- 🔄 **Language Swap** – Switch source and target languages instantly.  
- 🖥️ **Modern & Responsive UI** – Animated background, gradient styles, ripple button effects.  
- 📋 **Copy to Clipboard** – Quickly copy translated text.  
- 🧹 **Clear All** – Reset input and output in one click.  
- 🔐 **Secure API Handling** – API key stored only in session memory.  

---

## 🛠 Tech Stack
- **Frontend:**  
  - HTML5  
  - CSS3 (Gradients, Animations, Responsive Design)  
  - JavaScript (Vanilla ES6 Classes)  

- **Backend/Services:**  
  - Microsoft Translator API (Azure Cognitive Services)  

- **UI/Assets:**  
  - [Font Awesome](https://fontawesome.com/)  
  - [Google Fonts – Inter](https://fonts.google.com/specimen/Inter)  

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Fardeen37/CodeAlpha_LinguaAI-Pro.git
````

### 2️⃣ Open Project

Navigate into the folder and open the main HTML file:

```bash
cd CodeAlpha_LinguaAI-Pro
```

Then double-click `LinguaAI Pro.html` or open it in your browser.

### 3️⃣ Get Microsoft Translator API Key

* Sign in to [Azure Portal](https://portal.azure.com).
* Create a **Translator resource** under Cognitive Services.
* Copy your **API Key** and **Region**.

---

## 🔑 API Key Configuration

* On the web app, enter your API key in the **API Key field**.
* The app will automatically validate and connect.
* ✅ Green status = Connected successfully.
* ❌ Red status = Invalid or missing key.

> ⚠️ For production environments: **Never expose API keys in frontend code.** Use a backend proxy server for security.

---

## 📖 Usage Guide

1. Enter your **Microsoft Translator API Key**.
2. Choose **Source Language** (or select *Auto Detect*).
3. Select a **Target Language**.
4. Type or paste text into the **Source Text** box.
5. Click **Translate** (or press `Ctrl+Enter`).
6. View translated text along with confidence score and detected language.
7. Copy or clear results using available action buttons.

---

## 📂 Folder Structure

```
CodeAlpha_LinguaAI-Pro/
│
├── LinguaAI Pro.html                     # Main application file
├── README.md                             # Documentation
```

---

## ⚠️ Security Notes

* API keys are **temporarily stored in session memory only**.
* For **production**, always configure a **backend proxy** (e.g., Node.js/Flask server) to protect API credentials.
* Avoid committing API keys into version control.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/awesome-feature`).
3. Commit your changes (`git commit -m 'Add awesome feature'`).
4. Push to the branch (`git push origin feature/awesome-feature`).
5. Create a Pull Request.

---

## 📜 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute it.

---

## 🙏 Acknowledgments

* **CodeAlpha** – For providing the internship and project opportunity.
* **Microsoft Cognitive Services** – For the translation API.
* **Font Awesome & Google Fonts** – For design assets.

---

## 👨‍💻 Author

**Data Fardeen**
📌 GitHub: [Fardeen37](https://github.com/Fardeen37)
