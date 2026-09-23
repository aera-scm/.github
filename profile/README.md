# AERA

**Autonomous Exception Resolution Agent** — agentic AI for supply chain exception handling on AWS and SAP.

A supply chain exception rarely arrives as clean data. It arrives as a supplier email, a PDF confirmation, a photo on WhatsApp, a carrier notice. The authority to fix it, meanwhile, lives inside the ERP. AERA closes that gap: it reads the raw signal, grounds every figure in SAP, works out who is affected and how much is at risk, proposes options, and writes the correction back — automatically when the action is small and reversible, with a named approver when it is not.

| Repository | What it is |
|---|---|
| **aera-be** | Backend, reasoning agent, deterministic control plane, infrastructure, SAP Mirror |
| **aera-fe** | Planner console (React) |

Built for the AWS / SAP Agentic AI Hackathon, track: Intelligent Supply Chain.
