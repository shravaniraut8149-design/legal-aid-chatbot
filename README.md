An AI-powered multi-agent legal assistant built using IBM Watson Orchestrate, IBM Granite Models, RAG, and IBM watsonx.ai.

📖 Overview

The Closer AI is an AI-powered legal assistance platform that simplifies legal information through Agentic AI.The Closer AI is your intelligent legal aid assistant, designed to simplify complex legal matters. It explains legal concepts, reviews documents, drafts legal content, and provides clear, reliable information in plain language. While not a substitute for a lawyer, it helps you understand your options and prepare with confidence.

Instead of relying on a single chatbot, the system routes user queries to specialized AI agents capable of:

📜 Explaining legal concepts
📄 Reviewing legal documents
⚖️ Researching case law
✅ Checking compliance
🔍 Retrieving relevant legal information using RAG

Disclaimer: The Closer AI provides educational legal information and does not replace professional legal advice.

🚀 Features
Multi-Agent AI Architecture
Retrieval-Augmented Generation (RAG)
Contract Review
Legal Question Answering
Compliance Checking
Case Law Research
IBM Watson Orchestrate Integration
IBM Granite Models
IBM watsonx.ai
IBM Cloud Deployment

🏗 Architecture
## 🏗 Architecture

```mermaid
flowchart TD
    A[User] --> B[IBM Watson Orchestrate]
    B --> C[AI Orchestrator]

    C --> D[Contract Review Agent]
    C --> E[Compliance Checker Agent]
    C --> F[Legal Q&A Agent]
    C --> G[Case Research Agent]

    D --> H[RAG Knowledge Base]
    E --> H
    F --> H
    G --> H

    H --> I[IBM Granite Model]
    I --> J[Legal Response]

