---
layout: default
title: Projects
---

[← Back to Home](./index.html)

# My Projects

Here is a list of some of the projects I've worked on:

## Lambda: A Minimal Yet Powerful Coding Agent

[![GitHub stars](https://img.shields.io/github/stars/ayusrjn/lambda?style=social)](https://github.com/ayusrjn/lambda) ⭐ Star it on GitHub!

A minimal coding agent that can build different kinds of apps. Lambda uses intelligent context management with a tiered sliding window approach, memory systems, and sub-agents to handle larger tasks without breaking the context window.

- **Technologies:** Python, LLM API, Context Management
- **Key Features:** 
  - Long-term and short-term memory system
  - Tiered sliding window for context protection
  - Sub-agent architecture for task isolation
  - Efficient grep-powered code search
- **Install:** `pip install lambda-agent`
- [View on GitHub](https://github.com/ayusrjn/lambda) | [Read the Article](./general/2026/04/12/designing-lambda-a-minimal-yet-powerful-coding-agent.html)

---

## Zomato Live Support Agent

[![GitHub](https://img.shields.io/badge/GitHub-View%20Code-blue?logo=github)](https://github.com/ayusrjn/voice-server-agent) ⭐ Star it on GitHub!

A real-time voice AI agent for Zomato customer support. Talk to an AI directly from your browser—no waiting, no hold music. The agent can pull up orders, process refunds, and file complaints while you're on the call.

- **Technologies:** Next.js 16, React 19, FastAPI, Google Gemini Multimodal Live API, MongoDB, WebSocket
- **Key Features:**
  - Real-time voice conversation via Web Audio API
  - Function calling with database operations
  - Audio streaming both ways
  - Deployed on Vercel (frontend) and Google Cloud Run (backend)
- [View on GitHub](https://github.com/ayusrjn/voice-server-agent) | [Read the Article](./general/2026/04/14/zomato-live-support-agent.html)

---

## Moderated Multi-Agent Discussion System

[![GitHub](https://img.shields.io/badge/GitHub-View%20Code-blue?logo=github)](https://github.com/ayusrjn/moderated-discussion-system) ⭐ Star it on GitHub!

A framework for controlled, epistemic interaction between autonomous LLM agents and a human moderator. Orchestrate structured debates between two AI agents (powered by Google Gemini) under strict supervision with explicit turn-taking and role adherence.

- **Technologies:** Python, Google Gemini API, CLI
- **Key Features:**
  - Triadic architecture (Discussion Controller, Hard-Contract Agents, Moderator Interface)
  - Explicit turn control and phase-based discussion (Introduction, Argumentation, Synthesis)
  - Active intervention commands (PAUSE, REPHRASE, EVIDENCE, INTERJECT)
  - Research-oriented for studying multi-agent orchestration and epistemic rigor
  - Human-in-the-loop moderation to prevent hallucination and topic drift
- **Install:** `pip install -r requirements.txt` and set `GOOGLE_API_KEY`
- [View on GitHub](https://github.com/ayusrjn/moderated-discussion-system)

---