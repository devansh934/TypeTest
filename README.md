# TypeTest ⚡
> A sleek, high-performance typing speed test for modern developers.

**TypeTest** is a minimalist web application designed to help users measure their typing speed (WPM), accuracy, and consistency. Built with a focus on a "dark mode" aesthetic and real-time performance tracking.



## 🚀 Live Demo
Check out the live app here: [https://devansh934.github.io/TypeTest/](https://devansh934.github.io/TypeTest/)

## ✨ Features
- **Real-time Stats:** Track WPM, Accuracy, and Character count as you type.
- **Visual Feedback:** Instant character highlighting (Green for correct, Red for mistakes).
- **Standardized Scoring:** Uses the industry-standard WPM formula: `(Characters / 5) / Time`.
- **Progress Tracking:** Dynamic progress bar and timer countdown.
- **Responsive UI:** Fully optimized for desktop, tablet, and mobile screens.
- **Anti-Cheat:** Paste protection enabled to ensure genuine typing results.

## 📊 The Math Behind the Stats
The application calculates speed using the professional Net WPM formula to ensure accuracy is taken into account:



- **Gross WPM:** `(Total Characters / 5) / Time (min)`
- **Net WPM:** `Gross WPM - (Errors / Time (min))`

## 🛠️ Built With
- **HTML5:** Semantic structure for better accessibility.
- **CSS3:** Custom properties (CSS variables) for the Deep Indigo & Cyber Lime theme.
- **JavaScript (ES6):** Real-time event listeners and DOM manipulation.
- **FontAwesome:** Professional iconography for the dashboard.

## 📂 Project Structure
```text
├── index.html   # Main structure and UI components
├── style.css    # Modern dark-mode styling and animations
├── script.js    # Core logic, WPM calculations, and state management
└── README.md    # Project documentation
⚙️ How to Run Locally
Clone the repository:

Bash

git clone [https://github.com/devansh934/TypeTest.git](https://github.com/devansh934/TypeTest.git)
Navigate to the folder:

Bash

cd TypeTest
Open index.html in any browser.

👤 Author
Devansh

GitHub: @devansh934

If you liked this project, feel free to give it a ⭐!


---

### 🚀 How to push this to GitHub:

1. Save the `README.md` file.
2. Run these three commands in your VS Code terminal:
   ```bash
   git add README.md
   git commit -m "Finalized professional README"
   git push
