
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050816,50:003B5C,100:00D9FF&height=190&section=header&text=GramSahayak&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=AI-Powered%20Gram%20Panchayat%20Complaint%20Management&descAlignY=60&descSize=15" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Smart+Village+Complaint+Management;Autonomous+Multi-Agent+AI+System;From+Complaint+to+Resolution;Technology+for+Rural+Communities" />

<br/>

<img src="https://img.shields.io/badge/AI-Multi--Agent%20System-00D9FF?style=for-the-badge" />
<img src="https://img.shields.io/badge/Python-3.11-050816?style=for-the-badge&logo=python&logoColor=00D9FF" />
<img src="https://img.shields.io/badge/FastAPI-Backend-050816?style=for-the-badge&logo=fastapi&logoColor=00D9FF" />
<img src="https://img.shields.io/badge/SQLite-Database-050816?style=for-the-badge&logo=sqlite&logoColor=00D9FF" />

<br/><br/>

**Empowering villages through intelligent complaint management.**

</div>

---

## 🌍 About The Project

**GramSahayak** is an autonomous multi-agent AI system designed to transform how Gram Panchayats receive, manage, track, and resolve citizen complaints.

It focuses on two essential rural infrastructure issues:

- 💧 Water supply problems
- 🧹 Sanitation and cleanliness issues

Instead of relying on slow manual processes, GramSahayak uses specialized AI agents to process complaints, identify urgency, assign responsible officers, generate action documents, and monitor deadlines.

### 🎯 Our Mission

To make rural grievance management smarter, faster, more transparent, and accountable.

---

## 🚨 The Problem

In many villages, citizen complaints face several challenges:

- Complaints are recorded manually or informally.
- Urgent issues may not receive immediate attention.
- Duplicate complaints create unnecessary workload.
- Citizens have limited visibility into complaint status.
- Delayed actions often go unnoticed.
- There is no consistent automated escalation mechanism.

## 💡 Our Solution

GramSahayak introduces an intelligent multi-agent workflow that manages the complaint lifecycle from submission to escalation.

<details>
<summary><b>✨ Key Features</b></summary>

- 🤖 Autonomous multi-agent complaint processing
- 🧠 AI-powered complaint classification and prioritization
- 🔍 Duplicate complaint detection
- 📍 Location and urgency extraction
- 📚 Context and relevant-rule research
- 📄 Automated work-order drafting
- 📢 Officer and citizen notifications
- ⏰ Deadline monitoring and escalation
- 📊 Complaint management dashboard

</details>

---

## ⚙️ How It Works

<div align="center">

```mermaid
flowchart TD
    A["👤 Citizen Submits Complaint"] --> B["📥 Intake Agent"]
    B --> C["🧠 Triage Agent"]
    C --> D["🔍 Research Agent"]
    D --> E["⚡ Action Agent"]
    E --> F["📄 Work Order Generated"]
    F --> G["📢 Officer & Citizen Notified"]
    H["⏰ Monitor Agent"] -.-> C
    H -.-> E
    H -.-> G
    H --> I["🚨 Automatic Escalation"]
    I --> J["👨‍💼 Higher Authority"]
    
    style A fill:#003B5C,color:#fff
    style B fill:#050816,color:#00D9FF
    style C fill:#050816,color:#00D9FF
    style D fill:#050816,color:#00D9FF
    style E fill:#050816,color:#00D9FF
    style H fill:#003B5C,color:#fff
    style I fill:#4A1942,color:#fff
```

</div>

### 🤖 Meet the Five AI Agents

| Agent | Responsibility |
|:---|:---|
| 📥 Intake Agent | Extracts complaint category, location, and urgency |
| 🧠 Triage Agent | Detects duplicates, assigns priority, and selects an officer |
| 🔍 Research Agent | Finds relevant rules, contextual information, and similar cases |
| ⚡ Action Agent | Drafts work orders and prepares officer/citizen notifications |
| ⏰ Monitor Agent | Tracks deadlines and automatically escalates overdue cases |

---

## 🛠️ Technology Stack

<div align="center">

| Technology | Purpose |
|:---:|:---|
| ![Python](https://img.shields.io/badge/Python-050816?style=flat&logo=python&logoColor=00D9FF) | Core programming |
| ![FastAPI](https://img.shields.io/badge/FastAPI-050816?style=flat&logo=fastapi&logoColor=00D9FF) | Backend API |
| ![SQLite](https://img.shields.io/badge/SQLite-050816?style=flat&logo=sqlite&logoColor=00D9FF) | Database |
| ![Anthropic](https://img.shields.io/badge/Anthropic_API-050816?style=flat&logo=anthropic&logoColor=00D9FF) | AI agent intelligence |
| ![HTML](https://img.shields.io/badge/HTML5-050816?style=flat&logo=html5&logoColor=00D9FF) | Frontend |
| ![JavaScript](https://img.shields.io/badge/JavaScript-050816?style=flat&logo=javascript&logoColor=00D9FF) | Frontend interactions |

</div>

---

## 📂 Project Structure

```text
GramSahayak/
│
├── app/
│   ├── main.py
│   ├── agents/
│   │   ├── intake.py
│   │   ├── triage.py
│   │   ├── research.py
│   │   ├── action.py
│   │   └── monitor.py
│   │
│   ├── routes/
│   ├── services/
│   └── database/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

*Adjust this structure to match your actual repository.*

---

## 🚀 Getting Started

### Prerequisites

- Python 3.11
- pip
- Anthropic API key

### Installation

**1. Clone the repository**

```bash
git clone <repo-url>
cd <team-name>
```

**2. Create a virtual environment**

```bash
python -m venv venv
```

**3. Activate the environment**

Windows:
```bash
venv\Scripts\activate
```

Linux / macOS:
```bash
source venv/bin/activate
```

**4. Install dependencies**

```bash
pip install -r requirements.txt
```

**5. Configure environment variables**

```bash
cp .env.example .env
```

Add your API key to `.env`:

```env
ANTHROPIC_API_KEY=your_api_key_here
```

Never commit your actual `.env` file or API key.

**6. Run the application**

```bash
uvicorn app.main:app --reload
```

**7. Open the dashboard**

```text
http://localhost:8000
```

Click **Load Sample Complaint** to explore the demonstration workflow.

---

## 🎬 Demo Workflow

<div align="center">

| Step | Demonstration |
|:---:|:---|
| 01 | Submit a sample water supply complaint |
| 02 | Intake Agent extracts complaint details |
| 03 | Triage Agent evaluates urgency and duplicates |
| 04 | Research Agent gathers relevant context |
| 05 | Action Agent drafts a work order |
| 06 | Monitor Agent tracks deadlines and escalation |

</div>

---

## 🌱 Social Impact

GramSahayak aims to contribute towards:

- 💧 Improved water supply complaint handling
- 🏡 Cleaner and healthier village environments
- ⚖️ Better administrative accountability
- 📊 Transparent complaint tracking
- 🤝 Stronger communication between citizens and local authorities

---

## 🔮 Future Enhancements

- 🌐 Multilingual complaint submission
- 📱 WhatsApp-based complaint registration
- 🗺️ Geographic complaint visualization
- 📷 Image-based issue identification
- 📈 Advanced analytics and reporting
- 🔔 SMS and real-time notifications
- 🏛️ Integration with official Panchayat systems

---

## 👥 Our Team

<div align="center">

**Built with 💙 for smarter and more accountable villages.**

| Team Member | Role |
|:---:|:---|
| <names> | AI / ML Engineering & Development |

</div>

---

<div align="center">

### 💙 GramSahayak

**Smart Villages. Faster Responses. Better Communities.**

*Technology with a purpose. Innovation with impact.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,50:003B5C,100:050816&height=120&section=footer" />

</div>
