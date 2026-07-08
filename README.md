# AI-Powered Code Reviewer


The **AI-Powered Code Reviewer** is a modern, full-stack application designed to provide developers with instant, intelligent feedback on their code. By leveraging the advanced reasoning capabilities of Google's Gemini LLM, this tool analyzes code snippets for logical errors, security vulnerabilities, performance bottlenecks, and adherence to industry best practices.

## 🚀 Features

- **Instant Code Analysis:** Receive real-time, comprehensive AI-driven feedback on your code structure and logic.
- **Multi-Language Support:** Versatile analysis capabilities spanning across multiple popular programming languages.
- **Educational Insights:** Beyond simply finding bugs, the AI suggests modern alternatives and idiomatic patterns to help developers improve their skills.
- **Lightweight & Blazing Fast:** A highly responsive user interface built on the Vite and React ecosystem.
- **Secure Architecture:** A decoupled Node.js and Express.js backend securely handles all API communications and AI model interactions.

## 🛠️ Technology Stack

**Frontend:**
- React.js
- Vite
- HTML5, CSS3, JavaScript

**Backend:**
- Node.js
- Express.js

**Artificial Intelligence:**
- Google Gemini Flash (`gemini-flash-lite-latest`)

## 📁 Folder Structure

```text
AI-powered-Code-Reviewer/
├── BackEnd/                 # Node.js + Express backend
│   ├── src/
│   │   ├── controllers/     # Request handlers
│   │   ├── routes/          # API endpoint definitions
│   │   └── services/        # Gemini AI logic & configuration
│   ├── server.js            # Backend entry point
│   └── package.json
├── Frontend/                # React + Vite frontend
│   ├── public/              # Static assets
│   ├── src/                 # UI components, views, and styles
│   │   ├── App.jsx          # Main application logic
│   │   └── main.jsx         # React DOM rendering
│   ├── index.html
│   ├── package.json
│   └── vite.config.js       # Vite configuration
└── README.md
```

## 📦 Local Installation & Setup

### Prerequisites
- Node.js (v16.0 or higher)
- npm (v8.0 or higher)
- A valid [Google Gemini API Key](https://aistudio.google.com/)

### 1. Clone the Repository
```bash
git clone https://github.com/sarv-tech/AI-powered-Code-Reviewer.git
cd AI-powered-Code-Reviewer
```

### 2. Backend Setup
Navigate to the backend directory, install dependencies, and configure your environment variables.
```bash
cd BackEnd
npm install
```
Create a `.env` file in the `BackEnd` directory and add your Google Gemini API key:
```env
GOOGLE_GEMINI_KEY=your_api_key_here
PORT=3000
```
Start the backend server:
```bash
npm start
```

### 3. Frontend Setup
Open a new terminal window, navigate to the frontend directory, and install dependencies.
```bash
cd Frontend
npm install
```
*(Optional)* If you are running the backend on a different port or in a production environment, create a `.env` file in the `Frontend` directory:
```env
VITE_API_URL=http://localhost:3000
```
Start the frontend development server:
```bash
npm run dev
```

## 🌐 Deployment

This project is structured to be easily deployed to modern cloud platforms:
- **Frontend:** Designed for zero-config deployment on platforms like [Vercel](https://vercel.com/) or [Netlify](https://netlify.com/).
- **Backend:** Ready to be hosted on environments like [Render](https://render.com/), Railway, or Heroku. Ensure you configure the `GOOGLE_GEMINI_KEY` environment variable in your production environment.

## 📺 Live Demo

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Site-success?style=for-the-badge&logo=vercel)](https://ai-powered-code-reviewer-self.vercel.app/)

![AI-Powered Code Reviewer Demo](https://github.com/user-attachments/assets/0863526b-0e20-4b11-a4a1-cf1e648619e1)

## 🙏 Acknowledgments
- **Google Gemini Team** for providing the powerful Large Language Model (`gemini-flash-lite-latest`).
- **Vite and React Communities** for the outstanding frontend tooling.
- **Node.js and Express.js Communities** for the robust backend ecosystem.

---
*Developed and maintained by [Sarvesh Pingale](https://www.linkedin.com/in/sarvesh-pingale-8b9090299).*
