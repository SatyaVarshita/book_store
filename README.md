Documentation link:
https://drive.google.com/drive/folders/1bWJo2ZzNJ2qaCQu9p0JS7FO6Xm1vLy3Y?usp=drive_link

# 📚 Book Store MERN Project

This is a full-stack Book Store application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).

## 📁 Project Structure
book-store-mern-project/
├── backend/ # Express + MongoDB server
│ ├── node_modules/
│ ├── .env # Environment variables (NOT committed)
│ ├── package.json
├── frontend/ # React frontend
│ ├── node_modules/
│ ├── .env.local # Frontend env vars (NOT committed)
│ ├── package.json
├── .gitignore
├── README.md

## 🚀 Features

- 🔐 User Authentication (Login/Register)
- 📚 Book listing and management
- 🛒 Shopping cart system
- 🧠 React with Hooks and Routing
- 📡 RESTful API with Express
- 🗄️ MongoDB for database
- 📦 Environment-specific configuration

- ## 🔧 Installation (Local Development)

### 1. Clone the Repository

```bash
git clone https://github.com/SatyaVarshita/book_store.git
cd book_store

. Install Backend Dependencies
bash
Copy
Edit
cd backend
npm install

Create Backend .env File
Create a file named .env inside the backend/ folder:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

DO NOT COMMIT .env to GitHub

4. Install Frontend Dependencies
bash
Copy
Edit
cd ../frontend
npm install

. Create Frontend .env.local File
Inside frontend/, create a .env.local file:

env
Copy
Edit
REACT_APP_API_URL=http://localhost:5000/api
❗DO NOT COMMIT .env.local to GitHub

. Run the Application
Start the backend:

bash
Copy
Edit
cd backend
npm run dev

Start the frontend:

bash
Copy
Edit
cd frontend
npm start:dev
Make sure your .gitignore includes:

bash
Copy
Edit
node_modules/
.env
.env.local
 In order to execute you should crete .env and .env.local file in this format
# .env.example

# MongoDB connection string
DB_URL=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority&appName=Cluster0

# JWT Secret Key for signing tokens
JWT_SECRET_KEY=your_jwt_secret_key_here

# .env.local.example

# Firebase Configuration (used by Vite/React)
VITE_FIREBASE_API_KEY=your_firebase_api_key_here
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id_here
VITE_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id


