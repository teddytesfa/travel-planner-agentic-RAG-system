# Agentic RAG System Demo: Eco-Friendly Ethiopia Travel Planner

This notebook showcases how to build **Agentic Retrieval-Augmented Generation (RAG) Systems** using the Hugging Face [`smolagents`](https://github.com/huggingface/smolagents) framework.

---

## 📋 Overview

Learn how to combine **web search** and a **custom semantic knowledge base** with agent orchestration. The demo guides you through:

- Using DuckDuckGo web search as a tool for live travel information retrieval.
- Building your own eco-friendly travel knowledge base and connecting it to the agent via a BM25 retriever.
- Composing queries, retrieving relevant trip ideas, and leveraging agentic strategies like query decomposition and multi-source result integration.

---

## 🚀 Use Case

**Eco-Friendly Ethiopia Travel Planner:**  
Find curated recommendations for responsible tourism—nature reserves, eco-lodges, authentic cultural experiences, wildlife watching, and sustainable transport options.

---

## 🛠️ Features

- **Web Search Tool:** Queries DuckDuckGo for live, up-to-date travel tips.
- **Custom Retriever Tool:** Searches a structured database of eco-friendly travel ideas using semantic similarity (BM25).
- **Agent Orchestration:** Wraps tools into a unified agent to flexibly answer complex or multi-step queries.

---

## 📑 Notebook Sections

1. **Environment Setup:** All necessary imports; instructions for installing dependencies.
2. **Web Retrieval:** Querying DuckDuckGo for Ethiopia travel information.
3. **Custom Knowledge Base:** Creating and semantically searching structured travel ideas.
4. **Agentic Strategies:**  
   - Query decomposition (breaking complex requests into focused sub-queries)
   - Multi-step retrieval demonstration
   - (Extendable for reranking, memory, multi-agent workflows)

---

## ⚡ Getting Started

1. Clone the notebook.
2. Install dependencies:  
   `!pip install smolagents langchain_community rank_bm25 ddgs`
3. Run each cell to see live agentic retrieval and response generation.
4. Adapt the knowledge base or queries for your own travel or planning use cases!

---

## 📚 References

- Hugging Face Agents Course: [Unit 2—Building Agentic RAG Systems](https://huggingface.co/learn/agents-course/unit2/smolagents/retrieval_agents)
- [smolagents GitHub](https://github.com/huggingface/smolagents)
- [Langchain Retrievers](https://python.langchain.com/docs/modules/data_connection/retrievers)

---

Enjoy building your next **Agentic RAG-powered assistant**!
