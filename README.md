# 5-Day Gen AI Intensive Course with Google

Google × Kaggle | 10 - 14 November 2025

## Overview
This 5-day online course was crafted by Google’s ML researchers and engineers to help developers explore the foundations and practical applications of AI agents. This repository served to save the notebook, course materials and resources for this course. 

Course Goals:
- Understand AI Agent Foundations – Learn the core concepts, structures, and behaviors that define intelligent, autonomous agents.
- Integrate Tools & Interoperability (MCP) – Enable agents to act using external tools, APIs, and the Model Context Protocol for real-time interaction.
- Implement Context & Memory – Build agents that remember and use past information to handle multi-turn, contextual tasks effectively.
- Ensure Agent Quality & Reliability – Apply evaluation, observability, and performance metrics to build dependable AI agents.
- Deploy Production-Ready Agents – Transition from prototypes to scalable, multi-agent systems using deployment best practices and the A2A protocol.

## Agenda
### Day 1 (Introduction to Agents)
Explore the foundational concepts of AI agents, their defining characteristics, and how agentic architectures differ from traditional LLM applications, laying the groundwork for building intelligent, autonomous systems.

Today’s whitepaper introduces **AI agents**, outlining their core capabilities, the importance of Agent Ops for reliability and governance, and the need for interoperability and security through identity and policy constraints. In the codelabs, first AI agent and a multi-agent system are build using the **Agent Development Kit (ADK)** powered by Gemini, enabling real-time Google Search integration and teamwork between specialized agents.

- [Summary podcast](https://www.youtube.com/watch?v=zTxvGzpfF-g) episode for this unit
- Read the [*"Introduction to Agents"* whitepaper](https://www.kaggle.com/whitepaper-introduction-to-agents)
- [Build](Day-1/day-1a-from-prompt-to-action.ipynb) your first agent using Gemini and ADK.
- [Build](Day-1/day-1b-agent-architectures.ipynb) your first multi-agent systems using ADK.

<br>

### Day 2 (Agent Tools & Interoperability with Model Context Protocol (MCP))
Dive into the world of tools, understanding how AI agents can "take action" by leveraging external functionalities and APIs, and explore the ease of discovering and using tools offered by the Model Context Protocol (MCP).

Today’s whitepaper focuses on **external tool functions** that enable agents to perform actions or access **real-time data** beyond their training set. It introduces **best practices** for designing effective tools and explores the **Model Context Protocol (MCP)** — covering its architectural components, communication layer, associated risks, and enterprise readiness gaps.

- [Summary podcast](https://www.youtube.com/watch?v=Cr4NA6rxHAM) episode for this unit
- Read the ["Agent Tools & Interoperability with Model Context Protocol (MCP)" whitepaper](https://www.kaggle.com/whitepaper-agent-tools-and-interoperability-with-mcp)
- [Explore](Day-2/day-2a-agent-tools.ipynb) new ways to add tools to extend what your agents can do.
- [Explore](Day-2/day-2b-agent-tools-best-practices.ipynb) best practices for tools, including using MCP and long-running operations.

<br>

### Day 3: Context Engineering: Sessions & Memory
Explore how to build AI agents that can remember past interactions and maintain context. Learn how to implement short-term and long-term memory to create more robust agents capable of handling complex, multi-turn tasks.

Today’s whitepaper introduces **context engineering**, explaining how to manage an AI’s conversation history and memory to create stateful, personalized interactions. In the codelabs, a stateful agent is built using the Agent Development Kit (ADK), first to handle short-term context within a session, and then to add long-term memory that persists across multiple sessions.

- [Summary podcast](https://www.youtube.com/watch?v=FMcExVE15a4&t=558s) episode for this unit
- Read the ["Context Engineering: Sessions & Memory whitepaper"](https://www.kaggle.com/whitepaper-context-engineering-sessions-and-memory)
- [Build](Day-3/day-3a-agent-sessions.ipynb) stateful agents and perform context engineering
- [Explore](Day-3/day-3b-agent-memory.ipynb) how to use memory with your agent

<br>

### Day 4: Agent Quality
Learn to build robust and reliable AI agents by mastering the critical disciplines of evaluating and improving agents. This session will cover observability, logging, and tracing to provide visibility, alongside key metrics and evaluation strategies to optimize agent performance.

Today’s whitepaper introduces **Observability** as the foundation for assuring AI agent quality, built on three pillars: **Logs** (the diary), **Traces** (the narrative), and **Metrics** (the health report). These enable a continuous feedback loop through scalable evaluation methods like LLM-as-a-Judge and Human-in-the-Loop (HITL). In the codelabs, you’ll learn to use logs, traces, and metrics to gain visibility into your agent’s decision-making, debug failures, and evaluate response quality and tool usage.

- [Summary podcast](https://www.youtube.com/watch?v=LFQRy-Ci-lk) episode for this unit
- Read the [Agent Quality whitepaper](https://www.kaggle.com/whitepaper-agent-quality)
- [Implement](Day-4/day-4a-agent-observability.ipynb) observability to help you debug your agents
- [Evaluate](Day-4/day-4b-agent-evaluation.ipynb) your agents

<br>

### Day 5: Prototype to Production 
Go beyond local testing and learn to deploy and scale AI agents for real-world use. This session will cover the best practices for deploying your agents so that others can use them, including how to create a truly multi-agent system with the Agent2Agent (A2A) Protocol.

<br>

## Resources
[Course Page](https://www.kaggle.com/learn-guide/5-day-agents) \
[Live Stream Recording](https://www.youtube.com/playlist?list=PLqFaTIg4myu9r7uRoNfbJhHUbLp-1t1YE)
