An AI-powered multi-agent legal assistant built using IBM Watson Orchestrate, IBM Granite Models, RAG, and IBM watsonx.ai.
![Homepage](Screenshot%20(152).png)


📖 Overview

The Closer AI is an AI-powered legal assistance platform that simplifies legal information through Agentic AI.The Closer AI is your intelligent legal aid assistant, designed to simplify complex legal matters. It explains legal concepts, reviews documents, drafts legal content, and provides clear, reliable information in plain language. While not a substitute for a lawyer, it helps you understand your options and prepare with confidence.

Instead of relying on a single chatbot, the system routes user queries to specialized AI agents capable of:

1. 📜 Explaining legal concepts
2. 📄 Reviewing legal documents
3. ⚖️ Researching case law
4. ✅ Checking compliance
5. 🔍 Retrieving relevant legal information using RAG

Disclaimer: The Closer AI provides educational legal information and does not replace professional legal advice.

🚀 Features
1. Multi-Agent AI Architecture
2. Retrieval-Augmented Generation (RAG)
3. Contract Review
4. Legal Question Answering
5. Compliance Checking
6. Case Law Research
7. IBM Watson Orchestrate Integration
8. IBM Granite Models
9. IBM watsonx.ai
10. IBM Cloud Deployment

## 🏠 Homepage

![Homepage](Screenshot%20(153).png)

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

