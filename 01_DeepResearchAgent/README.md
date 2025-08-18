# DeepSearchAgent

> **An AI-powered research assistant built with the OpenAI Agents SDK.**
> Helps break down complex queries, search the web, validate sources, and generate professional research reports.

---

## 📌 Project Overview

DeepSearchAgent is a **multi-agent system** designed to:

* Plan and decompose research queries into smaller tasks.
* Search across multiple sources with fact-checking.
* Synthesize findings into structured knowledge.
* Generate professional reports with traceable steps.

The project is developed as part of **Panaversity’s OpenAI Agents SDK course**.

---

## ⚙️ Features (Planned by Phases)

* **Phase 1: Foundation** – Core agent, simple research loop, OpenAI tracing.
* **Phase 2: Multi-Agent** – Specialized agents (planner, researcher, synthesizer).
* **Phase 3: Smart Enhancements** – Source validation, caching, structured outputs.
* **Phase 4: Pro Features** – Report generator, examples, polished UI/demo.

---

## 📂 Project Structure

```
DeepSearchAgent/
├── pyproject.toml
├── README.md
├── src/
│   └── deepsearchagent/
│       ├── deep_research_system.py
│       ├── research_agents.py
│       ├── planning_agent.py
│       ├── synthesis_agent.py
│       ├── report_writer.py
│       ├── utils/
│       │   ├── search_tools.py
│       │   └── cache_manager.py
│       └── examples/
│           ├── sample_output.md
│           └── demo_script.py
└── tests/
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/DeepSearchAgent.git
cd DeepSearchAgent
```

### 2️⃣ Install Dependencies (via `uv`)

```bash
uv sync
```

### 3️⃣ Run Example Demo

```bash
uv run python src/deepsearchagent/examples/demo_script.py
```

---

## 🔑 Environment Setup

Create a `.env` file (or use secrets manager) with your API keys:

```
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_key   # if using Tavily for search
```

*(see `.env.example` for template)*

---

## 📊 Progress Tracking

| Phase              | Status    | Notes                              |
| ------------------ | --------- | ---------------------------------- |
| Foundation         | ⬜ Pending | Setup single-agent loop            |
| Multi-Agent        | ⬜ Pending | Planner + Researcher + Synthesizer |
| Smart Enhancements | ⬜ Pending | Validation + caching               |
| Pro Features       | ⬜ Pending | Report generator + showcase        |

---

## 🧪 Testing

Run all tests:

```bash
uv run pytest
```

---

## 📜 License

MIT License – free to use, modify, and share.
