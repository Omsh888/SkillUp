# SkillUp 🎮

SkillUp is a Node.js and Express-based web application that provides user authentication (Signup/Login) using MongoDB Atlas and bcrypt. It features multiple EJS-based pages like Dashboard, Games, About, and Contact — ideal for showcasing web development skills.

---

## 🔧 Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** HTML, CSS, EJS
- **Database:** MongoDB Atlas (Mongoose)
- **Authentication:** bcrypt for password hashing
- **Environment Variables:** dotenv

---

## 🚀 Features

- User Signup with secure password hashing
- User Login using username or email
- Dashboard access after login
- Static pages: Home, Games, About, Contact
- MongoDB Atlas integration
- EJS templating engine

---

## 📁 Project Structure

```
skillup/
├── public/                  # Static assets (CSS, images, JS)
├── views/                   # EJS templates
│   ├── homePage.ejs
│   ├── login.ejs
│   ├── signup.ejs
│   ├── dashboard.ejs
│   ├── games.ejs
│   ├── about.ejs
│   └── contact.ejs
├── .env                     # Environment variables
├── package.json             # Project dependencies
└── server.js                # Main server file
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory and add:

```env
MONGODB_ATLAS_URI=your_mongodb_connection_string
PORT=3000
```

---

## 🛠️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/skillup.git
cd skillup

# Install dependencies
npm install

# Start the server
node server.js
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📌 Routes

| Method | Route        | Description                |
|--------|--------------|----------------------------|
| GET    | `/`          | Home Page                  |
| GET    | `/signup`    | Signup Form                |
| POST   | `/signup`    | Register New User          |
| GET    | `/login`     | Login Form                 |
| POST   | `/login`     | Authenticate User          |
| GET    | `/dashboard` | Logged-in User Dashboard   |
| GET    | `/games`     | Games Page                 |
| GET    | `/about`     | About Page                 |
| GET    | `/contact`   | Contact Page               |

---

## ✅ Future Improvements

- Add session-based authentication (e.g., using express-session or JWT)
- Form validation and error handling on frontend
- Store user profile images
- Add logout functionality
- Enhance UI/UX with animations and better layout

---

## 🙌 Author

**Om Sharma**  
📧 omsh888@gmail.com 