# Build Intelligent Apps with Microsoft's Copilot Stack & Azure OpenAI

### Overall Estimated Duration: 4 Hours

## Overview

In this lab, you will gain a strong understanding of Generative AI basics, Azure Open AI, Retrieval Augmented Generation (RAG) patterns, Semantic Kernel, and how to utilize these concepts to create your own Copilot for your business needs. You will also explore use cases that showcase Copilot product experiences. Using Microsoft's Copilot stack and practical use cases this lab will guide you in envisioning and creating intelligent systems that integrate foundation models resulting in improved productivity and hyper-personalized product experiences. 

## Objective

- **Verify and Retrieve the values of Azure Resources**: Verify and Retrieve the values to ensure the proper configuration and connectivity of the Azure resources.
- **Run Miyagi App Locally** : Configure the Miyagi App, implement the Recommendation service, deploy the frontend locally, optimize data retrieval with Azure AI Search, and explore the app and service for a personalized user experience.
- **Containerizing Miyagi UI and Recommendation service to Azure Kubernetes Service(AKS)** : Containerize and deploy Miyagi UI and recommendation services to AKS, configuring Kubernetes, pushing Docker images to ACR, and verifying deployment via service endpoints.
- **Explore and Verify the Containerized Miyagi UI and Recommendation service in AKS**: Deploy and verify Miyagi UI and Recommendation services on AKS, testing APIs and accessing the UI through Ingress endpoints to ensure functionality.
- **Expose Open AI through APIM**: Verify and create APIs in the API Management service to update the Docker image for the Recommendation service, ensuring the optimization and maintenance of containerized applications.
- **Getting Started with Your Own Copilot**: Semantic Kernel is an SDK that integrates Large Language Models (LLMs) with languages like C#, Python, and Java by allowing the creation of easily chainable plugins.
  
## Pre-requisites

- Understanding of Generative AI basics
- Familiarity with Azure Open AI
- Experience with Semantic Kernel

## Architecture

Miyagi's architecture uses AI for hyper-personalized user interactions, transforming applications with Semantic Kernel skills and advanced prompt engineering. It features scalable microservices and an event-driven backbone, evolving with new AI models. The frontend offers personalized experiences similar to Microsoft Copilot.

It integrates Azure Functions, AKS, and Apache Kafka for seamless communication, with data managed by Cosmos DB, Azure DB for PostgreSQL, Azure Redis Cache, and Azure Storage. GitHub Actions streamlines development and deployment. Miyagi exemplifies advanced AI and Azure services for future-ready, intelligent applications.

## Architecture Diagram

   ![](https://github.com/CloudLabsAI-Azure/miyagi/blob/main/docs/Lab-Scenario-Preview/sk-memory-orchestration.png)

## Explanation of Components

- **Azure Functions**: Run code in response to events without managing servers. Scales automatically based on demand.
- **AKS**: Managed Kubernetes service for container orchestration and scaling.
- **ACA**: Fully managed service for running containerized apps without managing infrastructure.
- **Apache Kafka**: Handles real-time data streaming and event processing.
- **Cosmos DB**: Globally distributed, multi-model database with low latency and high availability.
- **Azure DB for PostgreSQL**: Managed relational database with robust features.
- **Azure Redis Cache**: High-performance, in-memory caching.
- **Azure Storage**: Scalable storage for blobs, files, queues, and tables.
- **GitHub Actions**: Automates CI/CD workflows directly from GitHub.

> [!IMPORTANT]<br>
> **For a smoother experience during the hands-on lab, it's important to thoroughly review both the instructions and the accompanying notes. This will help you navigate through the tasks with ease and confidence.**

This hands-on-lab will guide you to create intelligent systems with Microsoft's Copilot stack, leveraging Generative AI and RAG patterns for enhanced productivity and personalized experiences.

## Happy Learning!!
