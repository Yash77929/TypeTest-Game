# ⌨️ Typing Test Game

A fun and interactive **Typing Test Game** designed to help improve your typing speed and accuracy.  
Built using optimized data structures and algorithms for real-time feedback and performance.

---

## 🚀 Features

- **Random Word Generation** – Uses a queue-based system to cycle through dynamic word lists efficiently.
- **Timer Functionality** – Implements a stopwatch algorithm to track session duration.
- **Real-Time Input Validation** – Instantly compares typed characters with the target word.
- **WPM Scoring System** – Calculates Words Per Minute (WPM) with precision.


---

## 🛠️ Built With

- **Languages:** JavaScript / Python / Java  
- **Data Structures:** Queue (for word generation)  
- **Algorithms:** Stopwatch logic, string comparison  

---

## 🧠 How It Works

### 🔤 Word Queue System

Words are loaded into a queue to cycle through without repetition and ensure quick access.

### ⏲️ Timer

The timer starts when typing begins and ends after a set time (e.g., 60 seconds) using a stopwatch mechanism.

### ✅ Input Validation

Every keystroke is validated against the target word, providing real-time feedback.

### 🧾 Scoring Formula

```txt
WPM = (Correctly Typed Words / Time in Minutes)
