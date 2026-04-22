# ⚙️ Agent Execution Guide (ADK)

This document provides a detailed guide to configure and run the Agent Development Kit (ADK) project.

## 🚀 Summary

This guide allows you to:

* Configure environment variables
* Install dependencies
* Run the agent via UI, CLI, or scripts

---

## 🛠️ Environment Setup & ADK Installation

Before running the agent, ensure your environment is properly configured.

### 📦 Project Synchronization

Retrieve all required source files and lab resources from the designated **Google Cloud Storage bucket**.

### ⚙️ Environment Variables

Update your system `PATH` to include local binaries:

```bash
export PATH=$PATH:"/home/${USER}/.local/bin"
```

### 🧩 Install Dependencies

Install Google ADK and project requirements:

```bash
python3 -m pip install google-adk -r adk_project/requirements.txt
```

---


> The ADK CLI and UI automatically detect this file.

---

## ▶️ Running the Agent

Once configured, you can run the agent using different methods:

---

### 🌐 A. Web Interface (ADK UI)

Launch the graphical interface:

```bash
adk web
```

---

### 🤖 B. Programmatic Execution

Run the agent as a standalone script:

```bash
python3 app_agent/agent.py
```

---

### 💬 C. Interactive CLI

Start an interactive session:

```bash
adk run my_google_search_agent
```

---

## ⚠️ Troubleshooting

### Common Issues

* **Command not found (`adk`)**

  * Ensure PATH includes `.local/bin`

* **Authentication errors**

  * Verify `.env` variables
  * Confirm Google Cloud credentials

* **Dependency issues**

  * Reinstall requirements:

    ```bash
    pip install -r adk_project/requirements.txt
    ```
