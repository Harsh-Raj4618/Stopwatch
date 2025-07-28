# ⏱️ Stopwatch Web App

A simple and elegant stopwatch application built using **HTML**, **CSS**, and **JavaScript**. It allows users to **start**, **stop**, and **reset** a timer with millisecond precision.

---


## 🧩 Features

- ✅ Start timer
- ⏹ Stop timer
- 🔄 Reset timer
- 📟 Displays time in minutes, seconds, and milliseconds
- 🎨 Dark-themed modern UI
- ⚡ Smooth animations and responsive layout

---

## 💡 Technologies Used

| Technology | Purpose            |
|------------|--------------------|
| HTML       | Page structure     |
| CSS        | Styling & layout   |
| JavaScript | Timer functionality|

---

## 📂 Project Structure
- main
  - html file
    - index.html
  - css file
    - style.css
  - js file
    - script.js
  - readme.md


---

## 🧠 How It Works

- The stopwatch uses `setInterval()` to update time every 1/60th of a second.
- Time is tracked in `timer` as a float and split into:
  - `minuteVal`
  - `secondVal`
  - `msVal`
- The UI is dynamically updated with padded zero values for consistency.

---

## 🛠 How to Use

1. Clone or download the repository:
   ```bash
   git clone https://github.com/Harsh-Raj4618/stopwatch.git
   cd stopwatch

