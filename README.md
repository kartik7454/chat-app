# Chat App

## Overview
Chat App is a real-time messaging application that allows users to communicate instantly with a modern, intuitive interface. Built with cutting-edge technologies for performance and scalability.

## 🌟 Features
- ✅ **Real-Time Messaging:** Instant message delivery using WebSockets and Socket.IO
- ✅ **User Authentication:** Secure login with NextAuth integration
- ✅ **Friend Management:** Add and manage contacts easily
- ✅ **Direct Messaging:** Private one-on-one conversations
- ✅ **Live Notifications:** Get real-time message alerts
- ✅ **Responsive UI:** Beautiful design with Tailwind CSS
- ✅ **Fast Database:** Redis for high-speed data access

## 🛠️ Tech Stack

### Frontend
- **Next.js 14.2.3** - React framework for production
- **React 18** - UI library
- **Tailwind CSS** - Utility-first CSS framework
- **TypeScript** - Type-safe development

### Backend
- **Node.js** - Runtime environment
- **Express** - Web framework
- **NextAuth** - Authentication solution
- **Pusher** - Real-time communication

### Database & Caching
- **Redis** - In-memory data store for sessions and messages
- **Upstash Redis** - Managed Redis provider

### Deployment
- **Vercel** - Frontend hosting and deployment

### Other Libraries
- **Zod** - Schema validation
- **React Hook Form** - Form management
- **Lucide React** - Icon library
- **Date-fns** - Date utilities
- **Axios** - HTTP client

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/kartik7454/chat_app.git
   cd chat_app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env.local` file in the root directory:
   ```
   NEXTAUTH_SECRET=your_secret_key
   NEXTAUTH_URL=http://localhost:3000
   REDIS_URL=your_redis_url
   PUSHER_APP_ID=your_pusher_id
   PUSHER_KEY=your_pusher_key
   PUSHER_SECRET=your_pusher_secret
   PUSHER_CLUSTER=your_cluster
   ```

4. **Run development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   Navigate to `http://localhost:3000`

## 🚀 Usage

1. **Sign Up** - Create a new account with email and password
2. **Add Friends** - Search and add friends to your contact list
3. **Start Chat** - Open a conversation with a friend
4. **Send Messages** - Type and send messages in real-time
5. **Receive Notifications** - Get notified when you receive new messages

## 📁 Project Structure
```
chat_app/
├── app/                 # Next.js app directory
├── components/          # React components
├── lib/                 # Utility functions
├── public/              # Static assets
├── styles/              # Global styles
├── .env.local           # Environment variables (not in repo)
├── package.json         # Dependencies
└── README.md            # This file
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 📝 Dependencies Overview

| Package | Version | Purpose |
|---------|---------|---------|
| next | 14.2.3 | React framework |
| react | 18 | UI library |
| socket.io-client | - | Real-time communication |
| next-auth | 4.24.7 | Authentication |
| @upstash/redis | 1.31.3 | Redis client |
| tailwindcss | 3.4.3 | CSS framework |
| zod | 3.23.8 | Schema validation |
| typescript | 5 | Type safety |

## 🌐 Live Demo
Visit the live application: [https://friendzone-youtube-six.vercel.app](https://friendzone-youtube-six.vercel.app)

## 🐛 Known Issues
- None at the moment

## 💡 Future Enhancements
- Group chat support
- Voice and video calling
- Message search functionality
- User profile customization
- Message encryption
- File sharing

## 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author
**Kartik** - [GitHub Profile](https://github.com/kartik7454)

## 🙏 Acknowledgments
- Thanks to all contributors and the open-source community
- Inspired by modern chat applications
- Special thanks to the developers of Next.js, Socket.IO, and Redis

## 📞 Support
For support, email your concerns or open an issue on GitHub.

---

Made with ❤️ by Kartik