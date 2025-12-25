# 📊 Learner Data Processor — SBA2

**Course Project** • JavaScript Fundamentals

This project processes learner assignment data using **core JavaScript concepts**, including objects, arrays, functions, conditionals, and error handling. The goal was to calculate assignment scores and overall averages while handling edge cases such as late submissions and invalid data.

---

## 🧠 About the Project

This application simulates how a learning platform might calculate student performance.

It:
- Validates course and assignment data
- Processes multiple learner submissions
- Applies late penalties when applicable
- Calculates per-assignment percentages
- Computes an overall average score per learner

The logic is written in **vanilla JavaScript** and runs in the browser console.

---

## 💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML** | Loads and runs the JavaScript file |
| **JavaScript (ES6)** | Data processing, validation, and calculations |

---

## 📁 Project Structure

|——index.html - Loads the JavaScript logic
|——index.js - Core data processing logic
|——README.md - Project documentation


---

## ⚙️ How It Works

1. Course, assignment group, and learner submission data are defined as objects and arrays.
2. The `getLearnerData()` function:
   - Confirms assignments belong to the correct course
   - Skips assignments that are not yet due
   - Applies a 10% late penalty when applicable
   - Calculates percentage scores per assignment
   - Computes an overall average score per learner
3. The final result is logged to the browser console as an array of learner objects.

---

## ▶️ How to Run

1. Open `index.html` in any web browser
2. Open the browser’s **Developer Tools**
3. View the output in the **Console**

No installation or build tools required.

---

## 🧩 Learning Outcomes

Through this project, I practiced:

✔ Working with complex objects and arrays  
✔ Writing reusable functions  
✔ Implementing conditional logic  
✔ Handling errors with `try/catch`  
✔ Performing data validation  
✔ Calculating derived values from datasets  

---

## 📌 Notes

This project was completed as part of **Software Bootcamp Assignment 2 (SBA2)** and focuses on JavaScript logic rather than UI or styling.

---

## ✨ Author

**TeMecha Griffin (MsGem0523)**  
Aspiring Software Engineer | Backend-Focused Developer
