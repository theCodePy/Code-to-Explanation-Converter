# 🌟 Code-to-Explanation Converter

An AI-powered, single-page web application (SPA) designed to act as an interactive computer science tutor. By leveraging Large Language Models (LLMs), this tool parses programming syntax and generates structured, human-readable, step-by-step explanations for complex code snippets.

### 🎓 Academic Information
* **Institution:** Brainware University
* **Department:** Cyber Science and Technology
* **Developer:** Anuska Kar
* **Supervised by:** Mr. Samudranil Maity, Assistant Professor

---

## ✨ Features
* **100% Client-Side Execution:** Built entirely with HTML, CSS, and Vanilla JavaScript. No backend server is required.
* **Intelligent Code Analysis:** Powered by the Google Gemini 2.5 Flash model.
* **Secure API Handling:** Users input their own API key, which is saved locally in the browser (`localStorage`) and never transmitted to third-party servers.
* **Modern "Cute Hacker" UI:** Features a dark glassmorphism design, neon pink/purple accents, typewriter animations, and custom markdown formatting for the AI's output.

---

## 🚀 Getting Started

Since this utility runs entirely in the browser, there is no installation required.

1. Clone this repository or download the source code.
2. Ensure `index.html` and `brainwarelogo.png` are in the same directory.
3. Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge).

---

## 🔑 How to Generate a Google Gemini API Key

This application requires a free Google AI API key to function. Follow these steps to generate yours securely:

1. Go to [Google AI Studio](https://aistudio.google.com/).
2. **Sign In** with your Google account.
3. In the left-hand navigation menu, click on **Get API key**.
4. Click the **Create API key** button. (If prompted, create it inside a "New project").
5. A long string of characters will be generated. **Copy this key.**
6. *Security Warning:* Never share this key publicly or hardcode it into public GitHub repositories. 

---

## 💻 Usage Instructions

1. Launch the application by opening `index.html`.
2. In the **Settings and Input** panel, paste your generated Gemini API Key into the designated password field. *(The app will securely remember it for your next session).*
3. Paste any C, C++, Python, or Java code snippet into the code editor area.
4. Click the **Analyze and Explain** button.
5. The AI will identify the language, point out complex syntax (like pointers), and provide a step-by-step logic breakdown in the right panel.

---
*Developed as part of the Basic AI Tools & Applications curriculum requirements.*