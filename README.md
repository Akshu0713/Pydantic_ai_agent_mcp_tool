# 🤖 Pydantic AI Agent with MCP Tool

An intelligent AI Agent built using **PydanticAI** that integrates external tools through the **Model Context Protocol (MCP)**.

The project demonstrates how Large Language Models (LLMs) can securely interact with real-world tools instead of relying only on pretrained knowledge. The AI agent communicates with an MCP Server and invokes tools dynamically to answer user queries.

---

## 🚀 Features

- 🤖 AI Agent built using **PydanticAI**
- 🔗 Model Context Protocol (MCP) integration
- 🌦️ Weather MCP Tool support
- ⚡ Powered by **Groq Llama 3.3 70B Versatile**
- 🔐 Secure API key management using `.env`
- 🧩 Easily extendable with custom MCP tools
- 🚀 Asynchronous execution using Python AsyncIO
- 📦 Lightweight and production-ready architecture

---

## 🛠️ Tech Stack

- Python 3.13+
- PydanticAI
- Model Context Protocol (MCP)
- Groq API
- Python Dotenv
- AsyncIO

---

## 📂 Project Structure

```
Pydantic_AI_Agent_MCP_Tool
│
├── main.py
├── weather.py
├── .env
├── pyproject.toml
├── uv.lock
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Akshu0713/Pydantic_AI_Agent_MCP_Tool.git

cd Pydantic_AI_Agent_MCP_Tool
```

### Install Dependencies

Using **uv**

```bash
uv sync
```

or using pip

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file.

```env
GROQ_API_KEY=your_groq_api_key
```

---

## ▶️ Running the Application

```bash
python main.py
```

---

## 💬 Example

### Input

```
What is the current weather in Chennai?
```

### Output

```
The current weather in Chennai is 31°C with partly cloudy skies.
```

---

## 🏗️ Architecture

```
                 User
                  │
                  ▼
          PydanticAI Agent
                  │
          MCP Tool Invocation
                  │
                  ▼
          Weather MCP Server
                  │
                  ▼
         External Weather API
                  │
                  ▼
          Weather Information
                  │
                  ▼
          Natural Language Response
```

---

## 🌟 Why MCP?

Model Context Protocol (MCP) standardizes communication between AI models and external tools. Instead of hardcoding APIs into the LLM, MCP allows AI agents to discover and invoke tools dynamically.

Benefits include:

- Better modularity
- Easier scalability
- Tool reusability
- Secure communication
- Cleaner architecture

---

## 🔮 Future Improvements

- 🌐 Web Search Tool
- 📈 Stock Market Tool
- 📅 Calendar Integration
- 📧 Gmail Integration
- 🗂️ File System Tool
- 🧠 Memory Support
- 💬 Multi-turn Conversations
- 🌍 Maps Tool
- 🖥️ Streamlit UI
- ⚡ FastAPI Backend
- 🐳 Docker Deployment

---

## 📚 Learning Outcomes

This project demonstrates:

- Building AI Agents with PydanticAI
- Working with the Model Context Protocol
- Connecting LLMs to external tools
- Async programming in Python
- Environment variable management
- Production-ready AI architecture

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.

It helps others discover the project and motivates future development.
