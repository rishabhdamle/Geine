<h1 align="center">🤖 Geine – A Custom Chatbot (AI Agent)</h1>

<p align="center">
  <b>Geine</b> is a custom AI-powered chatbot agent built with <a href="https://www.langchain.com/langgraph">LangGraph</a> in JavaScript.  
  It can chat naturally, browse the internet for real-time information, and remember conversations across sessions.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-43853d?style=for-the-badge&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript&logoColor=black"/>
</p>

---

## ✨ Features

- 💬 **Chat with the Agent** – Natural, human-like conversations
- 🌐 **Web Browsing** – Fetch live data from the internet
- 🧠 **Memory** – Remembers conversations (short-term + long-term)
- 🔄 **Context-Aware Responses** – Maintains context across multiple turns
- 🛠 **Customizable Tools** – Extend with APIs (weather, finance, etc.)
- 📂 **Multi-Session Support** – Separate memory per user
- ⚡ **Fast & Scalable** – Optimized with LangGraph

---

## 🛠 Tech Stack

| Layer        | Technology                                                          |
| ------------ | ------------------------------------------------------------------- |
| **Core**     | [LangGraph](https://github.com/langchain-ai/langgraph) (JavaScript) |
| **Models**   | OpenAI GPT • Anthropic Claude • Local LLMs                          |
| **Browsing** | Puppeteer • Playwright • LangChain Tools                            |
| **Memory**   | LangGraph Memory • Redis • Vector DB (Pinecone, Weaviate, Chroma)   |
| **Backend**  | Node.js + Express / TypeScript + Express                            |
| **Database** | MongoDB • PostgreSQL                                                |
| **Deploy**   | Vercel • Railway • Docker                                           |

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/rishabhdamle/Geine.git
cd Geine

# 2. Install dependencies
npm install

3. Set environment variables

Create a .env file:
OPENAI_API_KEY=your_openai_api_key
BROWSER_API_KEY=your_browser_api_key
DB_URI=your_database_uri

4. Run the app
npm run dev

📂 Project Structure
geine-chatbot/
│── src/
│   ├── agents/    # AI agent logic
│   ├── memory/    # Conversation memory
│   ├── tools/     # Browsing & external APIs
│   ├── routes/    # API endpoints
│   └── index.js   # Entry point
│── package.json
│── README.md

🧑‍💻 Future Enhancements

🎙 Voice Interaction (speech-to-text & text-to-speech)

🖼 Image Understanding (multimodal support)

🔌 Plugin Ecosystem (3rd-party integrations)

📱 React / Next.js frontend for chat

🤝 Contributing

Contributions are welcome!
Open an issue or submit a pull request to collaborate.

📜 License

Licensed under the MIT License – free to use & modify.

```
