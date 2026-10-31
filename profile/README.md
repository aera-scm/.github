# AERA

**Autonomous Exception Resolution Agent** — agentic AI for supply chain exception handling on AWS and SAP.

🏆 **1st place — AWS / SAP Agentic AI Hackathon, Asia Pacific 2026** (Intelligent Supply Chain track) · 640 entries → 40 finalists → 1 winner

A supply chain exception rarely arrives as clean data. It arrives as a supplier email, a PDF confirmation, a photo on WhatsApp, a carrier notice. The authority to fix it, meanwhile, lives inside the ERP. AERA closes that gap: it reads the raw signal, grounds every figure in SAP, works out who is affected and how much is at risk, proposes options, and writes the correction back — automatically when the action is small and reversible, with a named approver when it is not. The language model proposes; deterministic code verifies, routes and writes.

[![AERA overview board](https://github.com/aera-scm/aera-be/raw/main/docs/images/overview-board.png)](https://github.com/aera-scm/aera-be#demo)

| Repository | What it is |
|---|---|
| [**aera-be**](https://github.com/aera-scm/aera-be) | Backend, reasoning agent (Strands on Amazon Bedrock AgentCore), deterministic control plane, AWS CDK infrastructure, SAP Mirror, evaluation harness — **start here**, with the demo video |
| [**aera-fe**](https://github.com/aera-scm/aera-fe) | Planner console (React, TypeScript, Cloudscape) |

**Read more:** [How it works](https://github.com/aera-scm/aera-be/blob/main/docs/HOW_IT_WORKS.md) · [Architecture](https://github.com/aera-scm/aera-be/blob/main/docs/ARCHITECTURE.md) · [Safety and governance](https://github.com/aera-scm/aera-be/blob/main/docs/GOVERNANCE.md)
