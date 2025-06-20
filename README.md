
# 🧠 AI Travel Planner with LangGraph

This application demonstrates how to complete **LangGraph** and other AI agentic workflow assignments using real-world travel planning as the context. The app uses **LLM-driven steps** to simulate or integrate actual APIs like **OpenWeather**, **Yelp**, and **Expedia/Skyscanner**.

---

## 📌 Features

- 🌍 Real-time weather via **OpenWeather API**
- 🍽 Restaurant and attraction lookup via **Yelp API**
- 🏨 Hotel cost estimation using **Expedia/Skyscanner (or simulated)**
- 🧮 Budget estimation with exchange rate conversion
- 🗓 Day-by-day itinerary generation
- 🧵 LangGraph-based workflow to orchestrate modular AI tasks

---

## 📁 Project Structure

```bash
.
├── travel_agent.py         # LangGraph nodes and flow
├── api_wrappers.py         # Real API integrations (OpenWeather, Yelp)
├── main.py                 # Entry point for execution
├── .env                    # API keys (not committed)
└── README.md
