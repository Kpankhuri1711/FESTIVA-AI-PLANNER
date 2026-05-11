# 🎉 FESTIVA-AI-PLANNER

AI-powered event planning assistant using LLMs, RAG, Machine Learning, and Multi-Agent Systems for smart event planning and budget optimization.

---

# 📌 Project Overview

FESTIVA-AI-PLANNER is an intelligent AI-based event management system that helps users plan events efficiently using modern AI technologies.

The system understands user requirements such as:

* Event type
* Budget
* City
* Preferences

and generates:

* Complete event plans
* Budget allocation
* Vendor recommendations
* Event timelines
* Task checklists

The project combines:

* Machine Learning
* Retrieval-Augmented Generation (RAG)
* Large Language Models (LLMs)
* Multi-Agent AI Systems

---

# 🚀 Features

## ✅ AI Event Planner

* Generates complete event plans
* Creates task timelines and schedules
* Suggests required vendor categories
* Personalized planning based on user preferences

## ✅ Budget Optimizer (ML)

* Predicts cost allocation
* Suggests optimal budget distribution
* Uses regression models for budget estimation

## ✅ RAG-based Knowledge Assistant

* Answers event planning questions
* Retrieves information from event guides and blogs
* Context-aware responses using vector search

Example Queries:

* “Best wedding timeline?”
* “How to plan a corporate event?”
* “Budget tips for birthday parties?”

## ✅ Multi-Agent System

The system includes multiple AI agents:

### 🔹 Planner Agent

Creates event schedules and task plans.

### 🔹 Research Agent

Fetches relevant event knowledge using RAG.

### 🔹 Optimizer Agent

Optimizes budget allocation and planning.

---

# 🧠 Technologies Used

| Category             | Technologies             |
| -------------------- | ------------------------ |
| Programming Language | Python                   |
| Backend              | FastAPI                  |
| Machine Learning     | Scikit-learn             |
| Data Processing      | Pandas, NumPy            |
| NLP & LLM            | HuggingFace Transformers |
| Vector Database      | FAISS                    |
| RAG Framework        | LangChain                |
| Frontend             | HTML, CSS, JavaScript    |
| Deployment           | Docker                   |

---

# 🏗️ System Architecture

```text
User Input
   ↓
FastAPI Backend
   ↓
Multi-Agent System
   ├── Planner Agent
   ├── Research Agent (RAG)
   └── Budget Optimizer Agent
   ↓
LLM + ML Processing
   ↓
Generated Event Plan
```

---

# 📂 Project Structure

```text
FESTIVA-AI-PLANNER/
│
├── backend/
│   ├── agents.py
│   ├── database.py
│   ├── main.py
│   ├── ml.py
│   ├── rag.py
│   └── schemas.py
│
├── frontend/
│   ├── index.html
│   └── static/
│       ├── app.js
│       └── styles.css
│
├── data/
├── models/
├── notebooks/
├── requirements.txt
├── Dockerfile
├── README.md
└── .gitignore
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Kpankhuri1711/FESTIVA-AI-PLANNER.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd FESTIVA-AI-PLANNER
```

## 3️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

## Start FastAPI Server

```bash
uvicorn backend.main:app --reload
```

Server will start at:

```text
http://127.0.0.1:8000
```

---

# 📊 Example Input & Output

## User Input

```text
Wedding in Bangalore with budget ₹10 Lakhs
```

## System Output

```text
✔ Complete event timeline
✔ Budget breakdown
✔ Vendor recommendations
✔ Task checklist
✔ Venue suggestions
```

---

# 🤖 AI Components

## 🔹 Machine Learning

* Regression models for budget prediction
* Cost estimation and optimization

## 🔹 NLP

* Event type classification
* User intent understanding

## 🔹 Retrieval-Augmented Generation (RAG)

* Semantic search using FAISS
* Context-aware response generation

## 🔹 Multi-Agent AI

* Planner Agent
* Knowledge Agent
* Budget Optimization Agent

---

# 📈 Future Enhancements

* Vendor recommendation engine
* Real-time booking integrations
* AI chatbot assistant
* Voice-based event planning
* Recommendation system using collaborative filtering
* Mobile application
* Cloud deployment

---

# 🐳 Docker Support

Build Docker Image:

```bash
docker build -t festiva-ai-planner .
```

Run Docker Container:

```bash
docker run -p 8000:8000 festiva-ai-planner
```

---

# 📸 Screenshots

Add your project screenshots here.

Example:

```text
screenshots/homepage.png
screenshots/output.png
```

---

# 🧪 API Testing

FastAPI automatically provides Swagger UI:

```text
http://127.0.0.1:8000/docs
```

---

# 📚 Learning Outcomes

This project demonstrates:

* Machine Learning implementation
* NLP & LLM integration
* RAG architecture
* Multi-Agent orchestration
* FastAPI backend development
* Git & GitHub workflow
* Docker deployment

---

# 👩‍💻 Author

## Komal Pankhuri

AI/ML Enthusiast | Python Developer | Generative AI Learner

GitHub: [https://github.com/Kpankhuri1711](https://github.com/Kpankhuri1711)

---

# ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub
* Share feedback
* Contribute improvements

---

# 📄 License

This project is licensed under the MIT License.
