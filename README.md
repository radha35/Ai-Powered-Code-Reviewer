# Ai-Powered Code Reviewer | MERN Stack & AI Integration

**AI-Powered Code Reviewer** web application built using **MERN stack** (MongoDB, Express, React, Node.js) and integrated with AI APIs (OpenAI / Google AI).  
It allows users to submit code snippets and receive intelligent suggestions to improve code quality, readability, and performance.

---

## 📜 Features
- 💻 Submit code in multiple programming languages for review  
- 🤖 Get AI-generated suggestions and improvements  
- 🪙 Credit-based system to limit API usage (optional for future)  
- 🌐 Responsive and clean UI built with React  

---

## 🛠 Tech Stack
**Frontend:** React, Tailwind CSS  
**Backend:** Node.js, Express.js   
**AI Integration:** OpenAI / Google AI API  
**Version Control:** Git, GitHub  

---

## 📂 Folder Structure
```
Ai-Powered-Code-Reviewer/
│
├── client/ # React frontend
│ ├── src/
│ └── package.json
├── BackEnd/ # Node.js backend
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ ├── package.json
│ └── .env # Contains API keys (ignored in Git)
├── .gitignore
└── README.md
```
---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/radha35/Ai-Powered-Code-Reviewer.git
cd Ai-Powered-Code-Reviewer
```

---

### 2️⃣ Install Dependencies
```bash
# Backend
cd BackEnd
npm install


# Frontend
cd Frontend
npm install

```
---

### 3️⃣ Set up Environment Variables
Create a .env file inside BackEnd/

Add your API keys and configuration:
```bash
GOOGLE_GEMINI_KEY=your_new_api_key
```
---

### 4️⃣ Run the Application
```bash
Copy code
# Backend
cd ../BackEnd
npm start

# Frontend
cd ../Frontend
npm start
5️⃣ Access the App
Frontend: http://localhost:3000

Backend API: http://localhost:5000
```
---

### ⚙ How It Works
User submits a code snippet via the frontend
Backend sends code to the AI API for analysis
AI returns suggestions to improve code quality and readability
Suggestions are displayed on frontend in real-time

---

### 👨‍💻 Contributing
Fork the repo
Open issues for bugs or feature requests
Submit pull requests with improvements

---
### Author: Radha
GitHub: https://github.com/radha35
