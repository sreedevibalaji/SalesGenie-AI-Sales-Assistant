# SalesGenie-AI-Sales-Assistant
AI-powered multi-agent sales assistant for lead processing, CRM automation, and weekly sales intelligence.
## AI-Powered Sales Lead Processing & Weekly Sales Intelligence

SalesGenie is an AI-powered multi-agent sales assistant designed for **Oak & Ember Interiors**, a nationwide home and office furniture retailer.

The solution automates inbound sales lead processing, qualification, product recommendation, response drafting, CRM structuring, and weekly sales intelligence.

The goal is not simply to automate tasks with AI, but to build a **grounded, evaluated, observable, and trustworthy AI product**.

---

## 🎯 Business Problem

Sales representatives currently spend significant time manually processing inbound customer inquiries.

Key challenges include:

- 2–3 hours/day spent reading and processing inquiry emails
- Manual entry of leads into Excel/CRM
- Missing or inconsistent customer information
- Inconsistent lead qualification
- Manual product matching
- Delayed customer responses
- Delayed CRM updates
- Manual preparation of weekly sales insights

These challenges reduce selling time and create opportunities for data quality and decision-making errors.

---

## 💡 Solution

SalesGenie uses a **multi-agent AI architecture** to support the complete lead-processing lifecycle.

### Workflow 1 — Lead Processing

```text
Inbound Customer Email
        ↓
Email Ingestion Agent
        ↓
Lead Qualifier Agent
        ↓
Product Recommender Agent
        ↓
Response Drafter Agent
        ↓
CRM Update Agent
        ↓
Deterministic Rule Enforcement
        ↓
CRM-Ready Lead Record

### Workflow 2 — Weekly Sales Insight

CRM Records
     ↓
Filter Weekly Records
     ↓
Aggregate Weekly Metrics
     ↓
Weekly Sales Insight Agent
     ↓
LLM-as-Judge
     ↓
Evaluated Weekly Sales Insights

## 📁 Repository Structure

| Folder / File | What you'll find |
|---|---|
| `Ideation/` | BRD, PRD, Cost Estimation|
| `Design/` | Architecture Diagram, AI agents System prompts, Experiements |
| `System/` | n8n workflow JSON exports |
| `evidence/` | Screenshots, traces, and evaluation evidence |
| `evaluation/` | Test data, evaluation results, and experiment logs |
| `Demo Recordings/` | 5 mins Demo recording |
| `src/` | Custom JavaScript and deterministic business logic |
| `.gitignore` | Files excluded from GitHub |
| `README.md` | Project overview and documentation |

