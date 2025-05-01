# Exercise 2: Introduction to Azure AI Foundry Workshop 

This lab introduces participants to the core functionalities of Azure AI Foundry, covering authentication, environment configuration, and project initialization. It lays the groundwork for utilizing AI models and developing AI-driven applications.

### Lab Overview

In this lab, you will authenticate credentials using Azure CLI, configure the AI Project Client, and validate model and search connections. You will also get hands-on experience with initializing AI projects, listing available models, and making your first chat completion request. By the end of this lab, you will have a functional AI workspace and a clear understanding of how to begin AI solution development using Azure AI Foundry.

### Estimated Time: 40 minutes

### Task 1: Authenticate your Credentials 

1. In the Visual Studio code window, in the left **explorer** panel, click on the dropdown next to **1-introduction (1)** and select **1-authentication.ipynb (2)** file.

    ![](../images/step-1.png)

1. In the top right corner of the Visual Studio Code Window, select the dropdown under **Select Kernel** option.

    ![](../images/step-15.png)

1. Select **Python Environments..**.

    ![](../images/step-4.png)

1. Select **.venv (Python 3.12.1)** which will be used as kernel for this workbook.

    ![](../images/step-5.png)

1. Click on the **Execute cell** button. Here, we are installing azure-identity package along with its related packages. If the packages are already installed, it will provide output as **Requirement already satisfied**. 

    ![](../images/step-6.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-7.png)

1. Click on the **Execute cell** button for the next code cell. Here, the commands will redirect you to login to Azure portal by sign-in with Windows login.

    ![](../images/step-8.png)

1. Select the email provided to this lab and click on **Continue**.

    ![](../images/step-9.png)

1. If you have not logged-in to the provided email, select **Work or school account** and use the below credientials to login.
        
    Username:<inject key="AzureAdUserEmail"></inject>
    
    Password:<inject key="AzureAdUserPassword"></inject>
            
    ![](../images/step-9(1).png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-10.png)

1. In the next code cell, we are testing the authentication by acquiring a token. Click on the **Execute cell** button.

    ![](../images/step-12.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-13.png)

### Task 2: Configuring the Environment

1. In the left **explorer** panel, click on the dropdown next to **1-introduction (1)** and select **2-environment_setup.ipynb (2)** file.

    ![](../images/step-14.png)

1. In the top right corner of the Visual Studio Code Window, select the dropdown under **Select Kernel** option.

    ![](../images/step-15.png)

1. Select **.venv (Python 3.12.1)** which will be used as kernel for this workbook.

    ![](../images/step-18.png)

1. Click on the **Execute cell** button. Here, we are installing azure-ai-projects package along with its related packages. If the packages are already installed, it will provide output as **Requirement already satisfied**. 

    ![](../images/step-19.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-20.png)

1. Scroll down and click on the **Execute cell** button for the next code cell. Here, we are verifying the Azure credentials and setup.

    ![](../images/step-21.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-22.png)

1. Click on the **Execute cell** button for the next code cell. Here, we are initializing Project connection with the credentials.

    ![](../images/step-23.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-24.png)

1. Click on the **Execute cell** button for the next code cell. Here, we are validating all connections to components used in this lab.

    ![](../images/step-25.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-26.png)
    > Note: To verify the complete output block, scroll down at the end of output and click on ***scrollable element***.
        
     ![](../images/step-27.png)

1. Click on the **Execute cell** button for the next code cell. Here, we are validating connections for **Azure AI search** and **Azure Open AI**.

    ![](../images/step-28.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-29.png)

### Task 3: Quick Start to the Workshop

1. In the left **explorer** panel, click on the dropdown next to **1-introduction (1)** and select **3-quick_start.ipynb (2)** file.

    ![](../images/step-30.png)

1. In the top right corner of the Visual Studio Code Window, select the dropdown under **Select Kernel** option.

    ![](../images/step-31.png)

1. Select **.venv (Python 3.12.1)** which will be used as kernel for this workbook.

    ![](../images/step-34.png)

1. Click on the **Execute cell** button. Here, we are importing necessary libraries and initializing credentials.

    ![](../images/step-35.png)

1. Click on the **Execute cell** button for the next code cell. Here, we are initializing Project connection with the credentials.

    ![](../images/step-36.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-37.png)

1. Click on the **Execute cell** button for the next code cell. Here, we are providing single line prompt and make a simple completion request.

    ![](../images/step-38.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/step-39.png)
    >Note: The output response might differ when this code cell is executed multiple times.

1. Click on the **Execute cell** button for the next code cell. Here, we are creating an agent with interpreter tool and a conversation thread and send it to an AI model which will process and provide an visualization output in image format.

    ![](../images/step-40.png)

1. When the cell executes successfully, output will be expected as below. There will be an image saved in the same directory.

    ![](../images/step-41.png)

    ![](../images/step-42.png)
