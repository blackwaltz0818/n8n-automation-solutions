# Multimodal AI Personal Assistant (LINE-Integrated)

## 🚀 Project Overview
A comprehensive AI assistant integrated with LINE, designed to handle multimodal inputs (Text, Voice, and Images). It features automated identity verification, intelligent intent classification, and seamless integration with Google Calendar and Notion.

## ✨ Advanced Features
* **Multimodal Input Processing:** Uses OpenAI's Vision and Whisper models to analyze images and voice messages in real-time.
* **Intelligent Intent Classification:** An AI Agent determines the user's needs, routing queries between personal productivity (Calendar) and language learning (Dictionary).
* **Smart Dictionary & Spell-Check:** Automatically detects misspellings, provides structured definitions, and saves new vocabulary to a Notion database as a "Single Source of Truth."
* **Proactive Calendar Management:** Integrated via MCP (Model Context Protocol) to perform conflict-checking and event synchronization.
* **Security Layer:** Includes a specialized node to verify User Identity, ensuring data privacy for the account owner.

## 🏗️ Technical Workflow
1. **Entry:** Webhook receives LINE events.
2. **Security:** Identity Verification node filters unauthorized users.
3. **Input Adaptation:** Converts voice/images into text-based prompts.
4. **Agentic Logic:** Intent Classifier routes to specialized Agents (Calendar or Dictionary).
5. **Action & Feedback:** Updates Notion/Google Calendar and sends a structured reply back to the user via LINE API.

## 🛠️ Tech Stack
- **n8n:** Orchestration, Agentic Workflows, and Parent-Child logic.
- **AI Models:** GPT-4o (Vision), Whisper (Audio), GPT-4-mini.
- **Integrations:** LINE Messaging API, Notion API, Google Calendar (MCP).
