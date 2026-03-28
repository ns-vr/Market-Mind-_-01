# Market-Mind-_-01
MarketMind is built using a multi-agent AI architecture designed to convert raw financial data into personalized insights for Indian retail investors. The system consists of five main layers: the User Layer, Frontend Layer, AI Orchestration Layer, AI Agent Layer, and Data Layer.

Users interact with the platform through a web dashboard where they can view market signals, read AI-summarized financial news, analyze their portfolio, and chat with an AI assistant. The frontend sends requests to a Dashboard Orchestrator, which determines which specialized AI agent should handle the task.

A Context Builder enriches each AI request by combining the user’s portfolio data with real-time market signals and relevant news events. This ensures that every AI response is portfolio-aware and personalized.

The platform uses multiple specialized agents, including a Signal Agent for detecting insider trades and market opportunities, a Pattern Agent for identifying technical chart patterns, a News Agent for summarizing financial news, a Chat Agent for portfolio-aware conversations, a Story Agent for tracking evolving market narratives, and a Finance Agent for FIRE planning, tax optimization, and financial health scoring.

These agents use Google Gemini models for analysis and reasoning, while financial data is sourced from NSE market feeds, SEBI disclosures, Economic Times news APIs, and mutual fund data from AMFI. The modular design allows the platform to scale easily by adding new AI agents for additional financial intelligence features.

### AI Financial Intelligence for Indian Investors

MarketMind is an AI-powered financial intelligence platform built for the **ET AI Hackathon 2026**.

It merges two problem statements:

- **PS6 – AI for the Indian Investor**
- **PS8 – AI-Native News Experience**

The platform transforms **raw financial data, news, and signals** into **personalized actionable insights** for retail investors.

---

#  Features

##  Opportunity Radar
Detects high-value signals like:

- Insider trading activity
- Bulk / block deals
- 52-week breakouts
- Corporate filings

The AI ranks opportunities using historical signal success rates.

---

##  Chart Pattern Intelligence
AI detects patterns like:

- Ascending triangles
- Breakouts
- Double bottoms
- Head & Shoulders

Each signal includes:

- Target price
- Stop loss
- Historical success probability

---

##  AI News Feed
Economic Times articles are automatically:

- Summarized
- Sentiment tagged
- Linked to affected stocks
- Filtered for user portfolio relevance

---

##  Market ChatGPT
A portfolio-aware AI assistant that can answer:

Example:

The AI responds using:

- your quantity
- entry price
- P&L
- market conditions

---

##  Money Health Score

A financial wellness score across:

- Emergency Fund
- Insurance
- Investments
- Debt
- Tax Efficiency
- Retirement Planning

---

##  FIRE Planner

Helps users plan Financial Independence.

Includes:

- required retirement corpus
- SIP projections
- milestone roadmap

---

##  Tax Wizard

Compares:

- Old tax regime
- New tax regime

Finds:

- missed deductions
- tax savings opportunities

---

#  Architecture
User
↓
Frontend Dashboard
↓
AI Orchestrator
↓
Specialized AI Agents


Agents:

| Agent | Function |
|------|--------|
Signal Agent | Detect market signals |
Pattern Agent | Identify chart patterns |
News Agent | AI news summarization |
Chat Agent | Portfolio AI assistant |
Finance Agent | FIRE + Tax planning |

---

#  Tech Stack

Frontend

- HTML
- CSS
- JavaScript
- Chart.js

Backend

- Node.js
- Express

AI

- Google Gemini API

Data Sources

- NSE India API
- SEBI disclosures
- Economic Times RSS
- AMFI NAV API

---

#  Installation

Clone the repository
