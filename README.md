# 🚀 AI Automation Agents Dashboard (Next.js + Ollama)

A modern AI-powered frontend platform for showcasing, testing, and simulating **AI automation agents** for real-world business workflows.

This project demonstrates how AI can be integrated into enterprise systems like HR, Finance, Support, and Workflow Automation.

---

## ✨ Key Features

- 🤖 AI Agent Simulation Interface  
- 📊 Enterprise Dashboard UI  
- ⚡ Real-time AI responses (via Ollama)  
- 🔁 Fallback demo mode for portfolio usage  
- 🧠 Modular AI agent architecture  
- 🎯 Built for showcasing AI business automation  

---

## 🖥️ Product Showcase


### 🌐 Frontend Product Experience

<p align="center">
  <img src="./Frontend/front_end_page_1.png" width="800"/>
  <img src="./Frontend/front_end_page_2.png" width="800"/>
  <img src="./Frontend/front_end_page_3.png" width="800"/>
  <img src="./Frontend/front_end_page_4.png" width="800"/>
  <img src="./Frontend/front_end_page_5.png" width="800"/>
  <img src="./Frontend/front_end_page_6.png" width="800"/>
</p>

---
---

### 📊 Admin Dashboard (Full System)

<p align="center">
  <img src="./Admin%20Dashboard/admin_dashboard_1.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_2.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_3.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_4.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_5.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_6.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_7.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_8.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_9.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_10.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_11.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_12.png" width="800"/>
  <img src="./Admin%20Dashboard/admin_dashboard_13.png" width="800"/>
</p>

---

## 🏗️ System Architecture

           ┌──────────────────────┐
           │   User / Systems     │
           │ (Email, CRM, Files)  │
           └─────────┬────────────┘
                     ↓
           ┌──────────────────────┐
           │      Intake Layer    │
           │ (messages, forms)    │
           └─────────┬────────────┘
                     ↓
           ┌──────────────────────┐
           │   AI Reasoning Layer │
           │ intent + planning    │
           └─────────┬────────────┘
                     ↓
           ┌──────────────────────┐
           │   Decision Engine    │
           │ rules + approvals    │
           └─────────┬────────────┘
                     ↓
           ┌──────────────────────┐
           │   Action Layer       │
           │ reply / route / save │
           └─────────┬────────────┘
                     ↓
           ┌──────────────────────┐
           │   Observability      │
           │ logs / metrics       │
           └──────────────────────┘

---

## 🤖 AI Agents

Ai Aura is powered by modular, task-specific agents:

### Support Agent
- triages messages  
- drafts responses  
- escalates complex cases  

### Lead Agent
- scores inbound leads  
- prioritizes follow-up  
- suggests next actions  

### Document Agent
- extracts structured data  
- summarizes files  
- flags anomalies  

These agents run on **local LLMs via Ollama**, enabling:
- privacy  
- cost control  
- offline capability  

---

## 📊 Admin Command Center

The system provides a real-time operational view:

- request intake volume  
- queue pressure  
- automation performance  
- failure points  
- revenue signals  

It answers:
> “What needs attention right now?”

---

## 🔁 End-to-End Workflow


Incoming Request
↓
AI understands intent
↓
Decision rules applied
↓
Action generated
↓
Human review (if needed)
↓
Execution + logging


---

## 🔌 Integration Layer

Ai Aura connects to your existing stack:

- Gmail / Outlook  
- HubSpot / Salesforce  
- Slack  
- Google Drive / Dropbox  

It doesn’t replace tools.  
It **orchestrates them.**

---

## 🔐 Safety & Control

- Human-in-the-loop approvals  
- fallback routing for uncertain cases  
- full audit logs  
- role-based visibility  

No blind automation. Ever.

---

## 🛠️ Tech Stack

- Next.js 16  
- React 19  
- TypeScript  
- Tailwind CSS  
- Ollama (local LLM runtime)

---

## 🚀 Getting Started

### Setup
```
git clone https://github.com/your-username/ai-aura.git
cd ai-aura
```
Environment
```
OLLAMA_BASE_URL=http://127.0.0.1:11434
OLLAMA_MODEL=llama3.2:3b
AGENT_DEMO_FALLBACK=true
```
Run
```
ollama serve
ollama pull llama3.2:3b
npm install
npm run dev
```
🎯 Use Cases
Customer support automation
Sales pipeline acceleration
Document-heavy operations
Internal workflow automation
AI-assisted business operations
📈 Why This Matters

The next generation of software is not:

dashboards
CRMs
admin panels

It is:

AI systems that operate businesses

Ai Aura is a step toward that future.

🔮 Roadmap
Multi-agent orchestration
memory + learning system
cross-agent collaboration
enterprise workflow engine
audit-grade explainability
full backend microservices
🧠 Long-Term Vision

Build an AI Company Operating System

Where:

AI agents run workflows
Humans supervise decisions
systems continuously improve

👨‍💻 Author

Shakil
AI Systems Builder | AI Automation | Full-stack Developer
