# 🎨 ShortBit Frontend

This is the **React.js frontend** of the ShortBit URL Shortener. It provides a clean, responsive user interface for shortening URLs, managing links, and user authentication.

## 🔗 Live Demo

🌐 [https://incomparable-liger-aadad9.netlify.app](https://incomparable-liger-aadad9.netlify.app)

---

## 🚀 Features

- 🔐 User Authentication (SignUp / Login)
- 🔗 Create and manage short links
- 📊 View and track your URLs
- 🎨 Styled using Tailwind CSS
- 🌍 Integrated with Spring Boot backend
- 🔁 Protected routes with JWT auth
- ✨ Clean, modern UI/UX

---

## 🛠️ Tech Stack

- React.js (Hooks + Context API)
- React Router DOM
- Axios (API Calls)
- TailwindCSS
- JWT for frontend auth
- Netlify (deployment)

---

## 📁 Project Structure
```bash
frontend/
├── public/
├── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # Pages like Home, Login, Dashboard
│ ├── context/ # Auth and global context
│ ├── App.jsx
│ └── main.jsx
├── tailwind.config.js
├── index.html
└── package.json
```


---

## 📦 Installation & Run
```bash
cd frontend
npm install
npm run dev
```
---

## axios.js
```bash
axios.defaults.baseURL = "https://shortbit-sb.onrender.com/api";
```
---
🙋‍♂️ Author
Ashish Kumar
GitHub: @ashishkumar-17

---

## 🧪 Environment Setup
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/shortbit
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
jwt.secret=your_jwt_secret_key
```



