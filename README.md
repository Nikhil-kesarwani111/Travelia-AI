# ✈️ Travelia AI
### AI-Powered Travel Itinerary Agent

Travelia AI is an **LLM-driven travel itinerary planning system** that generates personalized one-day travel plans based on user preferences.  
It combines **LLM reasoning**, **agent-style workflows**, and a **modern UI** to deliver structured, context-aware itineraries.

The project demonstrates **applied Generative AI engineering**, including prompt design, agent orchestration, and production-ready UI integration.

---
<img width="1907" height="956" alt="Screenshot 2026-01-14 164140" src="https://github.com/user-attachments/assets/709604f9-56e2-431b-812a-9f62462b424f" />


## 🚀 Key Features

- Personalized one-day travel itineraries based on:
  - Destination city
  - User interests (culture, food, landmarks, etc.)
- LLM-powered reasoning using **LLaMA 3.3 (70B)** via Groq
- Agent-style workflow built with **LangGraph**
- Clean and responsive UI using **Gradio**
- Stylish, readable itinerary output with emojis and structure

---

## 🧠 System Architecture
<img width="411" height="576" alt="image" src="https://github.com/user-attachments/assets/356f1b44-0d3d-4d94-8fe4-ea6c74dc9f77" />


---

## 🤖 Agent Workflow (LangGraph)

The travel planner is implemented as a **state-driven agent** using LangGraph:

1. **Input City Node**
   - Captures destination city
2. **Input Interests Node**
   - Parses user interests
3. **Itinerary Generation Node**
   - Invokes the LLM with structured prompts
4. **Final Output**
   - Returns a formatted, user-friendly itinerary

This design mirrors real-world **agent-based LLM systems**.

---

## 🛠️ Tech Stack

- **Language:** Python
- **LLM:** LLaMA 3.3 (70B) via Groq
- **Agent Framework:** LangGraph
- **Prompting:** LangChain
- **UI:** Gradio
- **Visualization:** Mermaid (Agent graph)

---

## 📁 Project Structure
<img width="525" height="230" alt="image" src="https://github.com/user-attachments/assets/1781a004-b3c7-43cc-820d-55f9c51455e0" />


