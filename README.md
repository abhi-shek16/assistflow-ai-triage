# 🤖 AssistFlow AI — Intelligent Ticket Triage System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Groq](https://img.shields.io/badge/Groq-API-orange)
![LLaMA](https://img.shields.io/badge/LLaMA-3.3--70B-purple)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 📌 Problem
FlowBridge Technologies receives **7,000+ support tickets/day**. 
Their keyword-based triage system misroutes tickets and costs 
**$800,000/year** in inefficiency.

## 💡 Solution
An LLM-powered pipeline that reads each ticket and instantly outputs:
- ✅ Issue category
- 🚨 Urgency level (CRITICAL / HIGH / MEDIUM / LOW)
- 💡 Suggested action for the agent
- 🧠 Reasoning behind the decision

## 🔬 Features
| Feature | Description |
|---|---|
| Core Triage Pipeline | Classifies tickets using LLaMA 3.3-70B via Groq API |
| A/B Prompt Testing | Compares two prompts to find the best performing one |
| Drift Detection | Alerts when new ticket trend patterns emerge |
| Model Benchmarking | Speed vs accuracy: LLaMA-70B vs LLaMA-8B |
| Analytics Dashboard | 4 charts visualising triage results |

## 🛠 Tech Stack
Python · Groq API · LLaMA 3.3-70B · Pandas · Matplotlib

## 🚀 How to Run
1. Open `AssistFlow_AI_Triage.ipynb` in Google Colab
2. Get a free API key from [console.groq.com](https://console.groq.com)
3. Add it to Colab Secrets as `GROQ_API_KEY`
4. Run all cells

## 📈 Business Impact
- Resolution time: 48h → 24h
- FCR: 60% → 80%
- Projected savings: ~$800K/year
