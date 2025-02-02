# Hospital Chat App

A real-time chat application for hospitals built using **Node.js, Express, and Stream Chat API**. This app enables secure user authentication and real-time messaging, with user data stored in **MongoDB**.

## Features
- **User Authentication** (Signup & Login)
- **Real-Time Messaging** using **Stream Chat API**
- **Secure Password Hashing** with **bcrypt**
- **MongoDB Database Integration**
- **Environment Variable Support** using **dotenv**

## Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication & Chat:** Stream Chat API
- **Security:** bcrypt for password hashing

## Installation

### 1. Clone the Repository
```sh
git clone https://github.com/harsh-791/Hospital_Chat_App.git
cd Hospital_Chat_App
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Setup Environment Variables
Create a `.env` file in the root directory and add:
```sh
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
STREAM_APP_ID=your_stream_app_id
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4. Start the Server
```sh
npm start
```

The server will run on `http://localhost:5000`.

## API Endpoints

### 1. **User Signup**
**Endpoint:** `POST /api/auth/signup`

**Request Body:**
```json
{
  "fullName": "John Doe",
  "username": "johndoe",
  "password": "securepassword",
  "phoneNumber": "1234567890"
}
```

**Response:**
```json
{
  "token": "jwt_token",
  "fullName": "John Doe",
  "username": "johndoe",
  "userId": "generated_user_id",
  "phoneNumber": "1234567890"
}
```

### 2. **User Login**
**Endpoint:** `POST /api/auth/login`

**Request Body:**
```json
{
  "username": "johndoe",
  "password": "securepassword"
}
```

**Response:**
```json
{
  "token": "jwt_token",
  "fullName": "John Doe",
  "username": "johndoe",
  "userId": "generated_user_id"
}
```

## Future Enhancements
- **Frontend Integration** using React or Vue.js
- **One-on-One & Group Chat Support**
- **File Uploads & Media Sharing**
- **Notification System**

## Author
Developed by **Harsh Verma**.

