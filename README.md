# Jason Chuang — AI Automation Consultant | n8n · Claude

Most automation projects fail because they automate the wrong process. I'm a CBAP®-certified business analyst with 19 years in enterprise systems (KPMG, a banking platform serving 2M+ users, Mercedes-Benz Financial Services). I diagnose your workflow first, then build the smallest reliable fix with n8n and Claude — sometimes that's an AI agent, sometimes a simple deterministic workflow. I'll tell you which, honestly.

This repository is my automation portfolio: client case studies, production systems, and fully documented workflow builds.

**Try my work live:** [jasonchuang.com](https://jasonchuang.com) — an AI lead qualifier you can test yourself (Next.js · Claude · Supabase · Stripe). BANT scoring with hot / warm / cold routing and human-review gates — the same kind of system I build for clients.

## Client Work

### Company knowledge assistant from 20 years of documents (Claude)

A consulting firm's 20 years of project files (800K tokens) became an assistant their team can question in plain language. Answers cite the exact page, and the system says "no record" instead of guessing — verified with adversarial test questions before the client demo.

### Content automation system for a career consultancy (n8n)

A US semiconductor career consultancy (PhD physicist, ex-AMD/TSMC) was moving content between LINE, Notion, and Threads by hand. I built a 12-task automation system covering the whole path — LINE→Notion capture, AI-drafted posts via API, Threads auto-publishing driven by Notion status, and automated weekly reporting back into Notion — plus the n8n environment it runs on.

> *"He thinks in systems — turns ideas into scalable systems."*
> — the client, in a LinkedIn recommendation

### Lead-intake triage (n8n + Claude)

A UK catering business (via an agency partner) was triaging website-form leads by hand — slow enough to lose customers. I built an n8n + Claude workflow that qualifies each lead and drafts the response automatically, with a human-approval gate before anything reaches the customer. Delivered with test payloads and validated across four routing paths; the client's rollout stalled on their side before go-live.

[Watch the 5-minute walkthrough (Loom)](https://www.loom.com/share/7a518d7d2def405c802838cd039ecab8)

### AI-visibility (GEO) audit: finding the real problem

The same catering client believed their website was invisible to AI assistants (a tool reported 0% visibility). My diagnosis showed their robots.txt wasn't blocking anything — the real gaps were missing schema fields, an outdated address, and absent business metadata. Delivered a prioritized fix list with a competitor comparison instead of an unnecessary rebuild. Agency feedback: *"super useful when pitching."*

### Daily AI content pipeline

Designed, built, and operated an unattended daily pipeline: RSS topic discovery → AI summarization → image generation + text-to-speech → simultaneous publishing to Instagram, Threads, and Facebook. Ran daily in production for three months with error handling and per-platform failure notifications.

## Workflow Deep-Dives

Full architecture documentation and workflow files:

### [AI-Driven Content Automation](./AI-Content-Automation)

A modular system for topic discovery, AI-assisted content generation, and multi-platform publishing.

- **Key design:** decoupled parent-child workflows, so each stage can be tested and maintained independently.
- **Tech:** n8n, OpenAI, Notion.

### [Multimodal AI Personal Assistant](./AI-Personal-Assistant)

A cross-platform AI agent on LINE that centralizes productivity and language learning through voice, image, and text.

- **Key design:** multimodal processing (voice-to-text and OCR) with agentic tool use for calendar orchestration.
- **Tech:** n8n, LINE API, OpenAI (GPT-4o Vision & Whisper), Google Calendar (MCP), Notion.

### [Enterprise AI Customer Service Solution](./AI-Powered%20Customer%20Service%20Bot)

A high-precision AI support system with stateful long-term memory for business-scale interactions.

- **Key design:** external session-map architecture (Google Sheets) for persistent conversation context, plus automated filtering of reasoning-model outputs.
- **Tech:** n8n, Dify AI, Google Gemini (reasoning), Google Sheets API, LINE Messaging API.

## How I Work

1. **Diagnose first.** A free scoping conversation. I'll tell you honestly whether automation makes sense for your case — sometimes the right answer is "don't automate this."
2. **Smallest reliable fix.** Deterministic workflow, AI workflow, or AI agent — matched to the problem, not the hype. You don't pay for complexity you don't need.
3. **Built for handover.** Every build ships with error handling, human-approval gates wherever money or customers are involved, and full documentation (setup guide, node references, test payloads). No black boxes, no disappearing freelancer.

## Stack & Credentials

- **Stack:** n8n (Level 2 certified) · Claude API & Claude Code (Anthropic-certified) · OpenAI · Microsoft Power Automate & M365 (Outlook, SharePoint) · Supabase · REST APIs · SQL
- **Credentials:** CBAP® · PMP® · Salesforce Agentforce Specialist · Azure AI Fundamentals · ServiceNow CSA
- **Background:** 19 years across consulting (KPMG), core-banking system upgrades, and enterprise financial systems; early career in VB.NET/C# development.

## Get in Touch

Based in Taipei (GMT+8) — I overlap with US East Coast mornings, and I deliver overnight: brief me at your end of day, wake up to progress.

- **Website:** [jasonchuang.com](https://jasonchuang.com)
- **Email:** [jason@jasonchuang.com](mailto:jason@jasonchuang.com)
- **LinkedIn:** [Yu-Ta (Jason) Chuang](https://www.linkedin.com/in/yu-ta-chuang-10115a108)
