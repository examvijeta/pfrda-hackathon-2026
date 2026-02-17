# 🤖 NPS Saathi
### AI-Powered Multilingual NPS Assistant

> **PFRDA Innovate4NPS Hackathon 2026** | Problem Statement 4  
> Organized by PFRDA + SIIC IIT Kanpur

---

## 👥 Team
| Name | Role |
|------|------|
| Aman Kumar | Team Lead & Full Stack Developer |
| Rausheen Hasan | UI/UX Designer, Python Developer & Research Analyst |

---

## 📌 Problem Statement
80%+ of NPS queries go unanswered due to limited support capacity. Most NPS communication is English-only — excluding 700M+ vernacular language users. Subscribers cannot get personalized guidance without physically visiting a PoP office.

---

## 💡 Our Solution
**NPS Saathi** is an AI-powered multilingual conversational assistant that provides real-time NPS query resolution, personalized pension guidance, and financial literacy in 10+ regional languages — available 24/7 on any device.

---

## ✨ Key Features
- 💬 Multilingual Chat — text + voice in 10+ regional languages
- 🧠 RAG-Based NLP — responses grounded in official PFRDA documents only
- 👤 Personalized Guidance — context-aware based on age, account type, contribution
- ❓ FAQ Automation — instant answers to 200+ common NPS queries
- 🎙️ Voice Input — Hindi + English voice-to-text via Web Speech API
- 🔔 Contribution Reminders — smart nudges for due dates and milestones
- 🔀 Smart Escalation — unresolved queries routed to correct CRA/PoP with context
- 🔒 DPDP Act 2023 Compliant — explicit consent, no PII in AI model

---

## 🌐 Supported Languages
```
Hindi | English | Tamil | Telugu | Kannada
Marathi | Bengali | Gujarati | Odia | Punjabi | Malayalam
```

---

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React.js — Chat UI + Language Selector |
| Mobile | Flutter |
| Backend | Python FastAPI (NLP + RAG pipeline) |
| Vector DB | ChromaDB / Pinecone (knowledge embeddings) |
| LLM | Gemini 1.5 Flash API |
| Translation | IndicTrans2 / Google Translate API |
| Database | PostgreSQL (sessions + consent logs) |
| Deployment | Docker + APIX Platform |

---

## 🔄 Conversation Flow
```
Step 1 → User opens chat → Language auto-detected or selected
Step 2 → Quick action buttons shown (Balance, Contribution, Withdrawal)
Step 3 → User types/speaks query → Intent classified
Step 4 → RAG retrieves relevant PFRDA documentation
Step 5 → Gemini generates natural response in user's language
Step 6 → If unresolved → Smart escalation to CRA/PoP agent
```

---

## 💬 Sample Interactions
| User Query | Language | NPS Saathi Response |
|-----------|----------|-------------------|
| Mera NPS balance kaise check karein? | Hindi | Step-by-step NSDL/KARVY guide |
| What is a Tier 2 account? | English | Simple explanation + comparison |
| En contribution evvalavu? | Tamil | Personalized contribution summary |
| Kya NPS se paise nikal sakte hain? | Hinglish | Withdrawal rules in simple Hindi |

---

## 🎯 Expected Impact
- ✅ 80%+ NPS queries resolved automatically without human agent
- 🎯 95%+ response accuracy via RAG-grounded answers
- 🌍 800M+ vernacular users reached via 10+ language support
- ⚡ Under 2 seconds response time at scale
- 💰 60% reduction in CRA/PoP human agent query load

---

## 📁 Project Status
> 🚧 Currently in Idea Stage — Prototype to be built on APIX Platform post shortlisting

---

## 📬 Contact
- Aman Kumar — Team Lead
- Rausheen Hasan — UI/UX & Research

*Submitted for PFRDA Innovate4NPS Hackathon 2026*  
*#NPSZaruriHai | #Innovate4NPS | #PFRDA2026*
