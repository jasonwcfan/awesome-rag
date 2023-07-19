# 🧺 Awesome RAG [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub Repo stars](https://img.shields.io/github/stars/jasonwcfan/awesome-rag?style=social)

> Curated list of open source tools and projects to help with retrieval augmented generation

RAG stands for Retrieval Augmented Generation, a technique where the capabilities of a large language model (LLM) are augmented by retrieving information from other computer systems and providing them as context for the LLM through the prompt. This gives LLMs information beyond what was provided in their training data, which is critical for LLM applications to provide personalized responses. Example use cases include scraping data from current web pages, parsing data from PDFs and documents, and answering questions about data from Confluence, Salesforce or other SaaS apps.

RAG works better than fine-tuning models because it’s cheaper, it’s faster, and it’s more reliable since metadata about the sources of information is attached to each response.

## We also have an open source project that makes setting up RAG on your own infrastructure super easy. **[Check it out here](https://github.com/psychic-api/rag-stack)**

Contributions welcome. Add links through pull requests or create an issue to start a discussion. Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.

## Table of Contents

- [🧺 Awesome RAG ](#-awesome-rag--)
  - [Table of Contents](#table-of-contents)
  - [Data Connectors] (#connectors)
  - [Storage](#storage)
    - [Vector Databases](#vector-databases)
    - [Document Databases](#document-databases)
    - [Relational Databases](#agents)
    - [Graph Databases](#templates)
  - [Retrieval](#retrieval)
  - [LLMs](#llms)
  - [Deployment](#alternatives)
  - [Articles](#articles)


## Data Connectors
Tools for connecting to data sources
- [Psychic](https://github.com/psychicapi/psychic): Data integrations platform for LLMs with turnkey auth, syncs and an universal API. ![GitHub Repo stars](https://img.shields.io/github/stars/psychicapi/psychic?style=social)
- 
## Storage
Tools and databases to store knowledge for retrieval.

### Vector Databases

- [Chroma](https://github.com/chroma-core/chroma): The AI-native open-source embedding database. ![GitHub Repo stars](https://img.shields.io/github/stars/chroma-core/chroma?style=social)
- [Qdrant](https://github.com/qdrant/qdrant): Vector Database for the next generation of AI applications. Also available in the cloud. ![GitHub Repo stars](https://img.shields.io/github/stars/qdrant/qdrant?style=social)
- [Weaviate](https://github.com/weaviate/weaviate): Weaviate is an open source vector database that stores both objects and vectors, allowing for combining vector search with structured filtering with the fault-tolerance and scalability of a cloud-native database, all accessible through GraphQL, REST, and various language clients. ![GitHub Repo stars](https://img.shields.io/github/stars/weaviate/weaviate?style=social)

### Document Databases

- [MongoDB](https://github.com/mongodb/mongo): The MongoDB Database. ![GitHub Repo stars](https://img.shields.io/github/stars/mongodb/mongo?style=social)

### Relational Databases

- [PostgreSQL](https://github.com/postgres/postgres): Mirror of the official PostgreSQL GIT repository. Note that this is just a *mirror* - we don't work with pull requests on github. To contribute, please see https://wiki.postgresql.org/wiki/Submitting_a_Patch ![GitHub Repo stars](https://img.shields.io/github/stars/postgres/postgres?style=social)
- [Supabase](https://github.com/supabase/supabase): The open source Firebase alternative. Follow to stay updated about our public Beta. ![GitHub Repo stars](https://img.shields.io/github/stars/supabase/supabase?style=social)

### Graph Databases

- [Neo4j](https://github.com/neo4j/neo4j): Graphs for everyone ![GitHub Repo stars](https://img.shields.io/github/stars/neo4j/neo4j?style=social)


## Retrieval
- [LlamaIndex](https://github.com/jerryjliu/llama_index): LlamaIndex (GPT Index) is a data framework for your LLM applications ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=social)

## LLMs
- [Llama 2](https://ai.meta.com/llama/): The next generation of Meta's open source large language model.
- [LlamaIndex](https://github.com/nomic-ai/gpt4all): An ecosystem of open-source chatbots trained on a massive collections of clean assistant data including code, stories and dialogue ![GitHub Repo stars](https://img.shields.io/github/stars/nomic-ai/gpt4all?style=social)

## Deployment
- [RAGStack](https://github.com/psychicapi/rag-stack): Chat your data privately with a self-hosted retrieval augmented generation (RAG) stack built on top of open-source LLMs like Falcon, Llama and GPT4All ![GitHub Repo stars](https://img.shields.io/github/stars/psychicapi/rag-stack?style=social)

### Articles
- [Build a GitHub support bot with GPT3, LangChain, and Python](https://dagster.io/blog/chatgpt-langchain)
