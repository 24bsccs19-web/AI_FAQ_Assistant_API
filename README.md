# AI-FAQ-Assistant-API

🤖 Welcome to AI FAQ Assistant API 🤖

This is a Node.js and Express.js backend application that provides an AI-powered FAQ and customer support system.
It includes user authentication, FAQ management, and AI-powered answer generation using Google Gemini AI.

🌟 Features

👤 User Registration and Login with JWT authentication. 🔐 Secure password hashing using bcrypt.
📖 FAQ Management with Create, Read, Update, and Delete operations. 🤖 AI-powered answers using Google Gemini AI.
👤 User Profile retrieval for authenticated users. 🗄️ MongoDB database integration using Mongoose. 🛡️ Input validation and error handling.
📱 RESTful API design for easy integration with frontend applications.

🛠️ Tech Stack

Node.js  
Express.js  
MongoDB  
Mongoose  
Google Gemini AI  
JWT  
bcrypt  
dotenv  
CORS  
Postman  

🚀 How to Run

1. Clone this repository

git clone https://github.com/24bsccs19-web/AI_FAQ_Assistant_API.git

cd AI_FAQ_Assistant_API

2. Install dependencies

npm install

3. Create a .env file and add your MongoDB connection, JWT secret, Gemini API key, and port.

PORT=5000  
MONGODB_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  
GEMINI_API_KEY=your_gemini_api_key

4. Start the development server

npm run dev

5. Open the API in Postman or your browser at http://localhost:5000

🧪 API Testing

The project was tested using Postman with successful results for User Registration, User Login,
User Profile, FAQ Creation, FAQ Retrieval, FAQ Updating, FAQ Deletion, and AI Answer Generation.

🎥 Demo Video Link : https://drive.google.com/file/d/17ovLwNVU9F897t-4__6F994D8HChFmXS/view?usp=drivesdk

🎯 Purpose

This project is an AI-powered FAQ and customer support backend project.
The goal of this project is to provide automated answers to user questions while also allowing users to manage
frequently asked questions using RESTful APIs, MongoDB, and Google Gemini AI.
