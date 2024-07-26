# Build Intelligent Apps with Microsoft's Copilot Stack & Azure OpenAI

### Overall Estimated Duration: 4 Hours

## Overview

In this lab, you will gain a strong understanding of Generative AI basics, Azure Open AI, Retrieval Augmented Generation (RAG) patterns, Semantic Kernel, and how to utilize these concepts to create your own Copilot for your business needs. You will also explore use cases that showcase Copilot product experiences. Using Microsoft's Copilot stack and practical use cases this lab will guide you in envisioning and creating intelligent systems that integrate foundation models resulting in improved productivity and hyper-personalized product experiences. 

## Objective

- **Verify and Retrieve the values of Azure Resources**: Verify and Retrieve the values to ensure the proper configuration and connectivity of the Azure resources.
- **Run Miyagi App Locally** : Configure the Miyagi App, implement the Recommendation service, deploy the frontend locally, optimize data retrieval with Azure AI Search, and explore the app and service for a personalized user experience. You will successfully configure the Miyagi app, implement and run the Recommendation service and frontend locally, persist embeddings in Azure AI Search, and personalize your exploration of the app and service.
- **Containerizing Miyagi UI and Recommendation service to Azure Kubernetes Service(AKS)** : Containerize and deploy Miyagi UI and recommendation services to AKS, configuring Kubernetes, pushing Docker images to ACR, and verifying deployment via service endpoints. Successfully deployed AKS services and built Docker images for both the Miyagi UI and Recommendation service. After pushing the Recommendation service image to the container registry, AKS pods were deployed, ensuring a streamlined and operational deployment pipeline.
- **Explore and Verify the Containerized Miyagi UI and Recommendation service in AKS**: Deploy and verify Miyagi UI and Recommendation services on AKS, testing APIs and accessing the UI through Ingress endpoints to ensure functionality. Successfully explored the Recommendation service and Miyagi App in AKS by utilizing the Ingress Endpoint, gaining insights into their deployment and access configurations. This exercise enhanced understanding of managing and routing traffic within Kubernetes environments.
- **Expose Open AI through APIM**: Verify and create APIs in the API Management service to update the Docker image for the Recommendation service, ensuring the optimization and maintenance of containerized applications. Upon completing this exercise, the user will have successfully deployed and configured an API Management service, implemented policies and roles, updated and revised the Recommendation service via Docker and AKS, and set up Event Hub Logging with validated inputs.
- **Getting Started with Your Own Copilot**: Semantic Kernel is an SDK that integrates Large Language Models (LLMs) with languages like C#, Python, and Java by allowing the creation of easily chainable plugins. You will have successfully configured and executed the Semantic Kernel sample, demonstrating your ability to integrate and utilize kernel functionalities. Additionally, you'll achieve a fully configured Azure Cognitive Search, enabling advanced search capabilities within your application.
  
## Pre-requisites

- Understanding of Generative AI basics
- Familiarity with Azure Open AI
- Experience with Semantic Kernel

## Architecture

Miyagi's architecture uses AI for hyper-personalized user interactions, transforming applications with Semantic Kernel skills and advanced prompt engineering. It features scalable microservices and an event-driven backbone, evolving with new AI models. The frontend offers personalized experiences similar to Microsoft Copilot.

It integrates Azure Functions, AKS, and Apache Kafka for seamless communication, with data managed by Cosmos DB and Azure Storage. Miyagi exemplifies advanced AI and Azure services for future-ready, intelligent applications.

## Architecture Diagram

   ![](../../Lab-Scenario-Preview/sk-memory-orchestration.png)

## Explanation of Components

- **Azure OpenAI**: Azure OpenAI integrates OpenAI's language models into Microsoft's Azure cloud, enabling scalable AI solutions for natural language processing and automation.
- **AI Search**: Is a cloud service that enables powerful and flexible search capabilities, including full-text search and AI-powered features.
- **Azure Functions**: Run code in response to events without managing servers. Scales automatically based on demand.
- **AKS (Azure Kubernetes Service)**: Managed Kubernetes service for container orchestration and scaling.
- **Apache Kafka**: Handles real-time data streaming and event processing.
- **Cosmos DB**: Globally distributed, multi-model database with low latency and high availability.
- **Azure Storage**: Scalable storage for blobs, files, queues, and tables.
- **Bing Search**: Lets you add Bing search features to your apps. It provides APIs for web, image, video, and news searches.

> [!IMPORTANT]<br>
> **For a smoother experience during the hands-on lab, it's important to thoroughly review both the instructions and the accompanying notes. This will help you navigate through the tasks with ease and confidence.**

This hands-on-lab will guide you to create intelligent systems with Microsoft's Copilot stack, leveraging Generative AI and RAG patterns for enhanced productivity and personalized experiences.

## Happy Learning!!
