# LingoGraph-Agent: AI-Powered Language Learning Agent

LingoGraph-Agent is an end-to-end autonomous agent designed to streamline the language learning process. Built with **LangGraph** and **Python**, the agent utilizes a **ReAct** (Reasoning and Acting) architecture to assist users in sourcing vocabulary, translating complex phrases, and automating the creation of Anki flashcards.

## 🚀 Overview

This project explores the intersection of Agentic workflows and language acquisition. By leveraging the **Model Context Protocol (MCP)**, the agent connects to external tools and balances the strengths of both proprietary models (OpenAI) and local LLMs (Ollama).

## 🛠️ Tech Stack

*   **Orchestration:** [LangGraph](https://github.com/langchain-ai/langgraph)
*   **Inference:** OpenAI (GPT-4o/o1) & Ollama (Local Llama 3 / Mistral)
*   **Tooling:** Model Context Protocol (MCP)
*   **Language:** Python 3.10+
*   **Output:** Anki-compatible flashcard generation

## 🧠 Key Features

*   **ReAct Agent Architecture:** Implements a sophisticated "think-act-observe" loop for complex task solving.
*   **Hybrid LLM Strategy:** Seamlessly switches between high-performance cloud models and cost-effective local models.
*   **Automated Flashcards:** Automatically formats and exports vocabulary data into Anki decks for long-term retention.
*   **External Tool Integration:** Uses MCP to source real-world data and context for more accurate translations.

## 📈 Learning Objectives

1.  Designing multi-step AI agent workflows.
2.  Implementing state management within LangGraph.
3.  Managing tool-calling and external API integrations via MCP.
4.  Optimizing prompt engineering for language-specific nuances.

## ⚖️ Acknowledgments

This project is based on the [Language Learning Agent](https://github.com/t-redactyl/language-learning-agent) course by t-redactyl.
