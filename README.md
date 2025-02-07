# MERN Real-Time Chat App

A real-time chat application built with the **MERN stack** (MongoDB, Express.js, React, Node.js) using **Socket.io** for real-time messaging, authentication with login/logout, and **Cloudinary** for profile picture uploads. The UI is enhanced with **30+ themes** to provide a customizable experience.

## Features

- **Real-Time Chat** powered by **Socket.io**
- **User Authentication** (Login & Logout)
- **Profile Picture Upload** using **Cloudinary**
- **30+ Themes** to personalize the UI
- **Secure and Scalable Backend**
- **MongoDB Database** for storing user and message data

## Tech Stack

### Frontend:
- React.js
- Tailwind CSS / Styled Components
- Zustand / Redux for state management

### Backend:
- Node.js
- Express.js
- MongoDB & Mongoose
- Socket.io (for real-time communication)
- Cloudinary API (for image uploads)

### Other Tools & Libraries:
- JWT Authentication
- DaisyUI
- bcrypt.js (for password hashing)

## Installation

### Prerequisites:
- Node.js & npm installed
- MongoDB instance running

### Clone the Repository:
```sh
git clone https://github.com/yourusername/mern-chat-app.git
cd mern-chat-app
```

### Install Dependencies
#### Backend:
```sh
cd backend
npm install
```

#### Frontend:
```sh
cd ../frontend
npm install
```

## Configuration

1. Create a **.env** file in the backend directory and add:
```sh
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

2. Start the backend server:
```sh
cd backend
npm start
```

3. Start the frontend app:
```sh
cd frontend
npm start
```

## Usage

- **Sign up/Login** to the app
- **Upload Profile Picture** from settings
- **Start chatting** in real-time with friends
- **Switch themes** from the theme selector

## Screenshots
![image](https://github.com/user-attachments/assets/5da44b1e-7e53-4c1e-90f3-aa4c2d1a295c)



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

## License
This project is licensed under the MIT License.

---

**Author:** Mohammad Yunus Khan 
**GitHub:** https://github.com/khan1095
