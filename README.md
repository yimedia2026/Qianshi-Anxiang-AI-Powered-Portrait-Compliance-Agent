# Qianshi‑Anxiang‑AI‑Powered‑Portrait‑Compliance‑Agent
AI‑Powered dual‑module agent for portrait licensing quotation assessment and contract risk compliance review. Demo deployed on MiaoDa Agent platform.

## 📌 Project Introduction
This agent is built for portrait licensing business scenarios, contains two core modules:
1. Portrait Licensing Quotation Module: Generate estimated price range according to project parameters.
2. Contract Risk Review Module: Users paste contract plain‑text to identify high‑risk & medium‑risk clauses.

> ⚠️ Disclaimer: Quotation result and contract review report are for pre‑reference only. They cannot replace manual business audit and professional legal advice.

## 🛠️ Tech Stack / Technology Selection
### Base & Deployment Platform
- Low‑code Agent Platform: MiaoDa Agent
- Underlying Large Language Model: Built‑in general‑purpose LLM, no custom fine‑tuning performed
- Hosting & Runtime Environment: Cloud‑hosted web environment provided by MiaoDa platform

### Knowledge & Logic Engine
- Prompt‑driven workflow design
- Private Vector Knowledge Base: Internal knowledge repository for business rules
- Rule‑based risk grading logic embedded within system prompts

### Interaction & Output Technology
- Front‑end Interaction: Native web dialogue interface provided by the agent platform
- Input Method: Plain‑text copy‑paste input; offline document‑file parsing is not supported
- Output Standard: Structured Markdown‑formatted quotation sheet and compliance risk‑assessment report

> 💡 Note: This project has no independently‑developed backend service, self‑managed database or custom‑built front‑end page. The whole solution is delivered and operated based on the low‑code Agent platform.

## ⚙️ Core Implementation
1. Prompt Engineering
    - System Prompt: Built‑in quotation rules, risk grading logic, output constraints and disclaimer.
2. Private Knowledge Base
    - Portrait licensing price baseline knowledge base
    - AI‑portrait contract risk‑judgement rule library
3. Interaction
    - Web dialogue interaction
    - Plain‑text paste input only, **document file parsing is not supported**
    - Structured Markdown output for quotation sheet and risk report

## 🔗 Live Demo URL
[Click here to view Live Demo](https://app-e0tu9gmww6bl.appmiaoda.com/)

## 📁 Project Backup File
Agent backup file：[Website-Qianshi-Anxiang-Agent-Backup.zip](./Website-Qianshi-Anxiang-Agent-Backup.zip)

## 📦 Project Export Archive
`miaoda‑agent‑export‑backup.zip`

Raw exported archive downloaded from MiaoDa Agent platform.
Notice: This file cannot run independently. You need to import it into MiaoDa Agent to load the agent.

## 🧪 Test Cases
Test scripts for quotation evaluation and contract compliance checking.

## 🚀 Future Plan
Cooperate with local media companies in Guizhou to complete real‑world pilot deployment of portrait‑licensing review service.
