# Security Information and Event Management with Microsoft Sentinel

## Overall Estimated Duration: 4 Hours

## Overview

In this lab, you'll enable Azure Sentinel, deploy the Microsoft Sentinel Training Lab Solution, and onboard Azure resources. You'll define a hypothesis for threat hunting, create structured hunts, and use queries to analyze data. This setup enhances your skills in monitoring, detecting, and responding to security threats effectively. By engaging in these activities, you'll gain hands-on experience with Azure Sentinel, improving your ability to protect and secure your organization's IT environment.

## Objective

Understand how to deploy Azure Sentinel, configure it, and onboard cloud resources and servers. Gain skills in advanced security analytics and creating a training environment. By the end of this lab, you will be able to:

* **Deploying Azure Sentinel and Onboarding Cloud Resources and Servers**: Understand how to enable Azure Sentinel, deploy the Sentinel Training Lab Solution, and onboard Azure resources to create a robust security environment. This setup provides advanced security analytics and a training environment, enhancing your ability to monitor, detect, and respond to security threats effectively.

* **Conducting Log Analytics and Threat Hunting**: Understand how to define a hypothesis for threat hunting, create structured hunts in Microsoft Sentinel, and analyze data using queries and bookmarks. You’ll also learn to create incidents from alerts and track metrics, enhancing your threat detection and investigation skills.

## Pre-requisites

* General understanding of Security Operations
* Familiarity with networking
* Basic knowledge on log analytics

## Architecture

This architectural diagram illustrates the process of setting up and utilizing Azure Sentinel, a cloud-native security information event management (SIEM) and security orchestration automated response (SOAR) solution. It is divided into two main exercises. The first exercise focuses on onboarding Azure Sentinel, which involves creating a log analytics workspace, initializing Azure Sentinel by linking it to this workspace, and connecting various resources using data connectors. The second exercise is about conducting log analysis and threat hunting. This includes absorbing data into Azure Sentinel, connecting additional resources, and using various tools to analyze the data and hunt for potential security threats. This structured approach ensures effective security management and threat detection within a cloud environment.

## Architecture Diagram

![sentinel-architecture](../media/sentinel-architecture.png)

## Explanation of Components

- **Log Analytics Workspace**: This is the foundational component where all logs and data are collected and stored for analysis.
- **Azure Sentinel Initialization**: This step involves setting up Azure Sentinel by linking it to the previously created log analytics workspace, enabling it to start monitoring and analyzing data.
- **Data Connectors**: These are used to connect various resources (like virtual machines, applications, and other services) to Azure Sentinel, allowing it to ingest data from these sources for security monitoring.
- **Threat Analysis Tools**: These tools are used to analyze the ingested data, helping security teams to hunt for and identify potential threats. This includes various analytical tools represented by icons such as graphs and magnifying glasses.

These components work together to provide a comprehensive security management solution, enabling effective monitoring, analysis, and threat detection within a cloud environment

# Getting Started with Lab

1. Once the environment is provisioned, a virtual machine (JumpVM) and lab guide will get loaded in your browser. Use this virtual machine throughout the workshop to perform the lab. You can see the number on the lab guide bottom area to switch to different exercises in the lab guide.

   ![](../media/getting-started.png "Lab Environment")
   
1. To get the lab environment details, you can select the **Environment Details** tab. Additionally, the credentials will also be emailed to your email address provided during registration.

   ![split window](../media/getting-started.png "Lab Environment")

1. You can also view the lab guide in a separate and full window by selecting **Split Window** from the lower right corner.

   ![](../media/split-window.png "Lab Environment")

1. Actions on virtual machines such as **Start**, **Stop**, and **Restart** can be performed from the **Resources** tab.

   ![start and stop resources](../media/start-stop.png "Lab Environment")

## Login to Azure Portal
1. In the JumpVM, click on the Azure portal shortcut of the Microsoft Edge browser, which is created on the desktop.

   ![](../media/azureportal_icon.png "Lab Environment")
   
1. On the **Sign into Microsoft Azure** tab, you will see the login screen. Enter the following email/username and then click on **Next**.
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](../media/image7.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](../media/image8.png "Enter Password")
     
1. If you see the pop-up **Action Required**, click **Ask Later**.

     ![](../media/asklater.png "Action required window")
     
    > If you are getting popup **save password**, then select **Save & Turn on** option.
       
1. If you see the pop-up **Stay Signed in?**, click **No**.

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.

1. Now you will see the Azure Portal Dashboard, Click on **Resource groups** from the Navigate panel to see the resource groups.

     ![](../media/select-rg.png "Resource groups")

1. Confirm you have a resource group named **Microsoft-Sentinel** present as shown in the below screenshot. You need to use this resource group throughout the entire process of lab execution.

     ![](../media/sentinelrg.png "Resource groups")
   
1. Use the **Next** button from the lower right corner to move on to the next page.

   ![](../media/next.png "Resource groups")


> [!IMPORTANT]
*For a smoother experience during the hands-on lab, it's important to thoroughly review both the instructions and the accompanying notes. This will help you navigate through the tasks with ease and confidence.*

This hands-on lab will guide you in using Azure’s advanced tools, including OpenAI LLM, Azure AI Search, and Form Recognizer, to create intelligent systems that enhance productivity and deliver personalized experiences.

## Support Contact

The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: labs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support
  
Now, click on Next from the lower right corner to move on to the next page.

## Happy Learning!!

