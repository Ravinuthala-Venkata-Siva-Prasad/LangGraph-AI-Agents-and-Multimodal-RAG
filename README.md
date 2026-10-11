# LangGraph AI Agents and Multimodal RAG

A collection of hands-on AI projects built using Python, LangChain, and LangGraph. This repository explores AI agents, tool calling, chatbot development, human-in-the-loop workflows, and multimodal Retrieval-Augmented Generation (RAG).

The projects demonstrate how to build LLM-powered applications that can interact with tools, maintain conversational state, and perform different tasks using graph-based workflows.

## 🚀 Projects

### 1. Basic Chatbot
**Folder:** `1.BasicChatBot/`

- Build a conversational chatbot using LangGraph.
- Understand graph-based workflows.
- Learn how messages move between graph nodes.

### 2. Human Assistant
**Folder:** `2.HumanAssistant/`

- Explore human-in-the-loop AI workflows.
- Experiment with human interaction in agent-based applications.
- Learn how to integrate external tools into an assistant.

### 3. Tool Calling and Debugging
**Folder:** `3.Debugging/`

- Build a tool-calling agent using LangGraph.
- Integrate tools with an LLM.
- Use `ToolNode` and `tools_condition`.
- Create graph workflows with conditional edges.
- Explore how an agent calls tools and processes their results.

### 4. Multi-Agent System and Multimodal RAG
**Folder:** `4.Multimodel/`

**Multi-Agent System**
- Experiment with multiple AI agents.
- Explore researcher, analyst, and writer workflows.
- Understand how tasks can be divided among agents.

**Multimodal RAG**
- Explore PDF processing using PyMuPDF.
- Experiment with text and image extraction.
- Use Hugging Face CLIP for multimodal embeddings.
- Explore FAISS for similarity search.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **LLM Framework:** LangChain
- **Agent Framework:** LangGraph
- **LLM Provider:** Groq
- **Web Search:** Tavily Search
- **Embeddings:** Hugging Face CLIP
- **Vector Search:** FAISS
- **PDF Processing:** PyMuPDF
- **Environment Management:** uv
- **Development Tools:** VS Code, Jupyter Notebook
- **Tracing and Monitoring:** LangSmith

## 📋 Prerequisites

- Python 3.11 or 3.12
- uv
- Git
- API keys for the services required by individual projects
