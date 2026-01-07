# Aarya Sutar

B.Tech student at National Institute of Technology Tiruchirappalli. I build production-ready LLM systems and practical full-stack tools. Experienced in shipping a RAG-powered Oracle EBS support chatbot, engineering PDF and ticket ingestion pipelines, and building workflow tooling that converts Excel maps and plain-language edits into draw.io diagrams. I work in Python and Java and focus on turning prototypes into reliable, API-driven systems.

## Quick facts

- 📍 NIT Tiruchirappalli, Metallurgical & Materials Engineering
- 💼 AI/ML Intern @ Birlasoft — built a RAG-powered Oracle EBS support chatbot, PDF and ticket ingestion, and a draw.io workflow generator driven by Excel maps and natural-language edits
- 🛠 **Primary:** Python, Java, Flask, FastAPI, Docker, SQL, prompt engineering, vector-store retrieval, embeddings, REST APIs
- 📫 **Email:** [sutaraarya5@gmail.com](mailto:sutaraarya5@gmail.com)
- 🔗 **LinkedIn:** [linkedin.com/in/aarya-sutar](https://linkedin.com/in/aaryasutar03)
- 📌 **GitHub username:** `Aarya-Sutar` 

## What I do

I am a B.Tech student learning AI and machine learning while building small, practical systems that actually work. I know front end development, Flask, Python, Java and OOP, and I focus on applying that knowledge to chatbots and simple full stack tools rather than abstract research.
- Currently learning and practicing: retrieval augmented generation, prompt engineering, document and ticket ingestion, and deploying model-backed APIs.
- Building: the Aurenia chatbot (RAG pipeline, PDF and ticket ingestion, relevance filtering) and a few front-end and Flask projects to sharpen full stack skills.
- How I work: prototype fast, iterate with tests and simple deployments, document what I build so others can run it. I prefer solving concrete problems over perfect theory.
- Looking for: internships and real projects where I can learn production practices, improve engineering discipline, and ship features that users can actually use.

If your project needs someone who can bridge ML models and production engineering, I deliver results.

## Featured projects

### Aurenia Chatbot — RAG-based Oracle EBS support assistant

**Repo:** [Aurenia-Chatbot](https://github.com/Aarya-Sutar/Aurenia-Chatbot) (or aurenia-chatbot)

- RAG pipeline ingesting PDFs and ticket histories into a vector store
- Domain-filtering and out-of-scope detection so the bot avoids hallucinations on non-EBS questions
- FastAPI backend, embeddings, and vector retrieval with context windows and relevance filtering
- Production considerations: batching, metadata-aware search, fallback responses

**Why it matters:** Helps users get faster and more reliable answers from technical documents and support history, instead of manually searching through files.
### Flask-Blog

**Repo:** [Flask-Blog](https://github.com/Aarya-Sutar/Flask-Blog)

- Full-stack Flask app with authentication, CRUD, pagination, profile management, and secure password reset via email
- Good example of clean project structure, basic deployment steps, and README-driven onboarding

### Other small projects

- **[Simon-Game](https://github.com/Aarya-Sutar/Simon-Game)** — interactive JS memory game, clean front-end demo
- **[ToDo](https://github.com/Aarya-Sutar/ToDo)** — simple task manager showing UI + persistence basics
- **[Dice-Challenge](https://github.com/Aarya-Sutar/Dice-Challenge)** — JS game demonstrating DOM manipulation and game logic

## Tech stack & tools

- **Languages:** Python, Java, JavaScript, SQL
- **Modeling & ML:** prompt engineering, embeddings, vector stores, transformers, fine-tuning basics
- **Web & APIs:** Flask, FastAPI, REST, OAuth basics
- **Infra & deployment:** Docker, CI automation, simple cloud deployment patterns
- **Data:** PDF parsing, CSV/Excel ingestion, metadata extraction, ticket system integration

## How to run my main repos

Clone and inspect the repo README for full steps. Typical workflow:

```bash
# clone
git clone https://github.com/Aarya-Sutar/aurenia-chatbot.git
cd aurenia-chatbot

# create venv and install
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

# set env (example)
export VECTOR_STORE_PATH=./data/vectors
export OPENAI_API_KEY=sk_xxx

# run dev server
uvicorn app.main:app --reload
```

Each repo has a full README with endpoints, expected env vars, and demo data.

## What I am working on

- Hardening the Aurenia Chatbot for multi-tenant usage and better access controls
- Automating ingestion pipelines to handle noisy enterprise PDFs and email/ticket exports
- Learning production ML ops patterns: monitoring, model versioning, and cost-aware serving

## How to collaborate

- Star or fork the repos you find useful
- Open issues for bugs or feature requests — I respond faster to concrete, reproducible reports
- Want me to contribute? Send a short PR or an issue explaining the goal and I will review it

## If you want to work together

I take internships and freelance work related to AI/ML systems and frontend/backend engineering. If you need production-ready AI tooling and clean engineering, email me at [sutaraarya5@gmail.com](mailto:sutaraarya5@gmail.com) or message on [LinkedIn](https://linkedin.com/in/aaryasutar03).
