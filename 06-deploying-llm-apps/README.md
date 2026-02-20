# 6. Deploying LLM-Based Apps

Start of module 6: April 20, 2026       
End of module 6: April 26, 2026         
Duration: 1 week          
Time estimate: ~12 hours per week, ~12 hours total    

This module is all about shipping your app. You’ll learn how to package your project with FastAPI, use Docker for reproducibility, manage secrets and configs, and deploy to the cloud. By the end, your prototype will become a testable, production-ready service.

## Learning Outcomes

By the end of this module, you’ll:

- Package your RAG app for deployment with FastAPI and Docker
- Understand deployment options and trade-offs
- Manage environment variables, secrets, and logging
- Set up lightweight infrastructure for running AI apps
- Practice reproducible, version-controlled releases

## Step 1 – Watch the session: Deployment of LLM-based apps

The details for this session will be shared shortly.


## Step 2 – Project: LLM Evals Deploy
**FULL TRACK** / **SHORT TRACK**

For the second step of this sprint, you’ll deploy your application in a production-ready environment. This project is a continuation of LLM Evals: Preparing for production, but we provide the started code in the project itself.

You’ll learn how to:

- Create REST API endpoints with **FastAPI**
- Use **Docker** for containerization and reproducibility
- Manage environment variables and secrets securely
- Deploy on **AWS Cloud** (and other hosting providers, such as Qdrant cloud)
- Ship and share your application for testing and usage

Start the [**LLM Evals Deploy**](https://github.com/hyperskill-content/AI-Engineer-Deploy) project

1. Work on [**stage 1/4 – API Endpoint**](https://github.com/hyperskill-content/AI-Engineer-Deploy/blob/main/tasks/task_1.md)
    
    **Core concepts needed:** FastAPI web service setup, POST endpoint, Pydantic schemas, uvicorn, microservice architecture, REST API communication, JSON request/response handling.
    
2. Work on [**stage 2/4 – Refactoring to Cloud Services**](https://github.com/hyperskill-content/AI-Engineer-Deploy/blob/main/tasks/task_2.md)
    
    **Core concepts needed:** Migration from local to managed services, Qdrant and Langfuse Cloud setup, Redis Cloud database with connection string, replacing local service calls with cloud service endpoints.
    
3. Work on [**stage 3/4 – Production-ready Docker Image**](https://github.com/hyperskill-content/AI-Engineer-Deploy/blob/main/tasks/task_3.md)
    
    **Core concepts needed:** Docker production image, .dockerignore for build context optimization, multi-stage builds with builder and runtime stages, installing build tools, optimizing image size, adding basic security practices. 
    
4. Work on [**stage 4/4 – Deployment to AWS**](https://github.com/hyperskill-content/AI-Engineer-Deploy/blob/main/tasks/task_4.md)
    
    **Core concepts needed:** AWS account setup with zero-spend budget, IAM user with AdministratorAccess policy, setting up MFA for root user, AWS CLI access keys, Amazon ECR public repository, EC2 instance launch, SSH key pair creation, security group with SSH/HTTP/HTTPS traffic, Docker Engine installation on EC2, post-installation Docker user permissions.
    

## Step 3 – Open hours: Deployment

In this timeslot, you’ll be able to:

- Clarify deployment setups with FastAPI and Docker
- Ask questions about managing secrets, logging, and environment variables
- Get feedback on lightweight infrastructure options for AI apps
- Discuss trade-offs between different deployment strategies
- Learn best practices for reproducible, version-controlled releases

**Date & Time, link:** The meeting details will be shared via Discord and the calendar

## Wrapping Up

Congrats — you’ve taken your app from local prototype to a real, deployable service. Now your project can be tested, shared, and scaled in real environments.