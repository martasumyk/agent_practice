# Agentic AI Practice

A collection of hands-on notebooks and projects exploring **function calling**, **AI agents**, **multi-agent systems**, and **Model Context Protocol (MCP)**.

## Contents

### 01 — Function Calling

| Notebook | Description |
|---|---|
| [01-Agentic_AI_OpenAI_Eng.ipynb](01-Function_Calling/01-Agentic_AI_OpenAI_Eng.ipynb) | End-to-end agentic AI with OpenAI: function calling, parallel tool calls, agentic loops, structured outputs, Agents SDK, multi-agent handoffs, guardrails, shared context, and tracing |
| [02-Function_Calling_Eng.ipynb](01-Function_Calling/02-Function_Calling_Eng.ipynb) | Function calling fundamentals — open-source (Mistral) vs proprietary (OpenAI) approaches |
| [03-Function_Calling_Ukr_Lapa.ipynb](01-Function_Calling/03-Function_Calling_Ukr_Lapa.ipynb) | Function calling walkthrough (Ukrainian) |

### 02 — Agents

| Project | Description |
|---|---|
| [anthropic_cu/](02-Agents/01-Computer-Use-Agents/anthropic_cu/) | Computer-use agent using Anthropic's Claude — takes a task description and autonomously performs screen actions with step-by-step traces |
| [ui-tars/](02-Agents/01-Computer-Use-Agents/ui-tars/) | Computer-use agent using UI-TARS 1.5 (open-source, Qwen-based) — same autonomous screen interaction, self-hosted via HuggingFace |
| [02-Multi-Agent-Systems.ipynb](02-Agents/02-Multi-Agent-Systems.ipynb) | Multi-agent system with a manager agent that delegates to specialized sub-agents (web search, summarization) using smolagents |
| [03_Agentic_RAG.ipynb](02-Agents/03_Agentic_RAG.ipynb) | Agentic RAG pipeline: planner → research → answer → judge agents over AG News and SQuAD knowledge bases with self-correction |

### 03 — Model Context Protocol

| Project | Description |
|---|---|
| [MCP Setup Guide](03-Model-Context-Protocol/README.md) | Connect the Filesystem MCP server to Claude Desktop on macOS — enables Claude to read/write local files |

## Quick Start

```bash
git clone https://github.com/oleksa-kosovan/agent_practice.git
cd agent_practice
pip install -r requirements.txt
```

Set your API keys:
```bash
export OPENAI_API_KEY="your_key"
export ANTHROPIC_API_KEY="your_key"  # for computer-use agents
```

Open any notebook in Jupyter or Colab and run the cells.
