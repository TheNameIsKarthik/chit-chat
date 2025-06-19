# 🌍 Chit-Chat - Language Exchange Platform

A modern, full-stack language exchange application that connects language learners worldwide through real-time chat and video calls. Built with the MERN stack and powered by Stream Chat for seamless communication.

![Chit-Chat Demo](https://img.shields.io/badge/Status-Live-brightgreen)
![React](https://img.shields.io/badge/React-18.2.0-blue)
![Node.js](https://img.shields.io/badge/Node.js-Express-brightgreen)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-blue)
![Stream Chat](https://img.shields.io/badge/Stream-Chat-orange)
![Deployed on Render](https://img.shields.io/badge/Deployed%20on-Render-blue)

## 🚀 Live Demo

**🌐 [Visit Chit-Chat Live](https://chit-chat-p3g9.onrender.com/)**

Experience the full application with real-time chat and video calling features!

## ✨ Features

### 🔐 Authentication & User Management
- **Secure Authentication**: JWT-based authentication with HTTP-only cookies
- **User Registration & Login**: Complete signup/login flow with validation
- **Profile Onboarding**: Multi-step onboarding process for language preferences
- **User Profiles**: Rich user profiles with language preferences, bio, and location

### 👥 Social Features
- **Friend System**: Send and accept friend requests
- **User Discovery**: AI-powered recommendations for language exchange partners
- **Friend Management**: View friends, pending requests, and outgoing requests
- **Profile Cards**: Beautiful user cards with language flags and location info

### 💬 Real-Time Communication
- **Instant Messaging**: Real-time chat powered by Stream Chat
- **Message Threading**: Support for threaded conversations
- **File Sharing**: Share images and files in conversations
- **Message History**: Persistent chat history across sessions

### 📹 Video Calling
- **HD Video Calls**: Crystal clear video calls using Stream Video
- **Call Controls**: Mute, camera toggle, and screen sharing
- **Call Invitations**: Send video call links through chat
- **Responsive Design**: Optimized for desktop and mobile devices

### 🎨 User Experience
- **Dark/Light Themes**: 32 beautiful themes with DaisyUI
- **Responsive Design**: Mobile-first design that works on all devices
- **Loading States**: Smooth loading animations and skeleton screens
- **Toast Notifications**: User-friendly notifications for all actions
- **Error Handling**: Graceful error handling with user feedback

### 🔧 Technical Features
- **Monorepo Structure**: Organized frontend and backend in single repository
- **API-First Design**: RESTful API with proper error handling
- **Database Design**: MongoDB with Mongoose ODM
- **State Management**: React Query for server state, Zustand for client state
- **Type Safety**: Modern JavaScript with proper error handling

## 🚀 Tech Stack

### Frontend
- **React 18.2.0** - Modern React with hooks and functional components
- **Vite** - Fast build tool and development server
- **React Router** - Client-side routing
- **React Query** - Server state management and caching
- **Zustand** - Lightweight state management
- **Tailwind CSS** - Utility-first CSS framework
- **DaisyUI** - Component library with 32 themes
- **Stream Chat React** - Real-time chat components
- **Stream Video React SDK** - Video calling functionality
- **Lucide React** - Beautiful icons
- **React Hot Toast** - Toast notifications

### Backend
- **Node.js** - JavaScript runtime
- **Express.js 4.18.3** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - JSON Web Tokens for authentication
- **bcryptjs** - Password hashing
- **cookie-parser** - Cookie parsing middleware
- **CORS** - Cross-origin resource sharing
- **Stream Chat** - Real-time chat backend
- **dotenv** - Environment variable management

### Infrastructure
- **MongoDB Atlas** - Cloud database
- **Stream Chat** - Real-time messaging infrastructure
- **Stream Video** - Video calling infrastructure

## 📁 Project Structure

```
chit-chat/
├── frontend/                 # React frontend application
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/           # Page components
│   │   ├── hooks/           # Custom React hooks
│   │   ├── lib/             # Utility functions and API
│   │   ├── store/           # State management
│   │   ├── constants/       # Application constants
│   │   └── App.jsx          # Main application component
│   ├── public/              # Static assets
│   └── dist/                # Production build
├── backend/                 # Node.js backend application
│   ├── src/
│   │   ├── controllers/     # Route controllers
│   │   ├── models/          # Database models
│   │   ├── routes/          # API routes
│   │   ├── middleware/      # Custom middleware
│   │   ├── lib/             # Utility functions
│   │   └── server.js        # Express server
│   └── .env                 # Environment variables
└── package.json             # Root package.json
```

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (v18 or higher)
- MongoDB Atlas account
- Stream Chat account

### 1. Clone the Repository
```bash
git clone https://github.com/TheNameIsKarthik/chit-chat.git
cd chit-chat
```

### 2. Install Dependencies
```bash
npm run build
```

### 3. Environment Setup

#### Backend Environment Variables
Create a `.env` file in the `backend/` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET_KEY=your_jwt_secret_key
STREAM_API_KEY=your_stream_chat_api_key
STREAM_API_SECRET=your_stream_chat_api_secret
NODE_ENV=production
```

#### Frontend Environment Variables
Create a `.env` file in the `frontend/` directory:

```env
VITE_STREAM_API_KEY=your_stream_chat_api_key
```

### 4. Start the Application
```bash
npm start
```

The application will be available at `http://localhost:5000`

## 🔧 Development

### Development Mode
```bash
# Start backend in development mode
cd backend && npm run dev

# Start frontend in development mode (in another terminal)
cd frontend && npm run dev
```

### Available Scripts
- `npm run build` - Install dependencies and build frontend
- `npm start` - Start production server
- `npm run dev:backend` - Start backend in development mode
- `npm run dev:frontend` - Start frontend in development mode

## 📱 Features in Detail

### Authentication Flow
1. **Signup**: Users create accounts with email, password, and full name
2. **Login**: Secure authentication with JWT tokens
3. **Onboarding**: Multi-step profile setup with language preferences
4. **Profile Management**: Update bio, location, and language preferences

### Friend System
1. **User Discovery**: Browse recommended language exchange partners
2. **Friend Requests**: Send and accept friend requests
3. **Friend Management**: View friends list and manage connections
4. **Notifications**: Real-time friend request notifications

### Chat System
1. **Real-time Messaging**: Instant message delivery with Stream Chat
2. **Message Threading**: Reply to specific messages
3. **File Sharing**: Share images and documents
4. **Message History**: Persistent chat history
5. **Online Status**: See when friends are online

### Video Calling
1. **HD Video Calls**: High-quality video calls with Stream Video
2. **Call Controls**: Mute, camera toggle, screen sharing
3. **Call Invitations**: Send video call links through chat
4. **Responsive Design**: Works on desktop and mobile

## 🎨 Theming System

The application includes 32 beautiful themes powered by DaisyUI:
- Light, Dark, Cupcake, Forest, Bumblebee
- Emerald, Corporate, Synthwave, Retro, Cyberpunk
- Valentine, Halloween, Garden, Aqua, Lofi
- Pastel, Fantasy, Wireframe, Black, Luxury
- Dracula, CMYK, Autumn, Business, Acid
- Lemonade, Night, Coffee, Winter, Dim
- Nord, Sunset

Users can switch themes dynamically from the theme selector.

## 🌐 API Endpoints

### Authentication
- `POST /api/auth/signup` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout
- `GET /api/auth/me` - Get current user
- `POST /api/auth/onboarding` - Complete user onboarding

### Users
- `GET /api/users` - Get recommended users
- `GET /api/users/friends` - Get user's friends
- `POST /api/users/friend-request/:id` - Send friend request
- `PUT /api/users/friend-request/:id/accept` - Accept friend request
- `GET /api/users/friend-requests` - Get friend requests
- `GET /api/users/outgoing-friend-requests` - Get outgoing requests

### Chat
- `GET /api/chat/token` - Get Stream Chat token

## 🔒 Security Features

- **JWT Authentication**: Secure token-based authentication
- **Password Hashing**: bcrypt for password security
- **HTTP-only Cookies**: Secure cookie storage
- **CORS Protection**: Cross-origin request protection
- **Input Validation**: Server-side validation for all inputs
- **Error Handling**: Secure error responses

## 🚀 Deployment

### Production Build
```bash
npm run build
npm start
```

### Deployment Platform
This application is deployed on **Render** - a modern cloud platform that offers seamless deployment for full-stack applications.

**Deployment URL**: [https://chit-chat-p3g9.onrender.com/](https://chit-chat-p3g9.onrender.com/)

### Environment Variables for Production
Make sure to set all required environment variables in your production environment:
- `PORT` - Server port
- `MONGO_URI` - MongoDB connection string
- `JWT_SECRET_KEY` - JWT secret key
- `STREAM_API_KEY` - Stream Chat API key
- `STREAM_API_SECRET` - Stream Chat API secret
- `NODE_ENV` - Set to "production"

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 👨‍💻 Author

**Karthik**
- 🌐 **Live Demo**: [Chit-Chat](https://chit-chat-p3g9.onrender.com/)
- 📧 **Email**: [thenameiskarthik@pm.me](mailto:thenameiskarthik@pm.me)
- 💼 **LinkedIn**: [@thenameiskarthik](https://www.linkedin.com/in/thenameiskarthik)
- 🐙 **GitHub**: [@TheNameIsKarthik](https://github.com/TheNameIsKarthik)

## 🙏 Acknowledgments

- [Stream Chat](https://getstream.io/chat/) for real-time messaging
- [Stream Video](https://getstream.io/video/) for video calling
- [DaisyUI](https://daisyui.com/) for beautiful components
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [React Query](https://tanstack.com/query) for state management

## 📞 Support

If you have any questions or need help, please open an issue on GitHub or contact the author.

---

⭐ **Star this repository if you found it helpful!** 