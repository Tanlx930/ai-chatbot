# AI Chatbot — Knowledge-Based Conversational Assistant

> A knowledge-base FAQ + menu-driven chatbot built for the Introduction to AI module.

![Python](https://img.shields.io/badge/Language-Python-3776AB?logo=python&logoColor=white)
![AI](https://img.shields.io/badge/Domain-Conversational%20AI-blueviolet)
![License](https://img.shields.io/badge/license-Academic-blue)

---

## Overview

A conversational chatbot designed around a structured **knowledge base** (FAQ + Menu KB). The bot interprets user queries using rule-based natural-language matching, retrieves the most relevant answer from the KB, and presents explainable responses. Designed to demonstrate the foundational AI techniques covered in the IAI module — search, knowledge representation, and reasoning under uncertainty.

---

## Module / Course

- **Module Code:** AAPP002-4-2-IAI
- **Course:** Introduction to Artificial Intelligence
- **Institution:** Asia Pacific University
- **Project Type:** Group Assignment

---

## Key Features

- **FAQ knowledge base** — structured Q&A pairs for common queries.
- **Menu knowledge base** — guided menu/option flows for product browsing.
- **Intent matching** — keyword + similarity-based query interpretation.
- **Explainable responses** — bot states what it understood before answering.
- **Fallback handling** — graceful degradation when no KB match is found.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Python |
| AI Approach | Rule-based + keyword similarity |
| Knowledge Base | Structured documents (FAQ + Menu) |
| Diagrams | draw.io (flowchart, architecture) |

---

## Project Artifacts

| File | Purpose |
|---|---|
| `AI.drawio` / `AI.png` | System architecture diagram |
| `FlowchaRT.drawio` | Conversation flowchart |
| `KB_FAQ.docx` | FAQ knowledge base |
| `KB_MENU.docx` | Menu-driven knowledge base |
| `T-19-10_Report.pdf` | Full project report |
| `T-19-10_Video.mp4` | Demo video |

---

## Conversation Flow

```
User input
   │
   ├─ Tokenize & normalize
   │
   ├─ Match against FAQ KB
   │   ├─ High confidence  → return FAQ answer
   │   └─ Low confidence   → fall through
   │
   ├─ Match against Menu KB
   │   ├─ Match            → return menu option
   │   └─ No match         → fallback prompt
   │
   └─ Log interaction
```

---

## Getting Started

```bash
# 1. Ensure Python 3.x installed
python --version

# 2. Run the chatbot
python chatbot.py
```

> _Replace the entry script name with the actual file from your source._

---

## Screenshots

> _Add chatbot interaction screenshots — example queries and responses._

---

## Documentation

- Full report: `T-19-10_Report.pdf`
- Demo video: `T-19-10_Video.mp4`
- Architecture: `AI.drawio` / `AI.png`

---

## License

Academic project. Source provided for portfolio reference; not for commercial reuse.
