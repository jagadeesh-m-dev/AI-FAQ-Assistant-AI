# AI-FAQ-Assistant-AI

 
An AI-powered FAQ and customer support automation backend built using Node.js, Express.js, MongoDB, and Google Gemini AI.

The project provides secure user authentication, FAQ management, AI-powered FAQ generation, category management, and intelligent FAQ search through REST APIs.

👥 Team Details

Team ID: SWTID-2026-7867
Team Size: 5

Team Members

- Team Leader: Jagadeesh M
- Ravi M
- SHOBIKA K
- RISHIKANTH M
- Malaidhevan S

🚀 Features

- 🔐 JWT Authentication & Authorization
- 🤖 AI-powered FAQ Generation using Google Gemini
- 🔎 FAQ Search
- 📝 FAQ CRUD Operations
- 📂 Category Management
- 🔒 Password Hashing using bcrypt
- ✅ Mongoose Schema Validation
- ⚠️ Centralized Error Handling
- 🗄️ MongoDB Database Integration
- 🌐 RESTful API Architecture

🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Google Gemini AI
- Postman / Thunder Client
- VS Code

📁 Project Structure

AI-FAQ-Assistant/
│
├── src/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── app.js
│   └── server.js
│
├── .env
├── package.json
└── README.md

⚙️ Installation

1. Clone the Repository

git clone <your-repository-url>
cd AI-FAQ-Assistant

2. Install Dependencies

npm install

The project uses Express, Mongoose, dotenv, CORS, JSON Web Token, bcrypt, and the Google GenAI package.

3. Configure Environment Variables

Create a ".env" file and add the required configuration:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key

4. Run the Server

npm run dev

🔗 Main API Endpoints

Method| Endpoint| Access
POST| "/api/auth/register"| Public
POST| "/api/auth/login"| Public
POST| "/api/faqs"| Private
GET| "/api/faqs/search?q=configure"| Public
POST| "/api/ai/generate-faq"| Private

🔐 User Roles

- Admin – Manage users, FAQs, categories, and AI-generated content.
- Content Creator – Create, update, delete personal FAQs and generate FAQs using AI.
- Authenticated User – View and search FAQs and use AI-assisted features.
- Public User – View and search published FAQs without accessing protected APIs.

🎯 Project Objective

The main objective of this project is to reduce manual FAQ management work by providing a secure backend API with AI-powered FAQ generation, search, authentication, and structured content management.

📌 Project Status

Status: In Development

---

👨‍💻 Team

SWTID-2026-7867

Jagadeesh M • Ravi M • SHOBIKA K • RISHIKANTH M • Malaidhevan
