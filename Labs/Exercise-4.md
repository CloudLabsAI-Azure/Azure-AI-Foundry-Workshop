# Exercise 4: Agent Development 

This lab focuses on building AI agents using the Azure AI Foundry SDK, enabling them to perform specialized tasks such as health coaching, nutrition analysis, and intelligent search. By leveraging agentic AI principles, participants will create autonomous AI systems capable of reasoning, decision-making, and interacting with external tools to enhance their capabilities.

### Lab Overview

In this lab, you will develop AI agents tailored for health and fitness applications. You will begin by creating a wellness assistant capable of providing fitness and nutrition guidance. Then, you'll extend its functionality by incorporating tools like a code interpreter for BMI calculations, a file search agent for retrieving health resources, and a Bing Grounding tool for real-time web-based insights. Additionally, you’ll integrate Azure AI Search for enhanced data retrieval and explore the interaction between AI agents and Azure Functions for event-driven automation. By completing this lab, you will gain hands-on experience in building and enhancing AI agents with multi-agent collaboration, real-world reasoning, and dynamic task execution.

### Estimated Time: 40 minutes

### Task 1: Azure AI Foundry SDKs to create a playful health and fitness assistant

1. From the left pane in the Visual Studio Code window, click on the dropdown next to **2-notebooks** (1), then click on the dropdown next to **2-agent_service** (2) and select **1-basics.ipynb** (3) file.

    ![](../images/ex4-task1-1.png)

1. In the top left corner of the Visual Studio Code Window, select the dropdown under **Select Kernel (1)** option and choose **.venv(Python 3.12.1)** (2) and select the same in the option that appears under the search bar.

   ![](/images/ai2.png)

1. Click on the **Execute cell** button. Here, we are loading the environment with the variables from .env file and initializing the client.

    ![](../images/ex4-task1-2.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task1-3.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task1-4.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task1-5.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task1-6.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task1-7.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task1-8.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task1-9.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task1-10.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task1-11.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task1-12.png)

### Task 2: Health Calculator Agent

1. Click on the **2-code_interpreter.ipynb** link to proceed with the next notebook.

    ![](../images/ex4-task2-1.png)

1. In the top left corner of the Visual Studio Code Window, select the dropdown under **Select Kernel (1)** option and choose **.venv(Python 3.12.1)** (2) and select the same in the option that appears under the search bar.

   ![](/images/ai2.png)

1. Click on the **Execute cell** button. Here, we are loading the environment with the variables from .env file, initializing the client and creating a csv file.

    ![](../images/ex4-task2-2.png)

1. When the cell executes successfully, output will be expected as below. Also, notice a csv file with name **nutrition_data.csv** is created in the left pane.

    ![](../images/ex4-task2-3.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task2-4.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task2-5.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task2-6.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task2-7.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task2-8.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task2-9.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task2-10.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task2-11.png)

    ![](../images/ex4-task2-12.png)

1. Click on the **Execute cell** button for the next code cell.

    ![](../images/ex4-task2-13.png)

1. When the cell executes successfully, output will be expected as below.

    ![](../images/ex4-task2-14.png)


### Task 3: Health Resource Search Agent

### Task 4: Health & Fitness Agent with Bing Grounding

### Task 5: AI Search + Agent Service: Fitness-Fun Example

### Task 6: Fitness Fun: Azure Functions + AI Agent