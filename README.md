# 💬 HeyChat

A real-time chat application built using the MERN stack with modern UI and socket-based communication.

---

## 🚀 Features

* 🔐 User Authentication (Signup / Login)
* 💬 Real-time messaging with Socket.IO
* 🟢 Online / Offline user status
* 🖼️ Profile image upload (Cloudinary)
* 🔔 Instant message updates
* 📱 Responsive UI
* 🌐 REST API with Express

---

## 🛠️ Tech Stack

**Frontend**

* React (Vite)
* Axios
* Zustand (State Management)
* Tailwind CSS

**Backend**

* Node.js
* Express.js
* MongoDB (Atlas)
* Mongoose
* Socket.IO

**Other Tools**

* Cloudinary (Image Upload)
* JWT (Authentication)
* Cookie Parser

---

## 📂 Project Structure

```
HeyChat/
│
├── Backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   ├── lib/
│   │   └── index.js
│
├── Frontend/
│   ├── src/
│   └── index.html
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file in **Backend/** and add:

```
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## ▶️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/HeyChat.git
cd HeyChat
```

---

### 2️⃣ Install dependencies

```bash
# Backend
cd Backend
npm install

# Frontend
cd ../Frontend
npm install
```

---

### 3️⃣ Run the app

```bash
# Start backend
cd Backend
npm start

# Start frontend
cd ../Frontend
npm run dev
```

---

## 🌐 API Endpoints

### Auth Routes

* `POST /api/auth/signup`
* `POST /api/auth/login`
* `GET /api/auth/check`
* `PUT /api/auth/update-profile`

### Message Routes

* `GET /api/messages`
* `POST /api/messages/send`

---

## 🧠 Future Improvements

* 📁 File & media sharing
* 🎥 Video calling
* 🌙 Dark mode toggle
* 🔍 Search users/messages
* 📌 Message reactions

---

## 🤝 Contributing

Pull requests are welcome! Feel free to open issues for suggestions or improvements.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Saiman Rout**
