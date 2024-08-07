# Security Information and Event Management with Microsoft Sentinel

## Overall Estimated Duration: 4 Hours

## Overview

In this lab, you'll enable Azure Sentinel, deploy the Microsoft Sentinel Training Lab Solution, and onboard Azure resources. You'll define a hypothesis for threat hunting, create structured hunts, and use queries to analyze data. This setup enhances your skills in monitoring, detecting, and responding to security threats effectively. By engaging in these activities, you'll gain hands-on experience with Azure Sentinel, improving your ability to protect and secure your organization's IT environment.

## Objective

* **Deploying Azure Sentinel and Onboarding Cloud Resources and Servers**: This hands-on lab aims to enable Azure Sentinel, deploy the Sentinel Training Lab Solution, and onboard Azure resources. This setup provides advanced security analytics and a training environment, enhancing your ability to monitor, detect, and respond to security threats effectively.

* **Conducting Log Analytics and Threat Hunting**:This hands-on lab guides you to define a hypothesis for threat hunting, create structured hunts in Microsoft Sentinel, and analyze data using queries and bookmarks. You’ll also learn to create incidents from alerts and track metrics, enhancing your threat detection and investigation skills.

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

## Now, click on Next from the lower right corner to move on to the next page.
