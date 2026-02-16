# 🎓 Student Portal Dashboard

A responsive, frontend-only web application that simulates a university student portal. This project demonstrates **User Authentication**, **Session Management**, and **DOM Manipulation** using pure JavaScript without a backend server.

## 🚀 Live Demo
*(If you host this on GitHub Pages or Vercel, put the link here. Otherwise, you can remove this line.)*

## ✨ Features

* **User Authentication:**
    * **Register:** specific users can create an account (stored locally).
    * **Login:** Validates credentials against stored data.
    * **Error Handling:** Displays error messages for incorrect passwords or empty fields.
* **Persistent Session:**
    * Uses `localStorage` to keep the user logged in even if the page is refreshed or the browser is closed.
* **Dynamic Dashboard:**
    * The "Login" screen automatically hides, and the "Dashboard" appears upon successful login.
    * Features a responsive grid layout for portal apps (Attendance, Fees, Timetable).
* **Interactive UI:**
    * **Navigation Bar:** Includes a dynamic menu that appears only when logged in.
    * **Profile Menu:** A toggleable dropdown menu for user details and logout.

## 🛠️ Technologies Used

* **HTML5:** Structure and semantic layout.
* **CSS3:** Flexbox & Grid for layout, custom hover effects, and responsive design.
* **JavaScript (Vanilla):** Logic for authentication, DOM manipulation, and state management.
