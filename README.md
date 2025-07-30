# ReAct-Agent-with-LangGraph-OpenAI-Tavily

This project demonstrates a stateful AI agent using [LangGraph](https://github.com/langchain-ai/langgraph) and [LangChain](https://www.langchain.com/).  

The agent uses an LLM to reason and call [Tavily Search](https://www.tavily.com/) via `TavilySearchResults`, a tool that performs real-time web search and returns rich results in a ReAct-style loop.

Operates in a loop of: **Thought → Action → Observation → Answer
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


