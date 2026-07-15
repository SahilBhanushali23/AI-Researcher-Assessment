# 🚀 AI Researcher Technical Assessment

## 📌 Project Overview

This repository contains my submission for the AI Researcher Technical Assessment. The project is divided into two main phases:

1. **Phase 1 – LLM Research & Evaluation**
2. **Phase 2 – Multi-Agent AI Proof of Concept (POC)**

The objective was to evaluate Large Language Models (LLMs) and develop a Multi-Agent AI workflow capable of solving a real-world business problem.

---

# 📂 Repository Structure

```
AI-Researcher-Assessment/
│
├── notebooks/
│   ├── Research_Evaluation.ipynb
│   └── Multi_Agent_POC.ipynb
│
├── report/
│
├── presentation/
│
├── README.md
└── requirements.txt
```

---

# 📖 Phase 1 – LLM Research & Evaluation

This phase compares a **Closed Source LLM** and an **Open Source LLM**.

### Models Evaluated

- Google Gemini (Closed Source)
- Llama 3.1 8B Instant (Groq) (Open Source)

### Evaluation Criteria

- General Question Answering
- Multi-turn Conversations
- Structured JSON Output
- Reasoning Ability
- Context Retention
- Response Quality

### Outcome

A comparative analysis was performed to evaluate the strengths and limitations of each model for enterprise AI applications.

---

# 🤖 Phase 2 – Multi-Agent AI Proof of Concept

A Multi-Agent AI workflow was developed using **LangGraph** and **Groq's Llama 3.1**.

### Business Use Case

**AI-Powered Logistics Disruption Management**

The system simulates how AI agents collaborate to manage shipment delays in pharmaceutical logistics.

### Workflow

```
Shipment Information
        │
        ▼
Alert Analysis Agent
        │
        ▼
Route Planning Agent
        │
        ▼
Decision Agent
        │
        ▼
Execution Agent
        │
        ▼
Final Execution Report
```

---

# 🧠 AI Agents

## 1. Alert Analysis Agent

Responsibilities:

- Analyze shipment delays
- Identify delay reasons
- Determine severity
- Recommend immediate actions

---

## 2. Route Planning Agent

Responsibilities:

- Generate alternative delivery routes
- Estimate ETA
- Estimate transportation cost
- Recommend the best route

---

## 3. Decision Agent

Responsibilities:

- Evaluate all available routes
- Compare cost, ETA and risk
- Select the optimal route

---

## 4. Execution Agent

Responsibilities:

- Generate execution report
- Update shipment status
- Notify stakeholders
- Produce final logistics summary

---

# 🛠️ Technologies Used

- Python
- Google Colab
- LangGraph
- LangChain
- Groq API
- Llama 3.1 8B Instant
- Google Gemini
- Jupyter Notebook

---

# 📊 Key Features

- Comparative LLM Evaluation
- Multi-Agent AI Workflow
- Shared State Management
- LangGraph Orchestration
- AI-Based Decision Making
- Logistics Automation Proof of Concept

---

# 🚀 How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/AI-Researcher-Assessment.git
```

---

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3. Configure API Keys

Set the required API keys before running the notebooks.

Example:

```
GROQ_API_KEY=your_api_key
GOOGLE_API_KEY=your_api_key
```

---

## 4. Run the Notebooks

Run the notebooks in the following order:

1. Research_Evaluation.ipynb
2. Multi_Agent_POC.ipynb

---

# 📈 Future Improvements

- Google Maps API Integration
- Real-Time Traffic Analysis
- Weather-Based Route Optimization
- ERP Integration (SAP)
- Live Shipment Tracking
- Human Approval Workflow
- Web Dashboard Deployment

---

# 👨‍💻 Author

**Sahil Bhanushali**

Data Science Engineering Student

AI | Machine Learning | Data Analytics | Generative AI

---

# 📄 License

This project was developed as part of an AI Researcher Technical Assessment for educational and evaluation purposes.
