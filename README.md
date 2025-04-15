# CareConnect - Medical Chat Application

CareConnect is a real-time medical chat application designed to facilitate seamless communication between healthcare professionals. Built with modern web technologies, it enables secure messaging, group channels, and efficient team collaboration in a medical context.

![CareConnect Interface](https://drive.google.com/file/d/1-PgPgfwjZxu_uTAQFIJk0iXuIrB-8NCA/view?usp=sharing)

## 🌟 Features

- **Real-time Messaging**

  - Instant message delivery
  - Read receipts
  - Typing indicators
  - Emoji reactions
  - File sharing

- **User Management**

  - Secure authentication
  - Professional profiles
  - Role-based access control
  - User presence indicators

- **Channel Management**

  - Create specialized medical channels
  - Direct messaging
  - Group conversations
  - Channel search and filtering

- **Modern UI/UX**
  - Clean, medical-themed interface
  - Responsive design
  - Intuitive navigation
  - Dark/Light mode support

## 🛠️ Tech Stack

- **Frontend**

  - React.js
  - Stream Chat React SDK
  - CSS3 for styling
  - Responsive design principles

- **Backend**
  - Node.js
  - Express.js
  - MongoDB for data persistence
  - Stream Chat API for real-time functionality

## 📦 Installation

### Prerequisites

- Node.js (v14 or higher)
- npm/yarn
- MongoDB
- Stream Chat API credentials

### Setup Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/harsh-791/CareConnect.git
   cd CareConnect
   ```

2. **Install dependencies**

   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. **Environment Configuration**

   Create `.env` file in the server directory:

   ```env
   PORT=5000
   MONGODB_URL=your_mongodb_url
   STREAM_API_KEY=your_stream_api_key
   STREAM_API_SECRET=your_stream_api_secret
   ```

   Create `.env` file in the client directory:

   ```env
   REACT_APP_STREAM_API_KEY=your_stream_api_key
   ```

4. **Start the application**

   ```bash
   # Start server (from server directory)
   npm start

   # Start client (from client directory)
   npm start
   ```

   The application will be available at `http://localhost:3000`

## 🚀 Usage

1. **Authentication**

   - Sign up with professional credentials
   - Log in to access the platform

2. **Channel Creation**

   - Create new channels for different departments/teams
   - Add relevant members to channels

3. **Messaging**

   - Send real-time messages
   - Share files and images
   - React to messages with emojis
   - Create group conversations

4. **Profile Management**
   - Update professional details
   - Manage notification preferences
   - Set availability status

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Harsh Verma**

- GitHub: [@harsh-791](https://github.com/harsh-791)

## 🙏 Acknowledgments

- Stream Chat API for real-time messaging capabilities
- MongoDB for database management
- React.js community for excellent documentation and support
