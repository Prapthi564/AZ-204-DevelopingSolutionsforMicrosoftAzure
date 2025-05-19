# AZ204: Developing Solutions for Microsoft Azure

Welcome to your AZ-204-: Developing Solutions for Microsoft Azure Workshop! We've prepared a seamless environment for you to explore and learn Azure Services. Let's begin by making the most of this experience.

# Lab 01: Build a web application on Azure platform as a service offering

### Overall Estimated timing: 60 minutes

## Overview

In this hands-on lab, you’ll gain practical experience in building and deploying a web application on Azure using the Platform as a Service (PaaS) model. You will begin by creating a web application hosted on Azure App Service, a fully managed web hosting platform. Next, you’ll learn how to deploy existing web application files using the Apache Kudu zip deployment method, enabling streamlined and efficient file uploads. Finally, you’ll verify the deployment by viewing and testing the live web application. By the end of this lab, you’ll be equipped with the foundational skills to deploy and manage web applications in Azure using PaaS offerings.

## Objectives

By the end of this lab, you will be able to build and deploy a full-stack web application on Azure using Azure Storage and the Web Apps feature of Azure App Service.

+ Exercise 1: Build a backend API by using Azure Storage and the Web Apps feature of Azure App Service: In this exercise, participants will learn how to create and configure a web app in Azure and deploy a backend ASP.NET application using the Azure CLI and the Apache Kudu zip deployment utility. This includes setting up the Web Apps feature of Azure App Service and integrating it with Azure Storage to enable backend functionality.

+ Exercise 2: Build a front-end web application by using Azure Web Apps: In this exercise, participants will learn how to create an Azure Web App and deploy the front-end code of an existing web application to the cloud. This includes provisioning the web app resource and using deployment tools to host the application on Azure’s PaaS environment.


## Pre-requisites

- A basic understanding of web application architecture (frontend and backend components).
- Familiarity with ASP.NET web applications and core development concepts.
- Basic knowledge of command-line tools and zip file handling.

## Architecture

In this hands-on lab, the architecture flow includes several essential components.

1. Build a backend API by using Azure Storage and the Web Apps feature of Azure App Service: Learning how to create and configure a web app in Azure, deploy a backend ASP.NET application using the Azure CLI and Apache Kudu zip deployment utility, and integrate the application with Azure Storage to enable backend functionality using the Web Apps feature of Azure App Service.

1. Build a front-end web application by using Azure Web Apps: Learning how to create an Azure Web App and deploy the front-end code of an existing web application to the cloud, including provisioning the web app resource and using deployment tools to host the application on Azure’s PaaS environment.

## Architecture Diagram

![Architecture diagram depicting a user building a web application on Azure platform as a service offering.](../media/Lab01-Diagram1.png)

## Explanation of Components

1. Azure App Service: Azure App Service is a fully managed Platform as a Service (PaaS) offering from Microsoft that enables developers to build, deploy, and scale web apps and APIs quickly. It supports multiple programming languages and frameworks, including .NET, Java, Node.js, and Python, and integrates easily with other Azure services.

1. Azure Web Apps: Azure Web Apps is a feature within Azure App Service that provides a scalable hosting environment for web applications. It allows developers to deploy web apps using various deployment methods and manage them through the Azure portal, CLI, or DevOps pipelines.

1. Azure Storage: Azure Storage is Microsoft’s cloud storage solution for modern data storage scenarios. It offers scalable, durable, and secure storage for a variety of data types including blobs, files, queues, and tables. In this lab, it is used to support backend functionality for the deployed API.

# Getting Started with the Lab
 
Welcome to your AZ-204-: Developing Solutions for Microsoft Azure workshop! We've prepared a seamless environment for you to explore and learn Azure Services. Let's begin by making the most of this experience:
 
## Accessing Your Lab Environment
 
Once you're ready to dive in, your virtual machine and lab guide will be right at your fingertips within your web browser.
 
![Access Your VM and Lab Guide](../media/sg1.png)

### Virtual Machine & Lab Guide
 
Your virtual machine is your workhorse throughout the workshop. The lab guide is your roadmap to success.
 
## Exploring Your Lab Resources
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment** tab.
 
![Explore Lab Resources](../media/sg2.png)
 
## Utilizing the Split Window Feature
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the top right corner.
 
![Use the Split Window Feature](../media/sg3.png)
 
## Utilizing the Zoom In/Out Feature

To adjust the zoom level for the environment page, click the A↕ : 100% icon located next to the timer in the lab environment.

![Use the Split Window Feature](./media/sg4.png)

## Managing Your Virtual Machine
 
Feel free to start, stop, or restart your virtual machine as needed from the **Resources** tab. Your experience is in your hands!
 
![Manage Your Virtual Machine](../media/sg5.png)

## **Lab Duration Extension**

1. To extend the duration of the lab, kindly click the **Hourglass** icon in the top right corner of the lab environment. 

    ![Manage Your Virtual Machine](../Labs/Images/sg6.png)

    >**Note:** You will get the **Hourglass** icon when 10 minutes are remaining in the lab.

2. Click **OK** to extend your lab duration.
 
   ![Manage Your Virtual Machine](../Labs/Images/gext2.png)

3. If you have not extended the duration prior to when the lab is about to end, a pop-up will appear, giving you the option to extend. Click **OK** to proceed.
 
## Let's Get Started with Azure Portal
 
1. On your virtual machine, click on the Azure Portal icon as shown below:
 
    ![Launch Azure Portal](../Labs/Images/azure.png)
 
2. You'll see the **Sign into Microsoft Azure** tab. Here, enter your credentials:
 
   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>
 
      ![](../Labs/Images/image7.png)
 
3. Next, provide your password:
 
   - **Password:** <inject key="AzureAdUserPassword"></inject>
 
      ![](../Labs/Images/image8.png)

1. If you see the pop-up **Action Required**, click **Ask Later**.
   
     ![](../Labs/Images/asklater.png)

## Steps to Proceed with MFA Setup if "Ask Later" Option is Not Visible

1. At the **"More information required"** prompt, select **Next**.

1. On the **"Keep your account secure"** page, select **Next** twice.

1. **Note:** If you don’t have the Microsoft Authenticator app installed on your mobile device:

   - Open **Google Play Store** (Android) or **App Store** (iOS).
   - Search for **Microsoft Authenticator** and tap **Install**.
   - Open the **Microsoft Authenticator** app, select **Add account**, then choose **Work or school account**.

1. A **QR code** will be displayed on your computer screen.

1. In the Authenticator app, select **Scan a QR code** and scan the code displayed on your screen.

1. After scanning, click **Next** to proceed.

1. On your phone, enter the number shown on your computer screen in the Authenticator app and select **Next**.
       
1. If prompted to stay signed in, you can click "No."
 
1. If a **Welcome to Microsoft Azure** pop-up window appears, simply click "Maybe Later" to skip the tour.

1. Click **Next** from the bottom right corner to embark on your Lab journey!
 
    ![Start Your Azure Journey](../media/num.png)



