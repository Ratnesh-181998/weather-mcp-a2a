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

*Figure:High-Definition view of the Smart Weather Dashboard.*
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

<img width="1793" height="766" alt="image" src="https://github.com/user-attachments/assets/9a528f19-6531-4b96-a593-cec93644fc04" />
<img width="1331" height="613" alt="image" src="https://github.com/user-attachments/assets/a524fad0-c9de-495b-9bf9-d88ef66a0f04" />
<img width="1294" height="612" alt="image" src="https://github.com/user-attachments/assets/5ccdb062-f609-4f27-8737-947f7db6058a" />
<img width="1365" height="751" alt="image" src="https://github.com/user-attachments/assets/063d7303-0e96-4dff-a152-ee5651ac0948" />
<img width="1332" height="656" alt="image" src="https://github.com/user-attachments/assets/7441c4df-81c2-4eef-b479-394bbc6346c4" />
<img width="1359" height="779" alt="image" src="https://github.com/user-attachments/assets/9b597c1a-af8d-45b1-adb8-c7b3c2944115" />
<img width="1267" height="597" alt="image" src="https://github.com/user-attachments/assets/0f91c507-c9aa-4b80-98cb-0c2027d18c5d" />
<img width="1375" height="687" alt="image" src="https://github.com/user-attachments/assets/09b4bbff-b6aa-4b98-acca-0ac9825cd4d2" />


### 2. ℹ️ About Project (Educational Hub)
A detailed breakdown of the paradigm shift in AI.
*   **Evolution Timeline**: Visualizing the shift from Static LLMs -> Tool-Use Agents -> MCP Ecosystems.
*   **Protocol Comparison**: Why MCP is superior to proprietary plugin architectures.
*   **Interactive Simulations**: step-by-step walkthroughs of the agent's decision-making process.
  
<img width="1785" height="804" alt="image" src="https://github.com/user-attachments/assets/0c3216a8-c614-4e58-a31a-861757cc2dad" />
<img width="1487" height="633" alt="image" src="https://github.com/user-attachments/assets/a13f16fd-1cbc-4846-b466-3dec020adfd4" />
<img width="1500" height="783" alt="image" src="https://github.com/user-attachments/assets/a47d3c70-849f-4d8d-a800-fad2ee5d21db" />
<img width="1467" height="615" alt="image" src="https://github.com/user-attachments/assets/1e20bd9c-175a-4555-b45f-1ea7a8abbd02" />
<img width="1473" height="664" alt="image" src="https://github.com/user-attachments/assets/8a0ca20c-9e08-4a73-8a88-f7459859f23f" />

### 3. 🛠️ Tech Stack (Under the Hood)
Transparency in engineering.
*   **AI Core**: Llama 3.3 70B (Reasoning), LangChain (Orchestration).
*   **Frontend**: Streamlit Async Runtime, Custom CSS theming.
*   **Connectivity**: `mcp-use` Client, `requests` library, RESTful APIs (Open-Meteo, NWS).
  
<img width="1892" height="792" alt="image" src="https://github.com/user-attachments/assets/e1664228-a617-4e64-b9b4-61394b0dc526" />
<img width="1855" height="782" alt="image" src="https://github.com/user-attachments/assets/a4950e12-8656-4bbc-b192-4e9fe7b08164" />


### 4. 🏗️ Architecture (System Design)
Enterprise-grade visualization of the system.
*   **Data Flow**: `User -> Streamlit -> Agent -> MCP Client -> Tool -> Response`.
*   **Graphviz Charts**: Dynamically generated DAGs (Directed Acyclic Graphs) of the agent's logic.
*   **Network Topology**: Visualizing how the Host, Client, and Server interact.
<img width="1802" height="798" alt="image" src="https://github.com/user-attachments/assets/69375ee7-baa2-4934-82e1-298a18938c4b" />
<img width="1816" height="806" alt="image" src="https://github.com/user-attachments/assets/ce3dc07c-1305-4b69-85c9-e032a91cef35" />


### Detailed Graph Visualization
<img width="1119" height="523" alt="image" src="https://github.com/user-attachments/assets/c3f41704-7b5d-47ef-9222-44e29ffb2bed" />

#### 📂 Detailed Architecture Diagrams
- Diagram 1: Basic MCP Architecture
  <img width="1153" height="680" alt="image" src="https://github.com/user-attachments/assets/8c5bcb5a-3812-4bd7-823b-e7b07f8a085d" />
- Diagram 2: LLM + MCP Tool Selection Flow
  <img width="1208" height="763" alt="image" src="https://github.com/user-attachments/assets/f5ea2378-c665-4600-9fdd-a193593d5fc4" />
- Diagram 3: Multi-Tool MCP Server
  <img width="1030" height="617" alt="image" src="https://github.com/user-attachments/assets/a2f36aea-068c-40eb-a021-2eec2c798350" />
- Diagram 4: A2A Multi-Agent Architecture
   <img width="1132" height="673" alt="image" src="https://github.com/user-attachments/assets/41df1a35-d2ed-4a9e-beeb-791e563efc16" />
- Diagram 5: MCP vs A2A Combined System
  <img width="1079" height="613" alt="image" src="https://github.com/user-attachments/assets/24445a45-abee-4ca1-92c9-3ab2aa23d692" />


### 5. 📋 System Logs (Observability)
Production-ready monitoring.
*   **Real-time Event Stream**: Live tracking of every thought, tool call, and API response.
*   **Status Codes**: Visual indicators for `SUCCESS`, `ERROR`, and `INFO`.
*   **Audit Trails**: Downloadable JSON/TXT logs for debugging and analytics.
<img width="1834" height="818" alt="image" src="https://github.com/user-attachments/assets/3dc62c01-2608-4fbf-882f-7d60dc54de0e" />
<img width="1651" height="818" alt="image" src="https://github.com/user-attachments/assets/30fd0ff5-52d8-46b5-b0d4-7b3681544083" />

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
*   🌐 **Live Demo**: [Streamlit Cloud App](https://weather-mcp-a2a-agent-to-agent3a95dbsjhgfhd3yussfz3e.streamlit.app/)

### Project Links
*   📖 **Documentation**: [GitHub Wiki](https://github.com/Ratnesh-181998/weather-mcp-a2a/wiki)
*   🐛 **Issue Tracker**: [GitHub Issues](https://github.com/Ratnesh-181998/weather-mcp-a2a/issues)
*   💬 **Discussions**: [GitHub Discussions](https://github.com/Ratnesh-181998/weather-mcp-a2a/discussions)

---

---


<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,20,12,6&height=3" width="100%">


## 📜 **License**

![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge&logo=opensourceinitiative&logoColor=white)

**Licensed under the MIT License** - Feel free to fork and build upon this innovation! 🚀

---

# 📞 **CONTACT & NETWORKING** 📞


### 💼 Professional Networks

[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ratneshkumar1998/)
[![GitHub](https://img.shields.io/badge/🐙_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ratnesh-181998)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/RatneshS16497)
[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://share.streamlit.io/user/ratnesh-181998)
[![Email](https://img.shields.io/badge/✉️_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rattudacsit2021gate@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rattudacsit2021gate)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-F58025?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/32068937/ratnesh-kumar)

### 🚀 AI/ML & Data Science
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://share.streamlit.io/user/ratnesh-181998)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/RattuDa98)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/rattuda)

### 💻 Competitive Programming
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Ratnesh_1998/)
[![HackerRank](https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://www.hackerrank.com/profile/rattudacsit20211)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/ratnesh_181998)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Ratnesh_181998)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/ratnesh1998)
[![HackerEarth](https://img.shields.io/badge/HackerEarth-323754?style=for-the-badge&logo=hackerearth&logoColor=white)](https://www.hackerearth.com/@ratnesh138/)
[![InterviewBit](https://img.shields.io/badge/InterviewBit-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://www.interviewbit.com/profile/rattudacsit2021gate_d9a25bc44230/)


---

## 📊 **GitHub Stats & Metrics** 📊



![Profile Views](https://komarev.com/ghpvc/?username=Ratnesh-181998&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)





<img src="https://github-readme-streak-stats.herokuapp.com/?user=Ratnesh-181998&theme=radical&hide_border=true&background=0D1117&stroke=4ECDC4&ring=F38181&fire=FF6B6B&currStreakLabel=4ECDC4" width="48%" />




<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ratnesh-181998&theme=react-dark&hide_border=true&bg_color=0D1117&color=4ECDC4&line=F38181&point=FF6B6B" width="48%" />

---

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=4ECDC4&center=true&vCenter=true&width=600&lines=Ratnesh+Kumar+Singh;Data+Scientist+%7C+AI%2FML+Engineer;4%2B+Years+Building+Production+AI+Systems" alt="Typing SVG" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2000&pause=1000&color=F38181&center=true&vCenter=true&width=600&lines=Built+with+passion+for+the+AI+Community+🚀;Innovating+the+Future+of+AI+%26+ML;MLOps+%7C+LLMOps+%7C+AIOps+%7C+GenAI+%7C+AgenticAI+Excellence" alt="Footer Typing SVG" />


<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%">


