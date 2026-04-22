# Agent Development Kit (ADK) - Google AI Agents Certification

![Google AI Agents Certificate](https://img.shields.io/badge/Google%20AI%20Agents-Certificate-gold) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-Platform-blue) ![Vertex AI](https://img.shields.io/badge/Vertex%20AI-ADK-blue) ![Python](https://img.shields.io/badge/Python-Scripts-green)

This repository contains the implementation of two specialized AI agents developed as part of the **Google AI Agents Certification**. These projects demonstrate the ability to build, configure, and test autonomous agents using the **Agent Development Kit (ADK)**.

### 🎯 Project Goal

The primary objective was to master the ADK lifecycle by creating two distinct agentic workflows:
1.  **Search-Enabled Agent:** An agent capable of utilizing the Google Search tool to retrieve real-time information.
2.  **Decision-Making Agent:** An agent designed to follow a sequence of decisions to solve complex queries.

The project validates the transition from local development to various execution environments including CLI, Browser UI, and programmatic scripts.

### 💡 Key Skills Demonstrated

* **Tool Integration & Search:** Configured agents to autonomously use external tools (Google Search) to augment their knowledge base.
* **Multi-Modal Execution:** Demonstrated proficiency in running and testing agents through three distinct methods:
    * **Browser UI:** Testing interaction via the ADK web interface.
    * **CLI Chat:** Real-time debugging and interaction through the Command Line Interface.
    * **Programmatic:** Executing agent logic directly via Python scripts for automation.
* **ADK Architecture & Structuring:** Implemented standard directory structures required for ADK scalability and deployment.
* **Agent Parameter Tuning:** Configured critical parameters including model selection (Gemini), tool mapping, and system instructions.
* **Output Schema Control:** Managed and constrained agent output schemas to ensure consistent data structures for downstream applications.

### 📁 Files Info:

* **`agents/my_google_search_agent/`** — Implementation of the agent integrated with the Google Search tool for real-time data retrieval.
* **`agents/app_agent/`** — Core logic for the sequential decision-making agent designed for complex reasoning tasks.
* **`Guide.md`** — Comprehensive walkthrough and documentation of the development process and certification milestones.
* **`.env.md`** — Documentation for environment variable requirements, including API keys and Project IDs.

---

## 🛠 Technical Framework
* **Platform:** Google Cloud / Vertex AI
* **Orchestration:** Agent Development Kit (ADK)
* **Models:** Google Gemini Series
* **Interfaces:** CLI, ADK Browser UI, Python SDK
