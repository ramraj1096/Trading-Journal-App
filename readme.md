# 📈 Trading Journal Pro

**Trading Journal Pro** is a full-stack web application that empowers traders—beginners and professionals alike—to log, analyze, and optimize their trading strategies. It offers AI-powered insights, performance visualizations, and a sleek user experience to help traders make smarter decisions.

---

## 🚀 Live Demo

🌐 [Live Website](https://tradingjournalpro.vercel.app/)  
📦 [GitHub Repository](https://github.com/ramraj1096/Trading-Journal-App)

---

## 🧠 Key Features

- 🔐 **Secure Auth** – JWT-based user registration & login
- 📝 **Smart Trade Logging** – Log, view, and manage trades with details like asset, strategy, entry/exit price, and results
- 📊 **Performance Analytics** – Track win rate, profit factor, and net P&L with interactive charts
- 📈 **Real-Time Asset Search** – View charts and market data via TradingView widgets
- 🧠 **AI Sentiment Analysis** – Market mood detection from news/headlines using the FinBERT model
- 📉 **AI Technical Analysis** – KNN model predicts short-term price direction
- 💡 **AI Strategy Analyzer** – Gemini-powered suggestions based on historical trade patterns
- 🌙 **Dark Mode** – Theme toggle for comfortable viewing

---

## 🛠 Tech Stack

### 🔧 Backend

- **Spring Boot** – Core APIs and user management
- **FastAPI** – AI/ML services (FinBERT, KNN)
- **MongoDB** – NoSQL database for users, trades, and insights
- **JWT** – Token-based authentication system

### 🖥 Frontend

- **React.js** – UI development
- **Tailwind CSS** & **Shadcn UI** – Responsive and clean design
- **Chart.js** – Visualize trade performance
- **TradingView Widgets** – Live charts and market data integration

### 🧠 AI/ML

- **FinBERT** – Sentiment analysis from financial news
- **K-Nearest Neighbors (KNN)** – Trend prediction model
- **Gemini API** – Strategy suggestions based on performance history

---

## 🧪 Getting Started (Local Setup)

### Prerequisites

- Node.js
- Java 17+
- Python 3.9+
- MongoDB

### Backend Setup (Spring Boot + FastAPI)

```bash
# Spring Boot
cd backend
./mvnw spring-boot:run

# FastAPI (AI Services)
cd backend-fastapi-AI-features
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm i
npm run dev

```
