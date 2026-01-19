#ELEVATE

---

```md
# 🚀 ELEVATE™ — Pay-to-Win Elevator Game with AI Strategy

ELEVATE™ is a competitive sealed-bid elevator simulation game where players must bid to gain priority.
Both sides pay their bids, but only the higher bidder benefits.

An AI opponent analyzes player behavior, predicts future actions, and adapts its strategy over time.
The result is a strategic game that feels tense, readable, and human-like.

---

## 🎮 Gameplay Overview

- Player and AI place sealed bids every round
- Both sides pay their bids (all-pay auction)
- The higher bidder scores and sends a passenger down the elevator
- Maintenance fees increase over time
- Running out of money can end the game early

The objective is not to win every round, but to win the entire game.

---

## 🧠 Why the AI Is Smart

- Considers future maintenance costs, not just the current round
- Predicts a range of player bids instead of a single value
- Chooses between saving, baiting, or aggressive spiking
- Can intentionally lose a round to preserve money
- Exposes its reasoning to the player for transparency

> “The AI doesn’t try to win every round — it tries to win the game.”

---

## 🛠 Built With

### Languages
- JavaScript (ES Modules)
- HTML5
- CSS3

### Frontend
- Vanilla JavaScript
- HTML Canvas
- CSS Grid & Flexbox
- Custom CSS animations

### Backend
- Node.js
- Native HTTP server
- RESTful JSON API

### AI System
- LangChain (`@langchain/langgraph`)
- OpenAI GPT model (`gpt-4o-mini`)
- Zod for output validation

### Dev Tools
- npm
- dotenv
- nodemon

---

## 🧩 Architecture

```

Frontend (HTML/CSS/JS)
↓
REST API (Node.js)
↓
Game Engine
↓
AI Decision Pipeline (LangChain + GPT)

```

---

## 📂 Project Structure

```

.
├── public/
│   ├── index.html
│   ├── styles.css
│   ├── app.js
│   └── assets/
├── server/
│   ├── server.mjs
│   ├── game_core.mjs
│   ├── agent_pipeline.mjs
│   └── .env.example
├── package.json
└── README.md

````

---

## ▶️ Getting Started

### Install dependencies
```bash
npm install
````

### Set environment variables

```env
OPENAI_API_KEY=your_api_key_here
```

### Run the server

```bash
npm run start
```

Server runs at:

```
http://localhost:3000
```

---

## 🎯 Design Philosophy

* State-driven simulation
* Interpretable AI reasoning
* Fair but unforgiving mechanics
* Satirical take on pay-to-win systems

---

## 👥 Team

Built by a team of four for a hackathon project.

---

## 📜 License

MIT License
