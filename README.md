
//
echo '# Meet Video Call

## 📌 Overview
A real-time video conferencing application that allows multiple users to connect, share screens, and chat during video calls. Built with modern web technologies.

## ✨ Features
- 🎥 **Real-time Video/Audio Calling** - High-quality peer-to-peer communication
- 📱 **Screen Sharing** - Share your screen with participants
- 💬 **Chat Messaging** - Send messages during the call
- 🎤 **Mute/Unmute Controls** - Control your audio
- 📹 **Video On/Off** - Control your video stream
- 👥 **Multiple Participants** - Support for group video calls

## 🛠️ Tech Stack
| Technology | Purpose |
|------------|---------|
| React.js | Frontend framework |
| WebRTC | Peer-to-peer video/audio communication |
| Socket.io | Real-time signaling |
| Node.js + Express | Backend server |
| Material-UI | UI components |

## 📁 Project Structure
\`\`\`
MEET-video-call/
├── frontend/           # React frontend
│   ├── src/
│   │   ├── pages/      # App pages
│   │   ├── styles/     # CSS modules
│   │   └── contexts/   # React contexts
│   └── public/         # Static assets
├── backend/            # Node.js backend
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── routes/
│   └── package.json
└── .gitignore
\`\`\`

## 🚀 Installation & Setup

### Prerequisites
- Node.js installed on your system
- npm or yarn package manager

### Backend Setup
\`\`\`bash
cd backend
npm install
npm start
\`\`\`

### Frontend Setup
\`\`\`bash
cd frontend
npm install
npm start
\`\`\`

### Environment Configuration
Create an \`environment.js\` file in the frontend/src folder:
\`\`\`javascript
const server = "http://localhost:5000"; // Your backend server URL
export default server;
\`\`\`

## 📱 How to Use
1. Start both backend and frontend servers
2. Enter your username to join the lobby
3. Grant camera and microphone permissions
4. Share the meeting link with others
5. Start your video conference!

## 🔧 Key Features Explained

### WebRTC Implementation
- Uses RTCPeerConnection for peer-to-peer streaming
- STUN server for NAT traversal
- ICE candidates for network connectivity

### Socket.IO Signaling
- Room-based meeting management
- Real-time user join/leave notifications
- Chat message broadcasting

## 👨‍💻 Author
**Mohd Kaif**
- GitHub: [@Mohd-Kaif728](https://github.com/Mohd-Kaif728)

## 📝 License
This project is for educational purposes as a college project.

---
⭐ If you found this project helpful, give it a star on GitHub!
' > README.md
