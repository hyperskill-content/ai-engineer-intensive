# 5. Monitoring & Security

Start of module 5: April 6, 2026         
End of module 5: April 19, 2026            
Duration: 2 weeks            
Time estimate: ~10 hours per week, ~20 hours total

This module teaches you how to evaluate, monitor, and secure your LLM-powered applications. You’ll explore tools and practices that help prepare your app for real-world deployment — from performance tracking and prompt safety to cost control and failure handling.

By the end of this module, you’ll be able to build more trustworthy, maintainable, and cost-aware AI systems.

## Learning Outcomes

By the end of this module, you’ll:

- Learn how to monitor prompts, user inputs, and LLM responses in production
- Learn to evaluate the quality of LLM outputs enhanced with retrieval
- Set up observability with Langfuse and basic logging
- Apply security and rate-limiting practices to LLM endpoints
- Handle prompt injections and unsafe outputs
- Understand usage limits, quotas, and failure patterns of LLM APIs

> [!TIP]
> Both projects of the module belong to the short and full track.               

## Step 1 – Project: LLM Evals
**FULL TRACK** / **SHORT TRACK**

In this project, you'll build a complete evaluation pipeline for an LLM-based chatbot that helps users choose smartphones. You’ll integrate Langfuse and Ragas, and apply both human and model-based evaluation strategies to assess the performance and reliability of your system.

Start the [**LLM Evals** project](https://github.com/hyperskill-content/LLM-evals)

1. Work on [**stage 1/5 – Introduction and Setup**](https://github.com/hyperskill-content/LLM-evals/blob/main/tasks/task_1.md)
    
    **Core concepts needed:** Environment setup, working with Docker and Docker Compose, basic understanding of LangChain and Qdrant, Langfuse initialization, managing API keys. 
    
2. Work on [**stage 2/5 – Langfuse Monitoring**](https://github.com/hyperskill-content/LLM-evals/blob/main/tasks/task_2.md)
    
    **Core concepts needed:** `CallbackHandler`, `@observe` decorator (function tracing), UUID, traces (execution tracking), session management, metadata customization, token/cost tracking, understanding the RAG pipeline.
    
3. Work on [**stage 3/5 – Collecting User Feedback**](https://github.com/hyperskill-content/LLM-evals/blob/main/tasks/task_3.md)
    
    **Core concepts needed:** User feedback collection, manual annotation, scoring system, production feedback collection, evaluation methods comparison, trace-score linking
    
4. Work on [**stage 4/5 – Annotation**](https://github.com/hyperskill-content/LLM-evals/blob/main/tasks/task_4.md)
    
    **Core concepts needed:** Langfuse UI for trace annotation, expert evaluation workflows
    
5. Work on [**stage 5/5 – Model-Based Evaluation**](https://github.com/hyperskill-content/LLM-evals/blob/main/tasks/task_5.md)
    
    **Core concepts needed:** Ragas, DeepEval, LLM-as-a-judge, model-based evaluation, context precision and recall, faithfulness (hallucination detection), response relevancy (on-topic answers), modular evaluation, custom evaluation pipelines, automated scoring.
    

## Step 2 – Watch the session: Evaluation Nuances of LLM-based Apps

In this deep-dive recording, you’ll explore how to meaningfully evaluate LLM apps in production. It covers practical metrics, real-world examples, and tricky edge cases — especially in retrieval-augmented pipelines.

You’ll learn:

- How to evaluate both retrieval and generation quality
- What metrics actually matter for your use case
- How to build a test suite for RAG-style and tool-augmented pipelines
- Ethical and safety considerations
- How to use benchmarks effectively

**Topic:** **Deep-Dive: Evaluation Nuances of LLM-based Apps**

**The webinar was hosted by:** **Ivan Rodin**, AI researcher, collaborated with Intel Labs and Philips Research on various computer vision projects. Author of courses on neural nets, LLMs, prompt engineering

The details for this recording will be shared shortly. 

## Step 3 – Open hours: Monitoring and security

In this timeslot, you’ll be able to:

- Clarify how to set up monitoring and observability with Langfuse and logging
- Ask questions about evaluation metrics for retrieval and generation quality
- Discuss prompt injection risks, unsafe outputs, and safe handling practices
- Explore real-world strategies for rate-limiting, quotas, and failure patterns
- Get feedback on building reliable and secure LLM pipelines in production

**Date & Time, link:** The meeting details will be shared via Discord and the calendar

## Step 4 – Project: Preparing for production
**FULL TRACK** / **SHORT TRACK**

Every LLM request consumes tokens — and tokens cost money. In this project, you’ll set budget limits, optimize prompts, and manage inputs to keep your application both efficient and safe.

Start the [**LLM Evals: Preparing for production** project](https://github.com/hyperskill-content/llm-evals-2-preparing-for-prod)

1. Work on [**stage 1/4 – Prompt Management and Versioning**](https://github.com/hyperskill-content/llm-evals-2-preparing-for-prod/blob/main/tasks/task_1.md)
    
    **Core concepts needed:** Prompt versioning and management, prompt metadata linking, prompt experimentation, prompt rollback, cost optimization, token efficiency, UI-based prompt creation, API/SDK prompt retrieval, prompt tagging, decoupled prompt architecture, hard-coded prompt refactoring
    
2. Work on [**stage 2/4 – Managing chat history**](https://github.com/hyperskill-content/llm-evals-2-preparing-for-prod/blob/main/tasks/task_2.md)
    
    **Core concepts needed:** Redis and LangChain-Redis integration for chat history management, session management, chat history clearing, context balancing, persistence strategies, message trimming strategies. 
    
3. Work on [**stage 3/4 – LLM safety and security: Guardrails**](https://github.com/hyperskill-content/llm-evals-2-preparing-for-prod/blob/main/tasks/task_3.md)
    
    **Core concepts needed:** NeMo Guardrails, input rails (user input validation), output rails (LLM output validation), dialogue flow guardrails, YAML configuration for guardrails, harmful content detection, sensitive information protection, system prompt injection blocking, cost optimization (early blocking), debug logging, rail triggering.
    
4. Work on [**stage 4/4 – Managing API Keys and Budgets via LiteLLM Proxy**](https://github.com/hyperskill-content/llm-evals-2-preparing-for-prod/blob/main/tasks/task_4.md)
    
    **Core concepts needed:** LiteLLM, budget management, rate limiting (RPM/TPM), load balancing, fault tolerance, unified LLM API standardization, centralized management, user budgets, model routing, caching, alerting.
    

## **Wrapping Up**

This module helped you take your LLM app from prototype to production. With evaluation pipelines, logging, and safety layers in place, your system is now more transparent, cost-efficient, and reliable.

Next up: advanced architectures, agent orchestration, and autonomous workflows.

**See you in Module 6: Deploying LLM-Based Apps**