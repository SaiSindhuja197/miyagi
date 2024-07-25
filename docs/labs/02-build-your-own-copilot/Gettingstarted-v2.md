# Build Intelligent Apps with Microsoft's Copilot Stack & Azure OpenAI

### Overall Estimated Duration: 240 minutes

## Overview

In this lab, you will gain a strong understanding of Generative AI basics, Azure Open AI, Retrieval Augmented Generation (RAG) patterns, Semantic Kernel, and how to utilize these concepts to create your own Copilot for your business needs. You will also explore use cases that showcase Copilot product experiences. Using Microsoft's Copilot stack and practical use cases this lab will guide you in envisioning and creating intelligent systems that integrate foundation models resulting in improved productivity and hyper-personalized product experiences. 

Here are the labs you will be performing in this lab:

- Lab 1: Verify and Retrieve the values of Azure Resources (optional)
- Lab 2: Run Miyagi App Locally
- Lab 3.1: Containerizing Miyagi UI and Recommendation service to Azure Kubernetes Service(AKS)
- Lab 3.2: Explore and Verify the Containerized Miyagi UI and Recommendation service in AKS
- Lab 4: Expose Open AI through APIM
- Lab 5: Getting Started with Your Own Copilot

## Objective

By the end of this lab, you will achieve the following:

- Comprehend the transformative potential of Azure AI services and Copilot Stack in revolutionizing every facet of AI app development.
- Acquire hands-on experience in AI-driven design and user experience techniques
- Learn to effortlessly integrate foundation models into backend services, data processing, and frontend development
- Build an AI-infused app from the ground up during the hands-on project
- Implement Agents using Assistants API, Code Interpretor, and Retrieval intefaces.

## Pre-requisites

- Understanding of Generative AI basics
- Familiarity with Azure Open AI
- Experience with Semantic Kernel

## Architecture

Miyagi's architecture uses AI for hyper-personalized user interactions, transforming applications with Semantic Kernel skills and advanced prompt engineering. It features scalable microservices and an event-driven backbone, evolving with new AI models. The frontend offers personalized experiences similar to Microsoft Copilots.

It integrates Azure Functions, AKS/ACA, and Apache Kafka for seamless communication, with data managed by Cosmos DB, Azure DB for PostgreSQL, Azure Redis Cache, and Azure Storage. GitHub Actions streamlines development and deployment. Miyagi exemplifies advanced AI and Azure services for future-ready, intelligent applications.

## Architecture Diagram

   ![](https://github.com/CloudLabsAI-Azure/miyagi/blob/main/docs/Lab-Scenario-Preview/sk-memory-orchestration.png)
      
## Getting Started with the Lab

1. After the environment has been set up, your browser will load a virtual machine (JumpVM), use this virtual machine throughout the workshop to perform the lab. You can see the number on the bottom of the lab guide to switch to different exercises in the lab guide.

   ![](./Media/gettingstartedpagenew1-v2.png)
 
1. To get the lab environment details, you can select the **Environment** tab. Additionally, the credentials will also be emailed to your registered email address. You can also open the Lab Guide in a separate and full window by selecting the **Split Window** from the lower right corner. Also, you can start, stop, and restart virtual machines from the **Resources** tab.

    ![](./Media/gettingstartedpagenew2-v2.png)
   
   > You will see the SUFFIX value on the **Environment** tab; use it wherever you see SUFFIX or DeploymentID in lab steps.
 
## Login to the Azure Portal

1. Minimize the **Docker Desktop** by click on **Minimize** button.

   ![](./Media/miyagi-image1.png)

   - If you face any issue A WSL distro Docker Desktop relies on has exited unexpectedly. This usually happens as a result of an external entity terminating WSL, click on **Restart** Button.

      ![](./Media/docker-issue.png)

1. In the JumpVM, click on the Azure portal shortcut of the Microsoft Edge browser, which is created on the desktop.

   ![](./Media/gettingstartpage3.png)

1. On the **Sign in to Microsoft Azure** tab, you will see the login screen. Enter the following email or username, and click on **Next**. 

   * **Email/Username**: **<inject key="AzureAdUserEmail"></inject>**

     ![](./Media/miyagi-image2.png)
     
1. Now enter the following password and click on **Sign in**.
   
   * **Password**: **<inject key="AzureAdUserPassword"></inject>**

     ![](./Media/miyagi-image3.png)
   
1. If you see the pop-up **Stay Signed in?**, select **No**.

   ![](./Media/miyagi-image4.png)

1. If a **Welcome to Microsoft Azure** popup window appears, select **Cancel** to skip the tour.

    ![](./Media/miyagi-image5.png)
   
1. Now that you will see the Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

   ![](./Media/miyagi-image6.png)

1. In the **Resource groups**, click on **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource group.

   ![](./Media/miyagi-image7.png)

1. In the **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource groups, verify the resources present in it.

   ![](./Media/miyagi-image8.png)

> [!IMPORTANT]<br>
> **For a smoother experience during the hands-on lab, it's important to thoroughly review both the instructions and the accompanying notes. This will help you navigate through the tasks with ease and confidence.**

This hands-on-lab will guide you in envisioning and creating intelligent systems that integrate foundation models, resulting in improved productivity and hyper-personalized product experiences.

## Happy Learning!!
