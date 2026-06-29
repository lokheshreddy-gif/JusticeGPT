# ⚖️ JusticeGPT

JusticeGPT is an AI-powered legal assistant that helps users understand legal concepts, obtain preliminary legal guidance, and interact with an intelligent chatbot through both text and voice. The application provides a secure, responsive, and user-friendly interface while maintaining chat history for future reference.

## 🚀 Features

- 🤖 AI-powered legal question answering
- 🎙️ Voice input for hands-free interaction
- 💬 Real-time chatbot interface
- 🔒 Secure user authentication and chat history
- 📜 Persistent conversation storage using MongoDB
- 🔗 REST API integration for AI responses
- 📱 Responsive and modern UI
- ⚡ Fast and intuitive user experience

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### APIs & Tools
- REST APIs
- Web Speech API (Voice Input)
- Git & GitHub

## 🏗️ System Architecture

```
User
   │
   ▼
React Frontend
   │
   ▼
Node.js + Express Server
   │
   ├──────────► AI API
   │
   ▼
MongoDB Database
```

## 📂 Project Structure

```
JusticeGPT/
│
├── client/                 # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                 # Node.js Backend
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── package.json
│
├── README.md
└── .gitignore
```

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/JusticeGPT.git
cd JusticeGPT
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../server
npm install
```

### Configure Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

AI_API_KEY=your_api_key
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
cd ../client
npm start
```

The application will run at:

```
Frontend : http://localhost:3000
Backend  : http://localhost:5000
```

## 📸 Screenshots

Add screenshots here.

```
Home Page

Chat Interface

Voice Input

Chat History
```

## 🔐 Security Features

- User authentication
- Protected API routes
- Secure chat history storage
- Environment variable protection
- Input validation

## 📈 Future Enhancements

- Multi-language legal assistance
- Document upload and legal analysis
- PDF generation for legal summaries
- Voice response from AI
- Citation of legal acts and sections
- Case recommendation system

## 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Full Stack Web Development
- REST API Integration
- React State Management
- Node.js & Express Development
- MongoDB Database Design
- Voice Recognition Integration
- Secure Authentication
- AI-powered Application Development

## 👨‍💻 Author

**Mallela Lokesh Reddy**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

⭐ If you found this project useful, consider giving it a star!
