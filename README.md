<h1 align="center">Hi, I'm Zotriq 👋</h1>
<h3 align="center">AI Automation Engineer · RAG &amp; LLM Agents · Full-Stack Developer</h3>

<p align="center">
<a href="https://zotriq.github.io"><b>🌐 zotriq.github.io: portfolio website</b></a> ·
<a href="https://zotriq-demos.streamlit.app"><b>▶ Live demos: try my projects in the browser</b></a>
</p>

<p align="center">
I build AI systems that do real work for businesses: lead-qualification workflows, document chatbots,
research agents and the web apps around them.
</p>

---

### 🚀 What I do

- **Voice & chat agents:** phone receptionists (Vapi, ElevenLabs) and WhatsApp assistants that book appointments and hand off to staff
- **AI automation:** n8n workflows with Claude and other LLMs, human-in-the-loop approvals, CRM and email integrations (HubSpot, Slack, Gmail, Close CRM)
- **RAG and chatbots:** answers grounded in your own PDFs, websites and knowledge bases, with citations (pgvector, Pinecone, Chroma)
- **LLM agents:** ReAct and multi-agent pipelines with LangChain and LangGraph, tool use, memory and MCP servers
- **Data engineering:** ETL pipelines, PostgreSQL performance tuning, multi-tenant pgvector, document extraction (OCR + LLM)
- **Machine learning:** classifiers, computer vision (YOLOv8) and the data pipelines that feed them
- **Full-stack apps:** Next.js and React front ends with FastAPI, Flask or .NET back ends

### ⭐ Featured projects

Every project below can be tried live, running the real code from its repository.

| Project | What it does | Stack | Live demo |
|---|---|---|---|
| [**n8n-claude-lead-qualifier**](https://github.com/Zotriq/n8n-claude-lead-qualifier) | Scores inbound leads 0–100 with Claude, drafts a reply, waits for Slack approval, then updates HubSpot and sends it via Gmail | n8n · Claude · Slack · HubSpot | [▶ Try it](https://zotriq-demos.streamlit.app/n8n-lead-qualifier) |
| [**ai-lead-qualification-agent**](https://github.com/Zotriq/ai-lead-qualification-agent) | Full lead-qualification system: rules + GPT scoring, AI-drafted follow-ups with human approval, a sales dashboard, and HubSpot, Slack and n8n integrations | FastAPI · Next.js · PostgreSQL · Docker | [▶ Try it](https://zotriq-demos.streamlit.app/lead-qualifier) |
| [**voice-ai-receptionist**](https://github.com/Zotriq/voice-ai-receptionist) | AI phone receptionist for a dental clinic: books, finds and cancels appointments from the real schedule, transfers to staff, logs every call | Vapi · FastAPI · ElevenLabs · SQLite | [▶ Try it](https://zotriq-demos.streamlit.app/voice-receptionist) |
| [**whatsapp-ai-agent**](https://github.com/Zotriq/whatsapp-ai-agent) | WhatsApp assistant on the official Cloud API: answers in English/Urdu, books appointments with tool calling, hands off to staff | WhatsApp API · OpenAI · FastAPI | [▶ Try it](https://zotriq-demos.streamlit.app/whatsapp-agent) |
| [**langgraph-support-agents**](https://github.com/Zotriq/langgraph-support-agents) | Multi-agent support team: supervisor routing, billing/tech/sales specialists, QA review loop, human approval that survives restarts | LangGraph · Python · SQLite checkpoints | [▶ Try it](https://zotriq-demos.streamlit.app/support-agents) |
| [**pdf-rag-knowledge-assistant**](https://github.com/Zotriq/pdf-rag-knowledge-assistant) | RAG API that answers questions from your PDFs with citations, with OpenAI or Anthropic models | FastAPI · LangChain · pgvector · Docker | [▶ Try it](https://zotriq-demos.streamlit.app/pdf-rag) |
| [**multitenant-rag-saas**](https://github.com/Zotriq/multitenant-rag-saas) | Chat-with-your-docs SaaS backend where PostgreSQL row-level security keeps every company's data isolated | pgvector · RLS · FastAPI | [▶ Try it](https://zotriq-demos.streamlit.app/multitenant-rag) |
| [**stripe-crm-automation**](https://github.com/Zotriq/stripe-crm-automation) | Stripe payments to HubSpot, emails and Slack, with verified webhooks, idempotency and a retry outbox | Stripe · HubSpot · Python | [▶ Try it](https://zotriq-demos.streamlit.app/stripe-crm) |
| [**n8n-meeting-notes-to-clickup**](https://github.com/Zotriq/n8n-meeting-notes-to-clickup) | Meeting transcript or recording to AI summary, assigned ClickUp tasks and a Slack recap | n8n · Whisper · GPT · ClickUp | [▶ Try it](https://zotriq-demos.streamlit.app/meeting-notes) |
| [**invoice-extraction-pipeline**](https://github.com/Zotriq/invoice-extraction-pipeline) | Invoice PDFs and scans to structured data with OCR + LLM extraction, accounting checks, and Excel/Sheets export | Tesseract · OpenAI · Claude · FastAPI | [▶ Try it](https://zotriq-demos.streamlit.app/invoice-extraction) |
| [**postgres-mcp-server**](https://github.com/Zotriq/postgres-mcp-server) | Lets AI assistants query PostgreSQL in plain English, with a SQL safety guard and read-only sessions | MCP · PostgreSQL · sqlglot | [▶ Try it](https://zotriq-demos.streamlit.app/postgres-mcp) |
| [**postgres-performance-tuning**](https://github.com/Zotriq/postgres-performance-tuning) | Six real slow queries fixed with measured results (22x–460x faster on 2M orders) | PostgreSQL · EXPLAIN ANALYZE | [▶ Try it](https://zotriq-demos.streamlit.app/postgres-tuning) |
| [**sql-etl-pipeline**](https://github.com/Zotriq/sql-etl-pipeline) | Merges messy CSV exports and a live FX API into clean, deduplicated PostgreSQL tables with an audit log | Python · SQLAlchemy · PostgreSQL · Docker | [▶ Try it](https://zotriq-demos.streamlit.app/etl-pipeline) |
| [**SpecForge**](https://github.com/Zotriq/SpecForge) | Multi-agent MCP server that turns a one-line feature request into a plan and a full spec | LangGraph · FastMCP · Pydantic | [▶ Try it](https://zotriq-demos.streamlit.app/specforge) |
| [**research-agent**](https://github.com/Zotriq/research-agent) | Autonomous ReAct agent that searches the web and local files, with a live streaming chat UI | Python · Groq · FastAPI · Next.js | [▶ Try it](https://zotriq-demos.streamlit.app/research-agent) |
| [**hydra-rag**](https://github.com/ahmedjavedcodes/hydra-rag) | Chat with PDFs, Word, PowerPoint, Excel, images and web pages, with cited answers (built with Ahmed Javed) | LangChain · Pinecone · Groq | [▶ Try it](https://zotriq-demos.streamlit.app/hydra-rag) |
| [**Digisinc-chatbot**](https://github.com/Zotriq/Digisinc-chatbot) | Customer-support chatbot for an agency website, answering from the company's own documents | FastAPI · Pinecone · Groq · Docker | [▶ Try it](https://digisinc.systems/chat) |
| [**AI-vehicle-analysis**](https://github.com/Zotriq/AI-vehicle-analysis) | Turns raw vehicle work-order history into a maintenance report from a plain-English question | FastAPI · LangChain · Groq | [▶ Try it](https://zotriq-demos.streamlit.app/vehicle-analysis) |
| [**dietary-estimation-system**](https://github.com/Zotriq/dietary-estimation-system) | Estimates calories, protein and fat from a photo of a meal | YOLOv8 · scikit-learn · FastAPI · React | [▶ Try it](https://zotriq-dietary.streamlit.app/) |
| [**ai-phishing-detector**](https://github.com/Zotriq/ai-phishing-detector) | Flags phishing URLs and scam emails with two ML models | scikit-learn · NLP · Streamlit | [▶ Try it](https://zotriq-demos.streamlit.app/phishing-detector) |
| [**enterprise-pos**](https://github.com/Zotriq/enterprise-pos) | Point-of-sale and inventory system for retail stores | React · Tailwind CSS | [▶ Try it](https://zotriq.github.io/enterprise-pos/) |

### 🛠️ Tech stack

**AI and data**<br>
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)

**Back end**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Front end and mobile**<br>
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

### 🌐 Websites I've built

- **Autonomous Fleet Management SaaS** · [live](https://fleet-inky.vercel.app): fleet platform with AI agents for triage, Q&A and logistics (built with Ahmed Javed)

- [**fynrose**](https://github.com/Zotriq/fynrose) · [live](https://fynrose.shop): animated product site for a herbal skincare brand (Next.js, GSAP)
- [**eatddelight_frontend**](https://github.com/Zotriq/eatddelight_frontend) · [live](https://eatddelight.com): online menu and WhatsApp ordering for a home-kitchen food business (Next.js, Zustand)
- [**Digisinc-website**](https://github.com/Zotriq/Digisinc-website) · [live](https://digisinc.systems/): website for a digital marketing agency (React, Framer Motion)

---

<p align="center"><i>Open to freelance work on AI automation, RAG chatbots and agent projects.</i></p>
