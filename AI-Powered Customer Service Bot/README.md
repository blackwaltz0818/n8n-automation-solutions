# AI-Powered Customer Service Bot (Line + n8n + Dify)

[![n8n](https://img.shields.io/badge/Workflow-n8n-FF6D5A?style=flat&logo=n8n)](https://n8n.io/)
[![Dify](https://img.shields.io/badge/AI_Orchestration-Dify-00D1B2?style=flat)](https://dify.ai/)
[![Gemini 3](https://img.shields.io/badge/Model-Gemini_3_Flash_Preview-4285F4?style=flat&logo=google-gemini)](https://deepmind.google/technologies/gemini/)

## 🚀 Project Overview
A professional, production-ready AI automation workflow that integrates **Line Messaging API**, **n8n**, and **Dify AI** to provide a seamless customer service experience with long-term memory and advanced reasoning capabilities.

---

## 🌟 Key Features

* **Advanced Reasoning & Thinking**: Powered by **Gemini 3 Flash Preview**, the bot performs internal chain-of-thought reasoning to provide highly accurate and context-aware responses.
* **Long-term Contextual Memory**: 
    * Uses **Google Sheets** as a "Session Map" to persist `conversation_id`.
    * Allows the AI to maintain conversation context across different timeframes for each unique user.
* **RAG (Retrieval-Augmented Generation)**: 
    * Seamlessly integrated with **Dify Knowledge Bases**.
    * Extracts precision data from uploaded product manuals and FAQs to minimize hallucinations.
* **Real-time Business Analytics**: 
    * Every interaction (query, answer, timestamp, token usage) is logged in real-time to Google Sheets.
    * Provides business owners with immediate transparency into customer needs and API costs.
* **Enterprise-Grade Scalability**: 
    * The decoupled architecture allows for easy migration to WhatsApp, Slack, or enterprise web portals.

---

## 🏗️ System Architecture

1.  **User Interface**: Line Messaging API (Webhook).
2.  **Orchestrator**: n8n (Handles logic, state lookup, and formatting).
3.  **AI Engine**: Dify AI (Gemini 3 Flash Preview + RAG).
4.  **Database Layer**: Google Sheets (Session Management & Chat Logs).

---

## 🛠️ Tech Stack

* **Logic Engine**: [n8n](https://n8n.io/)
* **AI Agent Orchestration**: [Dify.ai](https://dify.ai/)
* **LLM**: Google Gemini 3 Flash Preview
* **Messaging Platform**: Line Messaging API
* **Data Persistence**: Google Sheets API

---

## 🏗️ Solution Architecture
![AI-Driven Content Automation Architecture](./AI-Powered%20Customer%20Service%20Bot.png)

---

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
