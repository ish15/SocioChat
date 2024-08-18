
# SocioChat

![Screenshot (138)](https://github.com/user-attachments/assets/71d66132-052f-4fe3-b449-1b0aaef2a44d)

![Screenshot (139)](https://github.com/user-attachments/assets/0e33b3ec-2d2e-464f-97f3-1f423f1980a9)

![Screenshot (137)](https://github.com/user-attachments/assets/df59233b-d0b6-40be-bcab-eebb20ba02dd)

![Screenshot (140)](https://github.com/user-attachments/assets/0e155fbd-53a0-40ce-adda-2a7b861bc076)



A chatting application built using the MERN stack, featuring real-time messaging, online statuses, typing indicators, notifications, and more with Socket.io.

# ✨ Features
- **User Authentication:** Secure login and registration.
- **Search Users:** Easily find and chat with other users.
- **Group Chats:** Create and manage group chats.
  - Only group admins can edit group details and manage members.
  - Users can leave group chats if uninterested.
- **Real-time Chatting:** Instant messaging with Socket.io.
- **Online/Offline Status:** See when users are online or offline in private chats.
- **Typing Indicators:** Real-time typing status in both private and group chats.
- **Notifications:** Receive real-time chat notifications for private and group chats.
- **Responsive Design:** Optimized for all screen sizes.
- **WhatsApp-like UI:** Familiar interface similar to WhatsApp Web/Desktop.

## 🙄 TODO
- **Message Deletion:** Allow users to delete messages.
- **Group Deletion:** Enable group admins to delete group chats.

## ⚙ Tools and Technologies
### Frontend
- React.js
- Chakra UI
- React Icons

### Backend
- Node.js
- Express.js
- MongoDB
- JWT
- Socket.io
- Cloudinary
- Bcrypt.js

## 🛠 Installation and Setup

### Clone the Repository
```bash
git clone <repository_url>
```

### Install Server Dependencies
```bash
npm install
```

### Install Client Dependencies
```bash
cd client
npm install
```

### Environment Variables
Create a `.env` file in the root directory and add the following:

```plaintext
PORT=5000
DB_URI=<mongodb_uri>
JWT_SECRET=<your_jwt_secret>
JWT_EXPIRE=5d
COOKIE_EXPIRE=5
NODE_ENV=development
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloudname>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
FRONTEND_URL=http://localhost:3000
```

### Start the Servers

#### Express Server
```bash
npm start
```

#### React Development Server
```bash
cd client
npm start
```

## 🏎 Creating Production Build

### Build the React App
```bash
cd client
npm run build
```

### Update Environment Variables for Production
```plaintext
NODE_ENV=production
```

---
