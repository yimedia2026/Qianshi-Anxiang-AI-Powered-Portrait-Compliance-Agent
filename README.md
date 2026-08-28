# Qianshi-Anxiang-AI-Powered-Portrait-Compliance-Agent
AI‑Powered dual‑module agent for portrait licensing quotation assessment and contract risk compliance review. Demo deployed on MiaoDa Agent platform. Tag: #Guikesong

## 📌 Project Introduction
This agent is built for portrait licensing business scenarios, contains two core modules:
1. Portrait Licensing Quotation Module: Generate estimated price range according to project parameters.
2. Contract Risk Review Module: Users paste contract plain‑text to identify high‑risk & medium‑risk clauses.

> ⚠️ Disclaimer: Quotation result and contract review report are for pre‑reference only. They cannot replace manual business audit and professional legal advice.

## 🛠️ Tech Stack / Technology Selection
### Base & Deployment Platform
- Agent Platform: MiaoDa Agent
- Underlying LLM: Built‑in large language model, no fine‑tuning.

### Core Implementation
1. Prompt Engineering
    - System Prompt: Built‑in quotation rules, risk grading logic, output constraints and disclaimer.
2. Private Knowledge Base
    - Portrait licensing price baseline knowledge base
    - AI‑portrait contract risk‑judgement rule library
3. Interaction
    - Web dialogue interaction
    - Plain‑text paste input only, **document file parsing is not supported**
    - Structured Markdown output for quotation sheet and risk report

> 💡 Note: This project has no independent backend service, database or front‑end page. It is delivered based on low‑code Agent platform.

## 🔗 Live Demo URL
[Paste‑your‑MiaoDa‑Agent‑Demo‑Link‑Here](https://app-e0tu9gmww6bl.appmiaoda.com/)

## 📦 Project Export Archive
`miaoda‑agent‑export‑backup.zip`
Raw exported archive downloaded from MiaoDa Agent platform.
Notice: This file cannot run independently. You need import it into MiaoDa Agent to load the agent.

## 🧪 Test Cases
Test scripts for quotation evaluation and contract compliance checking.

## 🚀 Future Plan
Cooperate with local media companies in Guizhou to complete real‑world pilot deployment of portrait‑licensing review service.

Tag: #Guikesong
