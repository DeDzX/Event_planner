# Event_planner
A multi-agent Event Planner built using LangGraph and LangChain. Supports vendor selection, scheduling, budget estimation, and human-in-the-loop simulation. 


# 🎯 Agentic Event Planner Assistant (Kaara AI Engineer Assignment)

This repository contains a multi-agent system built using **LangGraph** to simulate an intelligent Event Planner Assistant. The project was developed as part of the Kaara AI Engineer assignment in July 2025.

## 📌 Objective

Design and implement a **multi-agent system** capable of planning events such as weddings, conferences, or concerts using agent collaboration and tool-based reasoning.

## 🛠️ Tech Stack

- **LangGraph** for multi-agent orchestration
- **LangChain** for LLM interfacing and tools
- **OpenAI** or compatible LLM for task handling
- **Python** (Jupyter Notebook)

## 🧠 Agents

- `planner_agent`: Orchestrates the planning process
- `vendor_agent`: Suggests vendors for various event needs
- `scheduler_agent`: Proposes potential event dates
- `budget_agent`: Estimates costs based on vendors and preferences
- *(Optional extension: `review_agent` for human-in-the-loop simulation)*

## 🔧 Tools Used

- `structured_tool_vendor_selector`: Selects vendors based on location, budget, type
- `structured_tool_budget_estimator`: Estimates the cost for event setups *(defined but not fully wired into the graph)*

## 🔄 Workflow Features

- Agent collaboration via LangGraph nodes
- Clean loop termination (`_next = None`)
- Manual review placeholder for human-in-the-loop control
- Streaming logic for progressive output

## ✅ Features Implemented

- ✔ Multi-agent graph
- ✔ LangGraph `.stream()` loop
- ✔ Vendor selection tool
- ✔ Final state output
- ⚠ Budget estimator defined (not integrated)
- ⚠ Human review logic placeholder only

## 📁 Files

- `Final_final.ipynb` – Full implementation + research
- `README.md` – This file

## 🚀 How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Open `Final_final.ipynb` in Jupyter Lab or VSCode.
3. Follow the notebook instructions to run the event planning simulation.

## 📞 Contact

Built by **Vansh Ahlawat** | For Kaara AI Engineer Role – July 2025

