# Getting Started with the Lab

1. After the environment has been set up, your browser will load a virtual machine (JumpVM), use this virtual machine throughout the workshop to perform the lab. You can see the number on the bottom of the lab guide to switch to different exercises in the lab guide.

   ![](./Media/gettingstartedpagenew1.png)
 
1. To get the lab environment details, you can select the **Environment Details** tab. Additionally, the credentials will also be emailed to your registered email address. You can also open the Lab Guide in a separate and full window by selecting the **Split Window** from the lower right corner. Also, you can start, stop, and restart virtual machines from the **Resources** tab.

    ![](./Media/gettingstartedpagenew22.png.png)
   
   > You will see the SUFFIX value on the **Environment Details** tab; use it wherever you see SUFFIX or DeploymentID in lab steps.
 
## Login to the Azure Portal

1. In the JumpVM, click on the Azure portal shortcut of the Microsoft Edge browser, which is created on the desktop.

   ![](./Media/gettingstartpage3.png)

1. On the **Sign in to Microsoft Azure** tab, you will see the login screen. Enter the following email or username, and click on **Next**. 

   * **Email/Username**: **<inject key="AzureAdUserEmail"></inject>**

     ![](./Media/img4.png)
     
1. Now enter the following password and click on **Sign in**.
   
   * **Password**: **<inject key="AzureAdUserPassword"></inject>**

     ![](./Media/img5.png)

1. If **Action required** pop-up window appears, click on **Ask later**.

   ![](./Media/ask-later-01.png)
   
1. If you see the pop-up **Stay Signed in?**, select **No**.

      ![](./Media/img7.png)

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, select **Cancel** to skip the tour.
   
1. Now that you will see the Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

   ![](./Media/img10.png)

1. In the **Resource groups**, click on **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource group.

   ![](./Media/resource-group.png)

1. In the **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource groups, verify the resources present in it.

   ![](./Media/resources.png)

## Verify and Review the values of Azure Resources 

In this task, verification, and retrieval of specific values, including End Point, Connection String, and Key for the designated resources.

   - Azure OpenAI : **OpenAIService-<inject key="DeploymentID" enableCopy="false"/>** 
   - Azure Cosmos DB account : **cosmos-<inject key="DeploymentID" enableCopy="false"/>**
   - Search Service : **acs-<inject key="DeploymentID" enableCopy="false"/>**

1. To verify the deployment model names for "**deploymentOrModelId**" and "**embeddingDeploymentOrModelId**" follow the below steps:
   
      - In Azure Portal, click on **Resource groups** from the Navigate panel.

      - From the Resource groups page, click on **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>**.

         ![](./Media/image-rg-1.png)

      - In the **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>**, from the **Overview (1)** tab select the **OpenAIService-<inject key="DeploymentID" enableCopy="false"/> (2)**.

        ![](./Media/n1.png)

      - In the **Overview** **(1)** page, click on **Go to Azure AI Foundry portal** (2).

         ![](./Media/n2.png) 
   
      - In the **Azure AI Foundry**, select **Deployments (1)**, under the Shared Resources section.

      - In the **Deployments** blade of Azure AI Studio, click on **gpt-4** model name **(2)** and verify the **deployment name** of gpt-4 model **(3)**.

          ![](./Media/n3.png)
        
          ![](./Media/n4.png)
      
      -  Navigate back to the **Deployment (1)** page

      - In the Deployments blade of Azure AI Foundry, click on **text-embedding-ada-002 model name (2)** and verify the **deployment name** of **text-embedding-ada-002 model**.
        
         ![](./Media/n5.png)

         ![](./Media/n6.png)

1. To verify the values for **endpoint** and **apiKey** follow the below steps:

   -  Navigate back to the tab displaying **Azure portal**. 

   -  In the **OpenAIService-<inject key="DeploymentID" enableCopy="false"/>** blade under **Resource Management** section, select **Keys and Endpoint (1)**, verify the **KEY1 (1)**,**Endpoint (2)** and copy it to clipboard.
     
      ![](./Media/n7.png)

1. To verify the values for  "azureCognitiveSearchEndpoint", "azureCognitiveSearchApiKey", follow below steps:
   
   - Navigate back to **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource group.

   - On the **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** page, select **acs-<inject key="DeploymentID" enableCopy="false"/>** from resources list.

      ![](./Media/image-rg-12.png)
 
   - On **acs-<inject key="DeploymentID" enableCopy="false"/>** blade, verify the **URL**.
   
      ![](./Media/image-rg-13.png)

   - On **acs-<inject key="DeploymentID" enableCopy="false"/>** blade, under **Settings** section, verify the **Primary admin Key** value.
   
      ![](./Media/image-rg-14.png)

1. To verify the values for "**cosmosDbUri**" and "**cosmosDbName**," please follow the steps below:

   - Navigative back to resource group **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource group page, select **cosmos-<inject key="DeploymentID" enableCopy="false"/>** from resources list.

     ![](./Media/image-rg-15.png)

   - On **cosmos-<inject key="DeploymentID" enableCopy="false"/>** verify the **URL**.
     
     ![](./Media/image-rg-16.png)

   - On **cosmos-<inject key="DeploymentID" enableCopy="false"/>** under **Settings**, select **Keys** and verify the value of the **Cosmos DB Primary Connection String**.

     ![](./Media/cs.png)

1. To obtain the values for  "**blobServiceUri**", please follow the steps below:

   - Navigative back to resource group **miyagi-rg-<inject key="DeploymentID" enableCopy="false"/>** resource group page, select **miyagiblobstorge<inject key="DeploymentID" enableCopy="false"/>** from resources list.

     ![](./Media/select-storage-account.png)

   - In the **miyagiblobstorge<inject key="DeploymentID" enableCopy="false"/>** storage account from the left menu select **Endpoints** **(1)** under Settings verify the **Blob service** **(2)** under Blob service.

     ![](./Media/blob-storage-endpoint.png)

## Support Contact
 
The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:
- Email Support: cloudlabs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support

Now, click on **Next** from the lower right corner to move on to the next page.
 
   ![Start Your Azure Journey](./Media/n8.png)
 
### Happy Learning!!
