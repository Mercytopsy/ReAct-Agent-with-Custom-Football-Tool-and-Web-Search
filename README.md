This project implements a general-purpose ReAct agent using LangGraph. The agent dynamically chooses between:

🏟️ A custom LiveScore tool to fetch upcoming football matches by country

🌐 The Tavily Search tool to answer general user queries

By combining tools, the agent can decide whether to search the web or retrieve structured match data based on the user's intent.

This runs on a local LLM using Ollama.
