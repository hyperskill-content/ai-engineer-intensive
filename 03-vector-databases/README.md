# 3. Vector Databases

Start of module 1: March 16, 2026          
End of module 1: March 22, 2026             
Duration: 1 week             
Time estimate: ~12 hours per week            

This module introduces vector databases — essential components of modern LLM-powered applications. You’ll learn how to store, index, and query unstructured data using vector search, and integrate it into your own FastAPI app.

By the end, you’ll know how to implement semantic search with custom data using Qdrant and OpenAI embeddings.

## **Learning Outcomes**

By the end of this module, you’ll:

- Understand why vector databases matter in LLM-based systems
- Learn how embeddings and vector similarity work
- Store and query unstructured data using Qdrant
- Learn about the main techniques for vector database performance optimization

## Step 1 – Project: Vector Database with Qdrant
  **FULL TRACK**  /    **SHORT TRACK**

Let’s get hands-on with Qdrant — a high-performance, open-source vector database. You’ll start by loading data into the database and building a basic semantic search system using OpenAI’s embeddings and FastAPI.

Start the [**Vector Database with Qdrant**](https://hyperskill.org/projects/510) project 

1. Work on [**stage 1/5 – Abstract Loading**](https://hyperskill.org/projects/510/stages/3000/implement)
    
    **Core concepts needed:** Basics of vector and semantic search, cosine distance, embeddings, Qdrant vector DB, collections, [PointStruct](https://python-client.qdrant.tech/qdrant_client.http.models.models.html#qdrant_client.http.models.models.PointStruct), [upsert](https://api.qdrant.tech/api-reference/points/upsert-points), JSON streaming, batch processing, generator functions, UUID generation, Docker basics, text preprocessing, configuration management, error handling, record filtering, payload extraction.
    
2. Work on [**stage 2/5 – Similar Documents**](https://hyperskill.org/projects/510/stages/3001/implement)
    
    **Core concepts needed:** [Scroll](https://api.qdrant.tech/v-1-15-x/api-reference/points/scroll-points) method, [query_points](https://api.qdrant.tech/api-reference/search/query-points) method, similarity search, query vectors, match filters, vector retrieval, search parameters, limit and offset, ranked results processing, similarity scoring.
    
3. Work on [**stage 3/5 – Natural Search**](https://hyperskill.org/projects/510/stages/3002/implement)
    
    **Core concepts needed:** OpenAI API integration, API key management, environment variables (.env files), embedding generation, OpenAI client initialization, API response parsing, embedding data extraction, function composition patterns.
    
4. Work on [**stage 4/5 – Keys and Queries**](https://hyperskill.org/projects/510/stages/3010/implement)
    
    **Core concepts needed:** Regular expressions, pattern matching, conditional filtering, Filter class, FieldCondition, MatchText, query_filter parameter, hybrid search (embedding + metadata filtering), metadata-based filtering. 
    
5. Work on [**stage 5/5 – Search Wrap**](https://hyperskill.org/projects/510/stages/3011/implement)
    
    **Core concepts needed:** FastAPI framework, Pydantic models, BaseModel, HTTP POST endpoints, REST API design, API decorators (@app.post), response_model parameter, HTTPException, request validation, data serialization, uvicorn server, API documentation (Swagger UI), endpoint testing, JSON request/response format, exception handling, list comprehension.
    

## Step 2 – Open hours: Vector Databases

In this timeslot, you’ll be able to:

- Clarify concepts around embeddings and similarity search
- Ask questions about using Qdrant for storing and querying data
- Get help troubleshooting vector search performance
- Discuss optimization techniques for scaling vector database workloads

**Date & Time, link:** The meeting details will be shared via Discord and the calendar


## Step 3 – Project: Further Steps with Qdrant
  **FULL TRACK**

Time to go deeper. You’ll optimize your Qdrant setup for both speed and accuracy. Learn how index types, search parameters, and quantization affect performance — and when to use each.

Start the [**Further Steps with Qdrant**](https://github.com/hyperskill-content/further-steps-with-qdrant) project 

1. Work on [**stage 1/3 – Catching Up**](https://github.com/hyperskill-content/further-steps-with-qdrant/blob/main/tasks/task_1.md)
    
    **Core concepts needed:** k-NN vs approximate search, vector distance metrics, response time analysis
    
2. Work on [**stage 2/3 – Balance the Search**](https://github.com/hyperskill-content/further-steps-with-qdrant/blob/main/tasks/task_2.md)
    
    **Core concepts needed:** Fine-tuning search parameters (e.g., `ef`, `top_k`), understanding trade-offs in latency and precision
    
3. Work on [**stage 3/3 – Quantization**](https://github.com/hyperskill-content/further-steps-with-qdrant/blob/main/tasks/task_3.md)
    
    **Core concepts needed:** Embedding compression, scalar and product quantization, accuracy vs size trade-offs
    

## **Wrapping up**

This module laid the foundation for scalable knowledge retrieval. You now know how to store, embed, and semantically query large amounts of semi-unstructured data using Qdrant — one of the key building blocks of modern AI systems.

Next up: Building RAGs — Retrieval-Augmented Generation systems that combine vector search and LLMs to generate better, more grounded responses.

**See you in Module 4: Building RAG Systems**