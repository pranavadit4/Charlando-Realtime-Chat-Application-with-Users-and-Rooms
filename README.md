
# 🌐 Charlando – Real-Time Chat Application  

Charlando is a **real-time, room-based chat application** built using **Node.js**, **Express.js**, and **Socket.IO**.  
It allows multiple users to join chatrooms, exchange messages instantly, and view active users in real-time.  

---

## 🚀 Features  
- 🔹 **Real-Time Messaging** – Instant communication via WebSockets using Socket.IO  
- 🔹 **Room-Based Chats** – Users can join specific rooms for focused discussions  
- 🔹 **User Presence Tracking** – Displays a list of active users in each room  
- 🔹 **Join/Leave Notifications** – Alerts when users enter or exit a room  
- 🔹 **Responsive UI** – Works seamlessly across devices  
- 🔹 **Scalable Architecture** – Redis adapter support for multi-instance deployments  

---

## 🛠 Tech Stack  

**Backend:**  
- Node.js  
- Express.js  
- Socket.IO  
- Moment.js (for timestamps)  
- Redis Adapter (`@socket.io/redis-adapter`) *(optional for scaling)*  
- dotenv (for environment variables)  

**Frontend:**  
- HTML, CSS, Vanilla JavaScript  
- Qs (query string parsing)  

**Development Tools:**  
- Nodemon  

---

## 📂 Project Structure  
```bash
Charlando/
│
├── public/               # Frontend HTML, CSS, and JS
├── utils/                # Helper functions (messages, user handling)
├── server.js             # Main server entry point
├── package.json          # Project metadata & dependencies
├── .env                  # Environment variables
└── README.md              # Project documentation
```

---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/charlando.git
cd charlando
```

### 2️⃣ Install dependencies  
```bash
npm install
```

### 3️⃣ Configure environment variables  
Create a `.env` file in the root directory:  
```env
PORT=3000
```

*(Optional for scaling)* Add Redis configuration:  
```env
REDIS_URL=redis://127.0.0.1:6379
```

### 4️⃣ Start the application  
**Development mode:**  
```bash
npm run dev
```

**Production mode:**  
```bash
npm start
```

---

## 📸 Screenshots  


---

## 🤝 Contributing  
1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-name`)  
5. Open a Pull Request  

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## 💡 Future Enhancements  
- User authentication  
- Private messaging  
- File sharing  
- Emojis and reactions  
