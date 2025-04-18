# Exercise 1: Set Up the Environment

This lab focuses on setting up the foundational environment for developing AI applications using the Azure AI Foundry SDK. Participants will establish their development workspace, configure necessary connections, and authenticate credentials to ensure seamless integration with Azure AI services.

### Lab Overview

In this lab, you will set up the AI Foundry environment and configuring a Python-based development environment. You'll deploy essential connections and verify access to models, ensuring smooth execution of AI workflows. By completing this setup, you will be prepared to leverage Azure AI Foundry for building advanced AI solutions.

## Estimated Time: 40 minutes

## Task 1: Environment Setup in the Azure Portal

1. In the Azure portal, search for **azure foundry (1)** and select **Azure AI Foundry (2)**.

   ![](../images/b1.png)

1. Click on the **hub-demo** resource to navigate to the Azure AI Hub.

   ![](../images/b2.png)

1. Click on **Launch Azure AI Foundry** option.

   ![](../images/b3.png)

1. In the window that appears, select **Agents Projects resource** to move to the Azure AI Foundry project.

   ![](../images/b4.png)

1. From the left navigation pane select **Models + Endpoints** option.

   ![](../images/b6.png)

1. Select **+ Deploy Model** drop down and select **Deploy a Base Model**

   ![](../images/b7.png)

1. Search for and select **DeepSeek-R1 (1)** model and click on **Confirm (2)**.

   ![](../images/b9.png)

1. In the pop-up that appears, click on **Agree and Proceed**.

1. In the deploy model window, click on **Deploy** to deploy the model.

   ![](../images/b10.png)

1. Once the model is deployed click on **Models+Endpoints** from the left navigation pane to deploy **Phi-4 model.**

1. Select **+ Deploy Model** drop down and select **Deploy a Base Model**.

1. Search for and select **Phi-4 (1)** model and click on **Confirm (2)**.

   ![](../images/b12.png)

1. In the pop-up that appears, click on **Agree and Proceed**.

1. In the deploy model window, click on **Deploy** to deploy the model.

   ![](../images/b13.png)

1. Once the required models are deployed, we need to add the connections for the Bing resource and Azure AI Search resource in the Azure AI Foundry portal. Click on **Connected Resources (1)** from the left pane and click on **+ New Connection (2)**.

   ![](../images/b17.png)

1. In the window that appears, select **Azure AI Search** resource.

   ![](../images/b18.png)

1. Click on **Add Connection** by leaving everything else as default and once it is connected, you can click on **Close**.

   ![](../images/b19.png)

1. Now let us add another connection.Click on **New Connection**.

1. In the window that appears scroll down and select **Grounding with Bing Search** option.

   ![](../images/b20.png)

1. Leave everything else as default and click on **Add Connection** and once it is added, you can click on close.

   ![](../images/b21.png)

1. Once the connections are added, we need to add the user with developer permission. Click on **Users (1)** from the left pane and click on **+ New User (2)**.

   ![](../images/ex1-select-users.png)

1. Provide your **Username (1)** in place of New user and select the Role as **Azure AI Developer (2)**. Click on **Add (3)**.

   ![](../images/ex1-add-dev-role.png)

## Task 2: Environment Setup in Visual Studio Code

1. Minimize your browser window and from the Lab VM select **Visual Studio Code**.

   ![](../images/b22.png)

1. From the left pane, select **Explorer** (1) and click on **Open Folder** (2)

   ![](../images/b24.png)

1. Navigate to C: Drive and choose **ai-foundry-workshop**(1) and click on **Select Folder** (2). In the prompt that appears, select **Yes I trust the authors**.

    ![](../images/b25.png)

1. In the Visual Studio Code window, click on the **elipsis** (3) and choose **Terminal** (2) and click on **New Terminal** (3)

   ![](../images/b23.png)

1. In the powershell terminal, let us first create the uv environmment by running the following command in the terminal.

   ```
     uv venv
    ```

1. Once the uv environment is created, we need to activate it by running the following command.

    ```
    .venv\Scripts\activate
    ```

1. Now, lets install the required packages in the isolated environment.The below command installs the  core Azure AI SDKs and Jupyter requirements in the uv environment.

    ```
    uv pip install azure-identity azure-ai-projects azure-ai-inference[opentelemetry] azure-search-documents azure-ai-evaluation azure-monitor-opentelemetry
    ```
   
1. Run the following command to install the required packages for Jupyter 

     ```
     uv pip install ipykernel jupyterlab notebook
    ```
1. Run the following command to register the kernel with Jupyter.
  
    ```
    python -m ipykernel install --user --name=.venv --display-name="Python (.venv)"
    ```
1. Run the following command to install the required packages.

   ```
   uv pip install -r requirements.txt --prerelease=allow
    ```
