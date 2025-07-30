---

## 🚀 Launch in Binder

Try the notebook directly in your browser with zero setup:

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rajsiddarth/ReAct-Agent-with-LangGraph-OpenAI-Tavily)

> ⚠️ Note: Binder does **not support secrets** like `.env` securely. Use demo keys only or disable tools that require authentication.


# ReAct-Agent-with-LangGraph-OpenAI-Tavily

This project demonstrates a stateful AI agent using [LangGraph](https://github.com/langchain-ai/langgraph) and [LangChain](https://www.langchain.com/).  

The agent uses an LLM to reason and call [Tavily Search](https://www.tavily.com/) via `TavilySearchResults`, a tool that performs real-time web search and returns rich results in a ReAct-style loop.

---

## 📌 Features

- OpenAI-powered conversational agent
- Supports search tool use via `tool_calls`
- Uses LangGraph’s state machine to manage multi-step workflows
- ReAct-style reasoning loop: Thought → Action → Observation → Answer
- Accepts a `system` prompt at initialization to control agent behavior
- Can integrate real-time tools like `TavilySearchResults`
-  Automatically retries or handles unknown tools gracefully
  

---


