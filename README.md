# ⚖️ Quantity Measurement App — Frontend

A vanilla HTML/CSS/JS frontend for the Quantity Measurement App backend. Features a dark/light theme toggle, JWT authentication, and a clean dashboard for performing quantity measurement operations.

---

## 🌐 Live Demo

| Service | URL |
|---------|-----|
| 🖥️ Frontend | [quantity-measurementapp.netlify.app](https://quantity-measurementapp.netlify.app) |
| ⚙️ Backend API | [quantitymeasurementapp-production-369b.up.railway.app](https://quantitymeasurementapp-production-369b.up.railway.app) |

---

## 🚀 Tech Stack

![HTML5](https://img.shields.io/badge/HTML-5-orange?style=flat-square)
![CSS3](https://img.shields.io/badge/CSS-3-blue?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-ES9-yellow?style=flat-square)

---

## ✨ Features

- 🔐 **Email + Password** login and registration
- 🌐 **Google OAuth2** login
- 📊 **Dashboard** with all measurement operations
- 📋 **Operation history** table
- 🔄 **JWT token** management
- 📱 **Responsive** design with Flexbox and Grid

---

## 📁 Project Structure

```
QuantityMeasurementFrontend/
│
├── index.html              ← Login/Register page
├── app.html                ← Main app after login
├── signup.html             ← signup page

```

---

## 📖 Pages

### `index.html` — Auth Page
- Login with Email/Password
- Register with Email/Password
- Login with Google
- Dark/Light theme toggle
- Smooth tab switching between login and register

### `app.html` — Main App
- Navbar with user info + logout + theme toggle
- **Compare** — check if two quantities are equal
- **Add** — add two quantities
- **Subtract** — subtract one quantity from another
- **Divide** — divide one quantity by another
- **Convert** — convert between units
- **History** table showing recent operations

---

## 📐 Supported Units

| Category | Units |
|----------|-------|
| Length | `FEET`, `INCH`, `YARDS`, `CENTIMETER` |
| Weight | `KILOGRAM`, `GRAM`, `POUND` |
| Volume | `LITRE`, `MILLILITRE`, `GALLON` |
| Temperature | `CELSIUS`, `FAHRENHEIT` |

---

## ⚙️ Running the App

### Prerequisites
- Backend running at `http://localhost:8080`
- Any modern browser

### Steps
```bash
# Clone the repo
git clone https://github.com/MehakVarshney/QuantityMeasurementApp-Frontend.git

# Open index.html in browser
# OR use Live Server extension in VS Code
```

> ⚠️ Make sure your Spring Boot backend is running before opening the frontend!

---

## 🔗 Backend Repo

👉 [QuantityMeasurementApp](https://github.com/MehakVarshney/QuantityMeasurementApp)

---

## 🧠 Key Concepts Used

- DOM Manipulation
- Event Handling
- Fetch API / AJAX
- Promises & Async/Await
- JWT token in localStorage
- CSS Variables for theming
- Flexbox & Grid layout
- Responsive design with media queries
- ES9 features

---

## 👨‍💻 Author

**Mehak Varshney**