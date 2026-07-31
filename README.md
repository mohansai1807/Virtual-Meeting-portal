# 🎥 Virtual Meeting Portal

A full-stack real-time video conferencing web application that enables users to create, join, and manage virtual meetings securely. The platform provides authentication, instant meeting creation, screen sharing, chat, and a responsive user interface for seamless online collaboration.

---

## 🚀 Features

- 🔐 Secure User Authentication
- 🎥 High-Quality Video & Audio Calls
- 📅 Create and Join Meetings using Meeting ID
- 💬 Real-Time Chat During Meetings
- 🖥️ Screen Sharing
- 🎤 Mute / Unmute Microphone
- 📷 Turn Camera On / Off
- 👥 Multiple Participant Support
- 📱 Responsive Design
- ⚡ Real-Time Communication using WebRTC & Socket.io

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript
- Tailwind CSS / Bootstrap (if applicable)

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Real-Time Communication
- WebRTC
- Socket.io

### Authentication
- JWT Authentication
- bcrypt.js

---

## 📂 Project Structure

```
Virtual-Meeting-Portal/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── socket/
│   └── server.js
│
├── package.json
├── README.md
└── .env
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/mohansai1807/Virtual-Meeting-portal.git
```

### Navigate to the project

```bash
cd Virtual-Meeting-portal
```

### Install dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the **server** directory.

```env
PORT=5000

MONGO_URI=Your_MongoDB_URI

JWT_SECRET=Your_JWT_Secret

CLIENT_URL=http://localhost:3000
```

If your project uses additional APIs (such as TURN/STUN servers), add them here as required.

---

## ▶️ Running the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

The application will run on:

Frontend

```
http://localhost:3000
```

Backend

```
http://localhost:5000
```

---

## 📸 Screenshots

Add screenshots here.

```
screenshots/
├── home.png
├── login.png
├── dashboard.png
├── meeting-room.png
```

Example:

```markdown
![Home](screenshots/home.png)
```

---

## 🎯 Future Improvements

- Meeting Recording
- Meeting Scheduling
- Calendar Integration
- Live Captions
- AI Meeting Summary
- Virtual Backgrounds
- File Sharing
- Waiting Room
- Host Controls
- Meeting Analytics

---

## 🤝 Contributing

Contributions are always welcome.

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

**Mohan Sai**

GitHub:
https://github.com/mohansai1807

LinkedIn:
(Add your LinkedIn profile)

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

It motivates further development and helps others discover the project.

---

## 📬 Contact

For suggestions or feedback, feel free to connect through GitHub or LinkedIn.
