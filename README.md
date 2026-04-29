# 🚀 Web Dev Typing Game

An interactive, browser-based typing application designed to enhance typing speed while reinforcing essential web development concepts. Built with a focus on real-time feedback and clean performance.

[**🌐 Launch Live Demo**](https://webdev-typing-practice.netlify.app/)

---

## ✨ Key Features
- **Educational Content:** Practice typing using curated snippets about HTML, CSS, JavaScript, and modern best practices.
- **Dynamic Timer:** Customizable session durations (30s, 1m, 2m, 3m) to challenge users of all levels.
- **Real-time Feedback:** Visual character highlighting (correct/incorrect) as you type for immediate accuracy tracking.
- **Advanced Metrics:** Automatic calculation of WPM (Words Per Minute) and Accuracy % upon completion.
- **Developer UI:** Modern dark theme with a monospace font for a professional coding aesthetic.
- **Navigation Control:** Smooth transitions between game states with Restart and Home screen options.

---

## 🛠️ Technologies Used
- **Frontend:** HTML5 (Semantic Structure)
- **Styling:** CSS3 (Custom dropdowns, transitions, and responsive layout)
- **Logic:** Vanilla JavaScript (ES6+ for game state, timer management, and scoring logic)

---

## 🎮 How to Play
### 1. **Select Duration:** Choose your preferred timer from the home screen dropdown.

### 2. **Type to Start:** The timer triggers automatically on your first keypress.

### 3. **Analyze:** Check your white/red highlighting to track your accuracy in real-time.

### 4. **Evaluate:** View your final WPM and Accuracy score once the timer reaches zero.

## 🚀 Local Installation
### 1. **Clone the repository:**
   git clone https://github.com/HanNiKyawZin/Typing-practice.git

### 2. **Navigate & Run:** Open index.html directly in your web browser or use a Live Server extension.

---

## ⚙️ Core Logic Overview
- **Scoring Algorithm:** * WPM = (Correct Characters / 5) / Minutes
- Accuracy = (Correct Characters / Total Typed) * 100

- **Real-time DOM Manipulation:** Uses dynamic class toggling for character highlighting to ensure zero-latency feedback.

- **Randomized Content:** Paragraphs are procedurally selected from a curated array in script.js.

---

## 📁 File Structure
├── **index.html**       # Application entry point & UI structure
├── **style.css**        # Responsive styling & dark theme definitions
└── **script.js**        # Core game engine & scoring logic

---

## 📜 License & Credits
- **License:** MIT License. Free for educational and personal use.
- **Source:** Developed as a practical demonstration of Vanilla JavaScript DOM manipulation.

---

- **Developer Note:** This project is part of my technical portfolio for internship applications, focusing on logic-driven JavaScript development.
