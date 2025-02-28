# CardioTriage AI

CardioTriage AI is an advanced healthcare solution designed to streamline the triage process using artificial intelligence (AI), automation, and seamless integration with various Microsoft technologies. The solution leverages Power Apps, AI Builder, Copilot Custom Agent, and Dataverse for data management, along with Microsoft Bookings and Power Automate for scheduling and process automation. 

## Table of Contents
1. [Overview](#overview)
2. [High-Level Solution Architecture](#high-level-solution-architecture)
3. [Components](#components)
    - [User Interface (Front-End)](#user-interface-front-end)
    - [AI and Data Processing](#ai-and-data-processing)
    - [Automation and Integration](#automation-and-integration)
    - [Security and Infrastructure](#security-and-infrastructure)
4. [Security](#security)
5. [Technologies Used](#technologies-used)

## Overview

CardioTriage AI integrates multiple Microsoft technologies to deliver a comprehensive solution for triaging patients in a cardiology department. The solution uses **Power Apps** as the front-end interface, with **AI Builder** and **Copilot Custom Agent** for AI-powered patient data analysis and case prioritization. The back-end is powered by **Dataverse**, providing a secure and centralized database for patient information. 

The application ensures smooth and automated operations by utilizing **Microsoft Bookings** for appointment management and **Power Automate** to streamline workflow automation. Sensitive data and access keys are securely managed in **Azure Key Vault** for enhanced security.

## High-Level Solution Architecture

### Figure 1: High-Level Solution Architecture Diagram



### User Interface (Front-End)

- **Power Apps**: The primary interface for users, including **Lab Technicians**, **Front Desk Agents**, and **Doctors**. Power Apps provides a user-friendly environment to interact with the system.
- **Front Desk Agent (Interactive Agent)**: An interactive agent designed to assist with patient check-in and gather initial information.
- **TriageMaster (Autonomous Agent)**: The core AI component powered by **AI Builder** and **Copilot Custom Agent** that analyzes patient data to determine the severity of cases and prioritize them accordingly.

### AI and Data Processing

- **AI Builder**: Utilized for building and training AI models to analyze patient symptoms, medical history, and lab results using machine learning techniques.
- **Copilot Custom Agent**: A customized version of **Microsoft Copilot** that provides conversational AI to assist users and automate tasks specific to the cardiology department.
- **Dataverse**: The central database where patient information, medical records, lab results, and scheduling data are stored and managed.

### Automation and Integration

- **Power Automate**: Automates various workflows such as sending notifications, scheduling appointments, and updating patient records, ensuring smooth operations.
- **MS Graph API**: Facilitates integration with **Microsoft 365** services, such as **Outlook** for email notifications and **Microsoft Bookings** for scheduling management.
- **Microsoft Bookings**: Manages appointment scheduling for doctors and patients, simplifying the appointment booking process.
- **Outlook**: Used for email communications and notifications.

### Security and Infrastructure

- **Azure**: The cloud platform hosting all the solution components, providing scalability, reliability, and security.
- **Private Endpoints**: Secure all Azure resources by ensuring traffic remains within the Microsoft backbone network.
- **Key Vault**: Stores access keys, secrets, and other sensitive information securely, ensuring the confidentiality and integrity of critical data.
- **O365 Cloud**: Provides access to Microsoft 365 services such as **Outlook** and **Active Directory**.
- **Active Directory**: Handles user authentication and authorization, ensuring secure access to the system.

## Security

All sensitive components and data within the CardioTriage AI ecosystem are safeguarded through strict security measures, including:

- **Key Vault** for managing and storing access keys.
- **Private Endpoints** ensuring secure communication within the Microsoft backbone network.
- **Azure Active Directory** for secure user authentication and authorization.

## Technologies Used

- **Power Apps**
- **AI Builder**
- **Copilot Custom Agent**
- **Dataverse**
- **Power Automate**
- **Microsoft Bookings**
- **MS Graph API**
- **Azure**
- **Active Directory**
- **Outlook**
- **Key Vault**
- **O365 Cloud**

---

By leveraging the power of Microsoft technologies, CardioTriage AI ensures a secure, efficient, and intelligent solution for managing patient triage in cardiology. The system not only enhances the efficiency of medical professionals but also prioritizes security and data integrity at every step.
