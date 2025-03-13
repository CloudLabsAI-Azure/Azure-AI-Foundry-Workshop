# Exercise 1: Set Up the Environment

This lab focuses on setting up the foundational environment for developing AI applications using the Azure AI Foundry SDK. Participants will establish their development workspace, configure necessary connections, and authenticate credentials to ensure seamless integration with Azure AI services.

### Lab Overview

In this lab, you will set up the AI Foundry environment configuring a Python-based development environment. You'll deploy essential connections and verify access to models, ensuring smooth execution of AI workflows. By completing this setup, you will be prepared to leverage Azure AI Foundry for building advanced AI solutions.

## Task 1: Environment Setup 

1. In the Azure portal,search for and select **Bing Resource** to create a grounding with Bing resource.

   ![](/images/b14.png)

1. Click on the drop-down next to **Add** and select **Grounding with Bing Search** resource.

   ![](/images/b15.png)

1. In the window that appears, fill in the following details:

   - Subscription- Choose the default Subscription.(1)
   - Resource Group- Choose **foundry** (2)
   - Name: **Bing-Search** (3)
   - Pricing Tier: **Grounding with Bing Search** (4)
   - Terms: Check the Box (5)
   - Click on **Review + Create** (5) and click on **Create**

     ![](/images/b16.png)









1. In the Azure portal, search for and select Azure AI Hub Resource.

   ![](/images/b1.png)

1. Click on the **hub-demo** resource to navigate to the Azure AI Hub.

   ![](/images/b2.png)

1. Click on **Launch Azure AI Foundry** option.

   ![](/images/b3.png)

1. In the window that appears, select **Agents Projects resource** to move to the Azure AI Foundry project.

   ![](/images/b4.png)

1. From the left navigation pane select **Models + Endpoints** option.

   ![](/images/b6.png)

1. Select **+ Deploy Model** drop down and select **Deploy a Base Model**

   ![](/images/b7.png)

1. Search for and select **DeepSeek R1** model and click on **Confirm**.

   ![](/images/b9.png)

1. In the pop-up that apppears, click on **Agree and Proceed**

1. In the deploy model window, click on **Deploy** to deploy the model.

   ![](/images/b10.png)

1. Once the model is deployed click on **Models+Endpoints** from the left navigation pane to deploy **Phi-4 model.**

1. Select **+ Deploy Model** drop down and select **Deploy a Base Model**.

1. Search for and select **Phi-4** model and click on **Confirm**.

   ![](/images/b12.png)

1. In the pop-up that apppears, click on **Agree and Proceed**.

1. In the deploy model window, click on **Deploy** to deploy the model.

   ![](/images/b13.png)

















