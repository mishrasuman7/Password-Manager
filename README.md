# 🔐 Password Manager App

A secure, responsive, and user-friendly Password Manager built with the MERN stack (MongoDB, Express.js, React, Node.js) and styled using Tailwind CSS. This app allows users to store, manage, and access their passwords safely in an encrypted database.

## 🌟 Features

- 🔐 **Secure Authentication** (JWT-based)
- 📁 **Password Storage** with Encryption (AES/Hashing)
- 🔍 **Search and Filter** saved credentials
- 🧾 **Copy-to-Clipboard** functionality
- 📱 **Responsive Design** using Tailwind CSS
- 🌙 **Dark Mode Support** 
- ✅ CRUD operations for credentials (Create, Read, Update, Delete)

---

## 🛠️ Tech Stack

| Technology | Role |
|------------|------|
| React.js   | Frontend UI |
| Tailwind CSS | Styling |
| Express.js | Backend server/API |
| MongoDB    | Database |
| Node.js    | Runtime environment |
| bcrypt / crypto-js | Encryption/Hashing |
| JWT (JSON Web Tokens) | Authentication |

---

## 📸 Screenshots

> _Include 2–3 screenshots or a demo GIF here._

---

## ⚙️ Installation

### Prerequisites

- Node.js
- MongoDB

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/password-manager.git
cd password-manager

### 2. Install Dependencies
Backend
```bash
cd backend
npm install
Frontend
```bash
cd ../frontend
npm install
### 3. Setup Environment Variables
Create a .env file in the backend directory with the following:

```env

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
4. Run the App
Backend Server
```bash

cd backend
npm start
Frontend Client
bash

cd frontend
npm start
🚧 Folder Structure
pgsql

password-manager/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── tailwind.config.js
└── README.md
📌 TODO / Future Improvements
 Add password strength meter

 Add password generator tool

 Multi-device sync

 Biometric/2FA support

 Export/import passwords

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

🙌 Acknowledgements
Tailwind CSS

MongoDB Atlas

React.js

Express.js

CryptoJS

📬 Contact
Suman Mishra  – msuman7757@gmail.com
Project Link: https://github.com/mishrasuman7/password-manager

```yaml


---

Let me know if you want to:
- Add **deployment instructions** (e.g., for Vercel, Render, or Heroku)
- Use **Docker**
- Make it for a **team project**
- Or localize it with **Nepali/other language**

I'll adjust it accordingly!
