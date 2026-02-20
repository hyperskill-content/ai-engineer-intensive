# 4. Building RAG Systems

Start of module 4: March 23, 2026         
End of module 4: April 5, 2026                
Duration: 2 weeks             
Time estimate: ~12 hours per week, ~25 hours

This module covers the essentials of Retrieval-Augmented Generation (RAG) — a pattern for combining LLMs with your own data. You’ll learn how to connect vector stores, chunk text, and boost relevance with re-ranking techniques.

By the end of this module, your LLM apps will be smarter, more reliable, and actually grounded in the data you give them.

## Learning Outcomes

By the end of this module, you’ll:

- Understand the Retrieval-Augmented Generation (RAG) pattern
- Use LangChain to integrate LLMs with your own data
- Experiment with chunking strategies, query augmentation, re-ranking, and routing
- Improve reliability and user experience in data-rich AI apps

## Step 1 – Project: Introduction to LangChain
  **FULL TRACK**  /    **SHORT TRACK**

In this project, you’ll learn how to:

- Connect to LLM APIs and structure prompts
- Integrate external data and perform vector search
- Equip your LLM with tools and memory
- Build full LLM pipelines using modular components

By the end of the project, you’ll have created an application that answers questions about planets.

Start [**Introduction to LangChain**](https://hyperskill.org/projects/514) project

1. Work on [**stage 1/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3020/implement)
    
    **Core concepts needed:** The introduction to LangChain ecosystem, .env file configuration, prompt template and model invocation, response handling
    
2. Work on [**stage 2/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3021/implement)
    
    **Core concepts needed:** Prompt engineering basics, designing prompts for different tasks, few-shot prompting, response quality enhancement, structured instructions. 
    
3. Work on [**stage 3/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3022/implement)
    
    **Core concepts needed:**  Data ingestion, document loaders, text splitters, basics of chunking, vector stores, embeddings generation, similarity search, vector embeddings, retrievers, structured output. 
    
4. Work on [**stage 4/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3023/implement)
    
    **Core concepts needed:** Tool binding and invocation, function calling, `@tool` decorator, API interaction patterns, custom tool creation, multi-tool handling,
    
5. Work on [**stage 5/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3024/implement)
    
    **Core concepts needed:** Workflow composition using LangChain runnables, chaining components, executing complete LLM-based applications.
    

## Step 2 – Watch the session: RAG System Design

The details for this session will be shared shortly.

## Step 3 – Project: Building the Naive RAG 
  **FULL TRACK**

In this project, you’ll build your first full Retrieval-Augmented Generation (RAG) pipeline using movie scripts as your dataset.

You’ll learn how to:

- Load and chunk data for semantic search
- Generate vector embeddings for retrieval
- Connect the results to a language model for custom generation

Start [**Building the Naive RAG**](https://hyperskill.org/projects/518) project

1. Work on [**stage 1/5 Building the Naive RAG**](https://hyperskill.org/projects/518/stages/3035/implement)
    
    **Core concepts needed:** LangChain community loaders, web scraping, BeautifulSoup (bs4), exception handling, text parsing and conditional processing.
    
2. Work on [**stage 2/5 Building the Naive RAG**](https://hyperskill.org/projects/518/stages/3036/implement)
    
    **Core concepts needed:** Chunking strategies, context preservation, sentence and paragraph segmentation, working with overlapping windows, iterators.
    
3. Work on [**stage 3/5 Building the Naive RAG**](https://hyperskill.org/projects/518/stages/3037/implement)
    
    **Core concepts needed:** Text embedding generation, use of embedding models (e.g. OpenAI or Hugging Face), vector representation of chunks, dimensionality understanding.
    
4. Work on [**stage 4/5 Building the Naive RAG**](https://hyperskill.org/projects/518/stages/3038/implement)
    
    **Core concepts needed:** Semantic similarity search, vector distance metrics, retrieving top-k relevant chunks based on query input, query preprocessing.
    
5. Work on [**stage 5/5 Building the Naive RAG**](https://hyperskill.org/projects/518/stages/3039/implement)
    
    **Core concepts needed:** Prompt composition with context, injecting retrieved data into LLM prompts, generation control techniques, evaluating output quality.
    

## Step 4 – Open hours: Building RAG systems 

In this timeslot, you’ll be able to:

- Clarify concepts around chunking, query augmentation, and re-ranking
- Ask questions about building robust RAG pipelines with LangChain
- Get feedback on debugging common issues with retrieval and relevance
- Explore how to improve user experience in RAG-powered apps

**Date & Time, link:** The meeting details will be shared via Discord and the calendar

## Step 5 – Project: Advanced RAG 
  **FULL TRACK**  /    **SHORT TRACK**

In this project, you’ll apply advanced techniques that boost RAG system performance — making responses more relevant and better aligned with user intent.

You’ll learn how to:

- Clean and optimize your dataset
- Rewrite and decompose queries for better matches
- Generate hypothetical content to boost recall
- Score and rerank retrieved results for better quality

Start [**Advanced RAG**](https://hyperskill.org/projects/521) project

1. Work on [**stage 1/6 Advanced RAG**](https://hyperskill.org/projects/521/stages/3051/implement)
    
    **Core concepts needed:** Data cleaning and refinement, preprocessing strategies for noisy or inconsistent data, enhancing quality of source material before embedding.
    
2. Work on [**stage 2/6 Advanced RAG**](https://hyperskill.org/projects/521/stages/3052/implement)
    
    **Core concepts needed:** Vector store configuration, working with PGVector, matching data types with store capabilities, trade-offs in storage methods, embedding strategies.
    
3. Work on [**stage 3/6 Advanced RAG**](https://hyperskill.org/projects/521/stages/3053/implement)
    
    **Core concepts needed:** Query decomposition, intent recognition, identifying sub-questions, preparing complex queries for better chunk matching.
    
4. Work on [**stage 4/6 Advanced RAG**](https://hyperskill.org/projects/521/stages/3054/implement)
    
    **Core concepts needed:** Hypothetical document generation (HyDE), using LLMs to enrich context, improving weak queries with synthetic data.
    
5. Work on [**stage 5/6 Advanced RAG**](https://hyperskill.org/projects/521/stages/3055/implement)
    
    **Core concepts needed:** Context scoring and re-ranking, Cohere re-ranker, similarity metrics beyond top-k, evaluating retrieved documents based on quality and relevance.
    
6. Work on [**stage 6/6 Advanced RAG**](https://hyperskill.org/projects/521/stages/3056/implement)
    
    **Core concepts needed:** Query-based routing, dynamically choosing vector stores based on query type, decision logic in hybrid retrieval setups.    

## Wrapping Up

You now know how to build Retrieval-Augmented Generation systems — the foundation of scalable, grounded, and reliable AI tools. These pipelines let your models go beyond chat — and actually reason with your knowledge base.

In the next module, you'll take it even further: evaluating LLM output, scoring relevance, and stress-testing your system.

**See you in Module 5: Monitoring & Security**