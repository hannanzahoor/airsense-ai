# 🌍 AirSense AI

An AI-powered Air Quality Intelligence & Health Advisor. It combines **real-time AQI extraction**, **LLM reasoning**, and **personalized health recommendations** to help users make informed decisions about outdoor activities.

The application retrieves live air quality data for any location, analyzes environmental conditions, and generates personalized health recommendations based on the user's medical conditions and planned outdoor activities.

---

# ✨ Features

- 🌎 Real-time AQI analysis for cities worldwide
- 🤖 AI-powered personalized health recommendations
- 🩺 Context-aware suggestions based on medical conditions
- 🚶 Activity-specific outdoor safety analysis
- 🌬️ Live weather and pollution metrics
- 📊 Structured AQI visualization
- 🖥️ Available in both Gradio and Streamlit interfaces

---

# 🏗️ Architecture

```
                User Input
                     │
                     ▼
        Firecrawl Web Extraction
                     │
                     ▼
        Structured AQI Data (Pydantic)
                     │
                     ▼
         Agno AI Agent (GPT-4o)
                     │
                     ▼
      Personalized Health Recommendations
                     │
                     ▼
      Gradio / Streamlit User Interface
```

---

# ⚙️ Tech Stack

## AI

- Agno AI Agent Framework
- OpenAI GPT-4o

## Backend

- Python
- Pydantic
- Firecrawl API

## Frontend

- Gradio
- Streamlit

---

# 📊 Air Quality Metrics

The application analyzes:

- Air Quality Index (AQI)
- PM2.5
- PM10
- Carbon Monoxide (CO)
- Temperature
- Humidity
- Wind Speed

---

# 🧠 AI Recommendation Engine

The AI agent generates personalized recommendations based on:

- Current AQI level
- Air pollutants
- Weather conditions
- User medical history
- Planned outdoor activity

The generated report includes:

- Health impact analysis
- Outdoor activity recommendations
- Safety precautions
- Best time for the activity

---

# 📁 Project Structure

```
.
├── ai_aqi_analysis_agent_gradio.py
├── ai_aqi_analysis_agent_streamlit.py
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/hannanzahoor/ai-aqi-analysis-agent.git
cd ai-aqi-analysis-agent
```

Create a virtual environment

```bash
python -m venv venv
```

Activate it

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 API Keys

Create accounts and obtain API keys for:

- OpenAI
- Firecrawl

The application prompts you to enter both keys at runtime.

---

# ▶️ Running the Application

## Gradio

```bash
python ai_aqi_analysis_agent_gradio.py
```

## Streamlit

```bash
streamlit run ai_aqi_analysis_agent_streamlit.py
```

---

# 📸 Workflow

1. Enter API keys.
2. Select a location.
3. Enter medical conditions (optional).
4. Describe your planned outdoor activity.
5. View live AQI data.
6. Receive AI-generated health recommendations.

---

# 🔮 Future Improvements

- Historical AQI trends
- Multi-agent reasoning
- Weather forecasting integration
- Air quality comparison across cities
- PDF health reports
- Interactive charts

---
