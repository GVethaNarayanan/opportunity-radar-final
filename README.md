# Opportunity Radar

AI-powered FinTech dashboard that pipelines 6 algorithmic agents. 

## Setup Instructions
1. Navigate into this folder `cd opportunity-radar`
2. Install dependencies: `pip install -r backend/requirements.txt`
3. Launch with Docker: `docker-compose up --build`
   *If you do not have docker, launch backend with `cd backend && uvicorn main:app --port 8000` and frontend with `cd frontend && python -m http.server 80`*
4. Access at `http://localhost` (or the respective port you launched on).

Set `OPENAI_API_KEY` for OpenAI model features.

# Opportunity Radar 🚀

AI-powered FinTech dashboard that uses a multi-agent pipeline to detect high-confidence opportunities.

---

## 🚀 Quick Demo

1. Open frontend:
   cd frontend
   python -m http.server 5500

2. Open in browser:
   http://127.0.0.1:5500

3. Click **Run AI Scan** to execute the AI pipeline

---

## 🖥️ What You Will See

- AI Agent Pipeline visualization
- Signals from:
  - Technical indicators
  - Sentiment analysis
  - Filing data
- Final classification:
  - Bullish
  - Bearish
  - High Conviction opportunities

---

## ⚙️ How It Works

1. Data ingestion from multiple sources  
2. AI agents analyze:
   - Technical signals  
   - Sentiment  
   - Filings  
3. Scoring engine combines signals  
4. Final AI synthesis generates insights  

---

## 🛠️ Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Python (FastAPI)  
- AI: OpenAI API  

---

## 👨‍💻 Developed by

Vetha Narayanan