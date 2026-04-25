# Jose Antonio Morillo Sierra

**Full-Stack Developer · AI & Automation Engineer · Fintech Systems**

📍 Caracas, Venezuela · Available for remote work globally  
✉️ josemorillo702@gmail.com · [LinkedIn](https://www.linkedin.com/in/jose-a-morillo/)

---

## What I build

I design and ship full-stack systems that automate complex, manual business processes — with a focus on AI integration and fintech.

My current work: I architected and deployed an **end-to-end lending platform** from scratch as the sole technical hire at a regulated Venezuelan microfinance company. The platform covers the full loan lifecycle — application intake, multi-role risk review, disbursement, real-time payment verification against banking APIs, AI-powered document processing, and automated delinquency monitoring — serving 500+ applicants and 15+ internal staff.

---

## Core stack

**AI & Automation**  
`n8n` · `MCP server development` · `Claude AI / Anthropic API` · `LLM integration` · `WATI WhatsApp API`

**Backend**  
`Python` · `FastAPI` · `SQLAlchemy` · `JWT / RBAC` · `REST API design`

**Frontend**  
`React.js` · `JavaScript (ES6+)` · `Framer`

**Database**  
`PostgreSQL`

**Infrastructure**  
`VPS deployment` · `Server configuration` · `Production environment management`

---

## What I've shipped

### 🏦 Fintech Loan Lifecycle Platform *(Production — Private)*
Full-stack lending platform built on React + FastAPI + PostgreSQL. Multi-role workflow: applicants submit → risk department reviews → administration disburses. JWT-based auth with RBAC enforcing permission boundaries across three user tiers. Integrated with Loandisk API for real-time loan management sync.

**Stack:** React · FastAPI · PostgreSQL · SQLAlchemy · JWT/RBAC · Loandisk API · VPS

---

### 🤖 Claude AI ↔ Loandisk MCP Server *(Production — Private)*
Custom MCP (Model Context Protocol) server that connects Claude AI directly to a loan management system. Enables internal staff to query loan portfolios, check borrower status, and manage records through natural language — no dashboard required.

**Stack:** Python · MCP Protocol · Anthropic API · Loandisk REST API

---

### 📄 AI Document Processing Pipeline *(Production — Private)*
n8n-based automation pipeline: when applicants upload KYC and loan documents, an AI agent extracts structured borrower data and writes it directly to the database. Eliminated manual data entry for the operations team.

**Stack:** n8n · AI agent · PostgreSQL · REST API

---

### 💳 Real-Time Bank Payment Verification *(Production — Private)*
Integration with BNC (Banco Nacional de Crédito) payment API. Borrowers self-report payments through the platform → API validates against the bank in real time → Loandisk status updates automatically. Eliminated manual bank reconciliation entirely.

**Stack:** Python · FastAPI · BNC API · Loandisk API

---

### 📲 WhatsApp AI Chatbot + Delinquency Monitoring *(Production — Private)*
Two-part automation: (1) conversational AI chatbot on WhatsApp that handles company FAQs and borrower payment reports; (2) automated system that segments the entire loan portfolio by overdue bucket (1–30, 30–90, 90–180, 180+ days) and triggers templated collection messages.

**Stack:** n8n · WATI WhatsApp API · Python

---

### 🌐 Capital Invicto — Marketing Website *(Live)*
Public-facing marketing website for the lending product.  
🔗 [capitalinvicto.com](http://capitalinvicto.com/)

**Stack:** Framer

---

## Currently working on

Publishing a public MCP server demo — a clean, documented example of connecting Claude AI to an external REST API. Coming soon.

---

## Languages

🇻🇪 Spanish — Native  
🇺🇸 English — C2 Proficient *(Kaplan International Languages, Boston 2017–2019)*

---

*Most of my production work is private (company systems). The architecture, integrations, and design decisions behind each project above are things I'm happy to walk through in detail — just reach out.*
