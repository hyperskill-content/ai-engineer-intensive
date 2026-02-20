# 2. Building Agents & Multi-Agent Systems

Start of module 2: March 2, 2026               
End of module 2: March 15, 2026                              
Duration: 2 weeks             
Time estimate: ~12 hours per week, ~25 hours total

This module covers the basics of autonomous AI agents — systems that can perform tasks, call APIs, and work together without constant human input. 

We'll start with the basics of how agents actually work, then build 2 systems that demonstrate these concepts in action.

## Learning Outcomes

By the end of this module, you’ll:

- Understand the concept of autonomous AI agents and agent-based systems
- Learn how to structure agent workflows using tools like LlamaIndex
- Explore memory, reflection, and tool-use within agent design
- Create multi-step agents that interact with APIs, tools, or data

> [!TIP]
> Here is the breakdown of the short and full track project split for this module:                
> Building a PR Review Agent - short & full             
> Applied Memory for Agents - full              
> AI Diet & Meal Planner - full      

## Step 1 – Watch the session: AI Agents: Beyond the Hype

Start this module by watching the webinar recording, which covers:

- What AI agents really are (and what they’re not)
- Agent architecture in practice: memory, tools, goals
- Single-agent vs multi-agent setups
- Tradeoffs: autonomy vs control


**Topic:** AI Agents: Beyond the Hype

**The webinar was hosted by:** **Ivan Rodin**, AI researcher, collaborated with Intel Labs and Philips Research on various computer vision projects. Author of courses on neural nets, LLMs, prompt engineering

[See video recording of the webinar](https://drive.google.com/file/d/1Yj0PxDlD6DMXKudVvUfh-abomRvHrqw5/view?usp=sharing)

The code is available [here](https://github.com/hyperskill-content/AI-Agents-Intro-Hyperskill).


## Step 2 – Project: Building a PR Review Agent
**FULL TRACK** / **SHORT TRACK**

It’s time to make your agent part of the dev team.

In this project, you’ll build an AI agent that reviews pull requests on GitHub. It’ll read code changes, generate feedback, refine its drafts, and post final comments — all inside a GitHub workflow. You'll also automate it all with GitHub Actions.

Start [**Building a PR Review Agent**](https://hyperskill.org/projects/528) project

1. Work on [**stage 1/5 Building a PR Review Agent**](https://hyperskill.org/projects/528/stages/3079/implement)
    
    **Core concepts needed:** Git basics, GitHub repositories, local setup, remote syncing, forks, pull requests, git branches, environment variables, authentication, Personal Access Tokens.
    
2. Work on [**stage 2/5 Building a PR Review Agent**](https://hyperskill.org/projects/528/stages/3080/implement)
    
    **Core concepts needed:** The introduction of LlamaIndex (`FunctionTool`, `AgentOutput`, `ToolCallResult`, `ReActAgent`, etc.), working with `PyGithub` (pull request data extraction, file content retrieval, commit diff analysis), tool calling mechanisms, async execution patterns and event streaming, ReAct agent, agent tool composition, prompt planning, API exception handling.
    
3. Work on [**stage 3/5 Building a PR Review Agent**](https://hyperskill.org/projects/528/stages/3081/implement)
    
    **Core concepts needed:** Multi-agent orchestration, state management using async context, LlamaIndex’s `AgentWorkflow` and `FunctionAgent`, difference between `FunctionAgent` and `ReActAgent`, dictionary state manipulation, async function tools, event type checking.
    
4. Work on [**stage 4/5 Building a PR Review Agent**](https://hyperskill.org/projects/528/stages/3082/implement)
    
    **Core concepts needed:** Review and refinement workflows, GitHub API review submission, agent validation logic, multi-directional agent handoffs, tool composition for posting actions, system prompt refinement.
    
5. Work on [**stage 5/5 Building a PR Review Agent**](https://hyperskill.org/projects/528/stages/3083/implement)
    
    **Core concepts needed:** GitHub Actions setup, workflow automation, CI/CD fundamentals, deployment of AI workflows.
    
## Step 3 – Project: Applied Memory for Agents
**FULL TRACK** / **SHORT TRACK**                 
The details on this project will be provided shortly. 

## Step 4 – Open hours: Building Agents

In this timeslot, you’ll be able to:

- Ask questions about agent architecture and workflows
- Clarify how memory, reflection, and tool-use work in practice
- Discuss tradeoffs between autonomy and control in agent design

**Date & Time, link:** The meeting details will be shared via Discord and the calendar

## Step 5 – Project: AI Diet & Meal Planner (Optional)
**FULL TRACK**

In this project, you'll build a FastAPI backend where multiple agents work together. Each agent handles a specific task like checking ingredients or recommending recipes. You'll write clear JSON-based prompts, create endpoints that handle complete user requests, and work with logging and containers.

Start [**AI Diet & Meal Planner**](https://hyperskill.org/projects/530) project

1. Work on [**stage 1/5 AI Diet & Meal Planner**](https://hyperskill.org/projects/530/stages/3084/implement)
    
    **Core concepts needed:** FastAPI basics, ASGI, Uvicorn, MVC architecture, REST API routing, HTTP requests, server-client communication.
    
2. Work on [**stage 2/5 AI Diet & Meal Planner**](https://hyperskill.org/projects/530/stages/3090/implement)
    
    **Core concepts needed:** Agent modularity, classes, JSON, environment variable management, Pydantic basics and input/output validation, FastAPI endpoins, prompt engineering for JSON responses, error handling, f-string formatting, response schema definition.
    
3. Work on [**stage 3/5 AI Diet & Meal Planner**](https://hyperskill.org/projects/530/stages/3091/implement)
    
    **Core concepts needed:** Multi-agent coordination, FastAPI routing logic, unified workflows (`POST /ask`), input-output chaining.
    
4. Work on [**stage 4/5 AI Diet & Meal Planner**](https://hyperskill.org/projects/530/stages/3092/implement)
    
    **Core concepts needed:** Planner agent design, structured data generation, response handling.
    
5. Work on [**stage 5/5 AI Diet & Meal Planner**](https://hyperskill.org/projects/530/stages/3093/implement)
    
    **Core concepts needed:** Structured logging with Python, basic monitoring, observability practices, Docker containerization.
    

## Wrapping Up

You've built two agent systems: one that serves a FastAPI application and another that reviews GitHub pull requests using a multi-agent workflow. You're now working with agents that maintain state, execute tools, and coordinate with each other.

Next, you'll learn vector databases for knowledge storage and retrieval. This lets your systems access and search through large amounts of unstructured data.

**See you in Module 3: Vector Databases**