# 🤖 Autara AI – Customer Success Co-Pilot

Autara AI is an AI-powered toolkit for Customer Success Managers, Technical Account Managers, and Solutions Engineers. Built with Next.js and FastAPI, it helps you streamline your workflow with tools like:

- ✍️ **Meeting Summarizer**  
- 🗺 **Success Plan Generator** *(coming soon)*  
- 🚦 **Health Score Estimator** *(coming soon)*  
- 📬 **Communication Assistant** *(coming soon)*  

Whether you're closing loops, preparing EBRs, or scaling personalized customer strategies, Autara AI is your co-pilot.

---

## 🔧 Tech Stack

| Layer      | Tech                 |
|------------|----------------------|
| Frontend   | Next.js 14, Tailwind CSS, TypeScript |
| Backend    | FastAPI, Python, OpenAI API |
| Planning   | Notion (project tracker) |
| Dev Tools  | VS Code, GitHub, Render/Vercel |

---

## 🚀 Current Status

✅ MVP Feature: **Meeting Summarizer**  
🔄 In Progress: Success Plan Generator  
📆 Planned: Full-stack deployment and LinkedIn demo

---

## 🛠 Getting Started

### 🔐 Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate   # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload --port 8000

