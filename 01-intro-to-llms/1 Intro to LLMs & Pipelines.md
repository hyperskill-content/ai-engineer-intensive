# 1. Intro to LLMs & Pipelines

Start of module 1: February 16, 2026        
End of module 1: March 1, 2026       
Duration: 2 weeks            
Time estimate: ~12 hours per week, ~25 hours total                    

This module covers the fundamentals of building with AI. You'll work directly with LLMs to understand their capabilities and limitations, then learn to integrate them into code to create tools. We'll focus on practical implementation and building right away.

## Learning Outcomes

By the end of this module, you’ll:

- Learn about an AI engineer’s role, typical tasks, and job requirements.
- Practice Python basics to build simple apps and interact with LLM APIs.
- Understand the basics of LLMs and their current limitations.
- Master prompting skills and basic prompting techniques while building LLM-based apps.

## Step 1 – Watch the session: *Breaking Into AI Engineering*

Start the module by watching this session, which covers:

- What modern AI engineers actually do
- Where LLMs fit in today’s software stack
- The skill stack you need (and don’t need) to get started
- Common myths and blockers for newcomers

**Topic:** Breaking Into AI Engineering                     
**The webinar was hosted by:** Ruslan Davletshin, CTO of Hyperskill                 

[See video recording of the webinar](https://drive.google.com/file/d/1ePmMgWz6RnRfENbBFUCSxtCNr-dVqg_1/view?usp=sharing)

## Step 2 – Project: The Stock Analyzer (Responses API)
  **FULL TRACK**  /    **SHORT TRACK**

This project introduces building agents with OpenAI's Responses API by integrating MCP servers for external data retrieval and combining them with code interpreter tools for autonomous computational analysis and visualization generation.

Start the [Stock Analyzer](https://hyperskill.org/projects/558) project       

1. Work on [stage 1/4 Stock Analyzer](https://hyperskill.org/projects/558/stages/3190/implement)                 
**Core concepts needed**: `dotenv` library, OpenAI API client initialization, MCP server configuration (`server_label`, `server_url`, `authorization`, `require_approval`), `responses.create()` endpoint, prompt engineering for MCP tool usage.
2. Work on [stage 2/4 Stock Analyzer](https://hyperskill.org/projects/558/stages/3189/implement)          
**Core concepts needed**: Multi-tool MCP requests, technical indicator parameters (RSI, SMA, BBANDS), structured prompt design for sequential `TOOL_CALL` invocations, financial function parameter specification (`interval`, `time_period`, `series_type`).
3. Work on [stage 3/4 Stock Analyzer](https://hyperskill.org/projects/558/stages/3191/implement)              
**Core concepts needed**: Code interpreter tool integration, combining MCP with computational tools, multi-step prompt workflows (retrieve then analyze), statistical calculations through generated code.
4. Work on [task 4/4 Stock Analyzer](https://hyperskill.org/projects/558/stages/3192/implement)              
**Core concepts needed**: Visualization generation with code interpreter, response annotation parsing (`AnnotationContainerFileCitation`), `client.containers.files.content.retrieve()`, file content extraction and binary file writing.

## Step 3 – Open hours: Intro to LLMs & Pipelines

In this timeslot, you’ll be able to:

- Clarify what an AI engineer’s role looks like in real projects
- Ask any questions related to the curriculum and the module
- Discuss LLM capabilities, limitations, and prompting techniques
- Get advice on how to structure your own first steps in AI engineering

**Date & Time:** TBA

**Link:** TBA


## Step 4 – Project: Simple Python CLI Chat
  **FULL TRACK**  /    **SHORT TRACK**

In this project, you’ll learn how to:

- Send and receive structured messages through the OpenAI API
- Work with system, user, and assistant roles
- Manage the conversation history
- Print responses directly to your terminal

Start [Simple Python CLI Chat](https://hyperskill.org/projects/478) project

1. Work on [stage 1/3 Simple Python CLI Chat](https://hyperskill.org/projects/478/stages/2736/implement)    
Core concepts needed: Function declaration and invocation, modules and packages, command line navigation, pip package management, HTTP protocol, JSON handling, URL manipulation, dotenv configuration, and OpenAI API integration.
2. Work on [stage 2/3 Simple Python CLI Chat](https://hyperskill.org/projects/478/stages/2737/implement)            
Core concepts needed: basic arithmetic operations in Python, basic prompting techniques (zero-shot, few-shot, and chain-of-thought prompting).      
3. Work on [stage 3/3 Simple Python CLI Chat](https://hyperskill.org/projects/478/stages/2738/implement)       
Core concepts needed: global variables, dictionary and list data structures, loops, `**kwargs`, OpenAI’s API function/tool calling with JSON schema, object attribute access, string formatting with f-strings, conditional execution.

## Step 5 - Project: Introduction to Langchain

  **FULL TRACK**  /    **SHORT TRACK**

Note: If you don't have time to complete this project in the first module - don't worry, it will be revisited in the fourth module (Building RAG systems).

In this project, you’ll learn how to:

- Connect to LLM APIs and structure prompts
- Integrate external data and perform vector search
- Equip your LLM with tools and memory
- Build full LLM pipelines using modular components

By the end of the project, you’ll have created an application that answers questions about planets.

Start [**Introduction to LangChain**](https://hyperskill.org/projects/514) project

1. Work on [**stage 1/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3020/implement)
    
    **Core concepts needed:** The introduction to LangChain ecosystem, `.env` file configuration, prompt template and model invocation, response handling
    
2. Work on [**stage 2/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3021/implement)
    
    **Core concepts needed:** Prompt engineering basics, designing prompts for different tasks, few-shot prompting, response quality enhancement, structured instructions. 
    
3. Work on [**stage 3/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3022/implement)
    
    **Core concepts needed:**  Data ingestion, document loaders, text splitters, basics of chunking, vector stores, embeddings generation, similarity search, vector embeddings, retrievers, structured output. 
    
4. Work on [**stage 4/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3023/implement)
    
    **Core concepts needed:** Tool binding and invocation, function calling, `@tool` decorator, API interaction patterns, custom tool creation, multi-tool handling,
    
5. Work on [**stage 5/5 Introduction to LangChain**](https://hyperskill.org/projects/514/stages/3024/implement)
    
    **Core concepts needed:** Workflow composition using LangChain runnables, chaining components, executing complete LLM-based applications.

## Wrapping up

You built working AI tools in your first module. They are functional projects using LLMs and APIs with code you wrote and understand.


**See you in Module 2: Building Agents & Multi-Agent Systems**