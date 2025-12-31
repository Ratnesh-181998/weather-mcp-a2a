# 🌤️ Weather MCP Agent: Global Intelligence System

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://appudtzei3tyyttd6xjhwur.streamlit.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Groq Powered](https://img.shields.io/badge/AI-Groq%20LPU-orange)](https://groq.com/)
[![MCP Protocol](https://img.shields.io/badge/Protocol-MCP-green)](https://modelcontextprotocol.io/)

> **Next-Generation Agentic AI** powered by the **Model Context Protocol (MCP)** and **Llama 3 (Groq)**. A real-time, multi-modal weather intelligence system that bridges the gap between Large Language Models and deterministic data tools.

---

## 🚀 Overview

The **Weather MCP Agent** is a state-of-the-art implementation of the **Model Context Protocol (MCP)**, designed to demonstrate the future of AI interoperability. Unlike traditional chatbots that hallucinate data, this agent uses a standardized protocol to "connect" to live tools—fetching real-time weather forecasts, alerts, and atmospheric analytics for **any city on Earth**.

Built on **Streamlit** for a reactive UI and powered by **Groq's LPU** for near-instant inference, this system showcases how **Agentic AI** can orchestrate complex workflows (Geocoding -> Weather API -> Conversational Synthesis) in milliseconds.

---
## 🌐🎬 Live Demo
🚀 **Try it now:**
- **Streamlit Profile** - https://share.streamlit.io/user/ratnesh-181998
- **Project Demo** - https://weather-mcp-a2a-agent-to-agent3a95dbsjhgfhd3yussfz3e.streamlit.app/
---

### 🌟 Key Capabilities
*   **🌍 Global Coverage**: Instant weather intelligence for 100,000+ cities worldwide.
*   **⚡ Hyper-Fast Inference**: Uses Llama 3 70B on Groq LPUs for sub-second reasoning.
*   **🔌 Standardized Tooling**: Built 100% on the open-source MCP standard.
*   **🗣️ Multi-Modal Input**: Supports both Text and Voice (WebRTC) interaction.
*   **🧠 Smart Context**: Maintains conversation history and context-aware responses.

---

## 🎮 Interface & Features by Tab

The application is structured into 5 professional modules, each serving a specific purpose in the Agentic workflow:
#### Live Interface Preview
<img width="1888" height="789" alt="image" src="https://github.com/user-attachments/assets/9c6ee46b-c429-4771-b341-bbe7ea3bc4f5" />
*Figure: High-Definition view of the Smart Weather Dashboard.*
![Weather MCP Agent UI](assets/app_mockup.png)

### 1. 🚀 Project Demo (Interactive Core)
The command center of the application.
*   **AI Chat Interface**: Real-time conversation with the Agent.
*   **Quick Action Grid**: One-click execution for 16+ common scenarios.
*   **Smart City Extraction**: NLP-powered logic covers complex queries.
*   **Voice Input**: Speak naturally to the agent.



> **⚡ See it in Action:**
>
> ![Live Demo](assets/demo_video.webp)



### 2. ℹ️ About Project (Educational Hub)
A detailed breakdown of the paradigm shift in AI.
*   **Evolution Timeline**: Visualizing the shift from Static LLMs -> Tool-Use Agents -> MCP Ecosystems.
*   **Protocol Comparison**: Why MCP is superior to proprietary plugin architectures.
*   **Interactive Simulations**: step-by-step walkthroughs of the agent's decision-making process.

### 3. 🛠️ Tech Stack (Under the Hood)
Transparency in engineering.
*   **AI Core**: Llama 3.3 70B (Reasoning), LangChain (Orchestration).
*   **Frontend**: Streamlit Async Runtime, Custom CSS theming.
*   **Connectivity**: `mcp-use` Client, `requests` library, RESTful APIs (Open-Meteo, NWS).


### 5. 🏗️ Architecture (System Design)
Enterprise-grade visualization of the system.
*   **Data Flow**: `User -> Streamlit -> Agent -> MCP Client -> Tool -> Response`.
*   **Graphviz Charts**: Dynamically generated DAGs (Directed Acyclic Graphs) of the agent's logic.
*   **Network Topology**: Visualizing how the Host, Client, and Server interact.

#### System Visualization
![Architecture Overview](assets/mcp_combined.png)
*Figure 1: High-Level System Architecture bridging User, Agent, and MCP Tools.*

![MCP Flow](assets/mcp_flow.png)
*Figure 2: Detailed Data Flow from User Input to Tool Execution.*


### 5. 📋 System Logs (Observability)
Production-ready monitoring.
*   **Real-time Event Stream**: Live tracking of every thought, tool call, and API response.
*   **Status Codes**: Visual indicators for `SUCCESS`, `ERROR`, and `INFO`.
*   **Audit Trails**: Downloadable JSON/TXT logs for debugging and analytics.

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Orchestration** | **LangChain** | Manages the ReAct (Reason+Act) loop and prompt engineering. |
| **Protocol** | **MCP (Model Context Protocol)** | The universal standard for connecting AI models to external tools. |
| **Inference Engine** | **Groq LPU** | Provides the speed necessary for real-time agentic workflows. |
| **LLM** | **Llama 3.3 70B** | The "Brain" capable of complex tool selection and JSON parsing. |
| **Frontend** | **Streamlit** | Delivers a responsive, Python-native web interface. |
| **Data Source** | **Open-Meteo API** | Provides high-precision weather data without API keys. |
| **Audio** | **SpeechRecognition / WebRTC** | Handles voice-to-text conversion. |

---

## ⚙️ Installation & Local Setup

Follow these steps to run the agent on your local machine.

### Prerequisites
*   Python 3.10+
*   A [Groq API Key](https://console.groq.com/) (Free)

### 1. Clone the Repository
```bash
git clone https://github.com/Ratnesh-181998/weather-mcp-a2a.git
cd weather-mcp-a2a
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Secrets
Create a `.env` file in the root directory:
```env
GROQ_API_KEY=your_actual_api_key_here
```

### 5. Run the App
```bash
streamlit run Weather_streamlit_app.py
```

---

## 🐳 Large File Support (Git LFS)

This repository may contain large assets (images/diagrams). We use Git LFS to manage them efficiently.

```bash
# Install Git LFS
git lfs install

# Track large files
git lfs track "*.png"
git lfs track "*.jpg"

# Push to remote
git add .
git commit -m "Add large visual assets"
git push origin main
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1.  Fork the repository.
2.  Create a feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact & Community

**Ratnesh Kumar Singh**  
*Data Scientist (AI/Ml Engineer 4+ Yrs Exp)*

*   💼 **LinkedIn**: [ratneshkumar1998](https://www.linkedin.com/in/ratneshkumar1998/)
*   🐙 **GitHub**: [Ratnesh-181998](https://github.com/Ratnesh-181998)
*   🌐 **Live Demo**: [Streamlit Cloud App](https://appudtzei3tyyttd6xjhwur.streamlit.app/)

### Project Links
*   📖 **Documentation**: [GitHub Wiki](https://github.com/Ratnesh-181998/weather-mcp-a2a/wiki)
*   🐛 **Issue Tracker**: [GitHub Issues](https://github.com/Ratnesh-181998/weather-mcp-a2a/issues)
*   💬 **Discussions**: [GitHub Discussions](https://github.com/Ratnesh-181998/weather-mcp-a2a/discussions)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,100:9b59b6&height=120&section=footer"/>
</p>
