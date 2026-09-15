# ReAct Search Agent

A hands-on LangChain project for learning how to build an AI agent that can use tools to search the web and return structured results.

---

## Project Overview

In this project, I built a search agent using LangChain.

The agent uses:

- OpenAI GPT-5 as the LLM
- Tavily Search as a web search tool
- Pydantic to define the structure of the response
- LangChain Agent to connect the LLM and tools
- LangSmith for tracing and observing the agent

The agent can receive a user's question, decide to use the search tool, retrieve information, and return a structured response.

---

# Tools & Technologies I Used

## 1. Python

Python is the programming language used to build the agent.

---

## 2. LangChain

LangChain provides the framework for connecting the LLM, tools, and agent.

Main components I used:

```python
from langchain.agents import create_agent
from langchain_core.messages import HumanMessage
