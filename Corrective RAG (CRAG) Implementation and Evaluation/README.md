# Corrective RAG (CRAG) Implementation and Evaluation

Corrective-RAG (CRAG) is a strategy for Retrieval-Augmented Generation (RAG) that incorporates self-reflection and self-grading on retrieved documents. This is a small implementation of a custom/user-defined control flow in LangGraph, along with testing and evaluation procedures.

## Overview

In this project, we:
1. Implement a custom agent using LangGraph.
2. Test the agent with an evaluation set of question-answer pairs in LangSmith.
3. Evaluate end-to-end performance and reasoning trace of our agents.


**We have used the following**
- Llama 3.1 with Ollama as our LLM (can be swapped).
- Tavily for web search.
- OpenAI embeddings for the vector store (can be swapped for Nomic local embeddings).
- LangSmith for tracing and evaluation.
penai scikit-learn langchainhub langchain-ollama nomic[local]
