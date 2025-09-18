# OpenDeepResearcher

An Agentic LLM Research Framework built for autonomous research assistance.

## 📌 Project Description
This project implements Milestone 1 (**Scope Phase**) of the OpenDeepResearcher framework.  
The system clarifies user queries, refines them, decides whether to use web search, and produces structured summaries.  
It also stores memory for facts and previous questions.

## 🚀 Tech Stack
- Google Colab (Python 3.10+)
- LangGraph
- LangChain
- Google Gemini API
- Tavily API

## 🧩 Milestone 1 Features
- Clarification Agent (checks vague vs clear queries)
- Query Generator (refines queries)
- Research Pipeline (decides Gemini vs Tavily+Gemini)
- Memory System (facts + history)
- Continuous Chatbot loop with quit option

## 📂 Notebook
- `Milestone1_ScopePhase.ipynb`

## 📜 How to Run
1. Open the notebook in Google Colab.
2. Enter your **Gemini API Key** and **Tavily API Key**.
3. Run cells 1 → 10 in order.
4. Interact with the chatbot in the last cell.

---
