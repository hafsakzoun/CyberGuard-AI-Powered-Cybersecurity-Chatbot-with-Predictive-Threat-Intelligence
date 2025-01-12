# CyberGuard: AI-Powered Cybersecurity Chatbot

## Submission Details
**Title:** CyberGuard: Combining Diffusion Models and Language Understanding Models in a Cybersecurity Chatbot with Advanced Retrieval-Augmented Generation (RAG) Using a Microservices Architecture in a DevOps/MLOps Context  
**Submission Date:** 2024-01-14  
**Professor:** EL AACHAK Lotfi   
**Master:** Cybersecurity and Big Data (Second Year) 
**Program:** Deep Learning
**Team Members:**  
- AKZOUN Hafsa  
- BOULBEN Firdaous  
- EL HAYANI Adnan  
- EL YAHYAOUY Imane  
- TOUYEB Zakaria   

## Short Description
**CyberGuard** is an advanced cybersecurity chatbot combining Language Understanding Models (LUM), Diffusion Models for threat forecasting, and Retrieval-Augmented Generation (RAG) to deliver intelligent, real-time security insights. Built on a scalable microservices architecture with DevOps/MLOps integration.

## Project Overview
CyberGuard is an intelligent cybersecurity chatbot designed to handle complex security queries, provide incident responses, and assist in threat analysis. The system integrates advanced Language Understanding Models (LUM) for contextual comprehension, Diffusion Models for threat forecasting, and Retrieval-Augmented Generation (RAG) for enriched responses. Built on a scalable microservices architecture, the project ensures high availability and maintainability, leveraging DevOps/MLOps practices for efficient deployment and operation.

## Objectives
The project aims to develop a cybersecurity-focused chatbot designed to intelligently respond to cybersecurity inquiries. It will integrate diffusion models for threat forecasting to predict the spread of threats within network environments. The chatbot will leverage advanced language understanding models (LUM) like GPT-4 and BERT for accurate user input comprehension. To enhance its responses, the chatbot will implement advanced retrieval-augmented generation (RAG) for real-time data retrieval. The system will adopt a microservices architecture for scalability and maintainability, and DevOps/MLOps practices will be applied, including continuous integration and deployment (CI/CD), model management, and infrastructure automation.

## System Architecture

### Technology Stack
   **Spring Boot**: Used for authentication and registration, and integration with databases.
   **Flask**: Implements lightweight microservices for Python-based services, specifically for the RAG model.
   **Angular**: Frontend service for the application.
   **Python**: Utilized for Python-based services, including the RAG model and diffusion prediction.

### DevOps/MLOps Integration
- **CI/CD Pipelines**: Automated testing, deployment, and monitoring.
- - **DevOps/MLOps**: GitHub Actions, MLflow
- **Containerization**: Docker for services.

## Setup Instructions
1. **Clone the Repository:**  
   **Frontend**: https://github.com/firdaous-boulben/CyberGuard.git
   **Backend**: https://github.com/hafsakzoun/ChatBoot-security.git
   **Rag Model**: https://github.com/adnanelhayani/chatbot_rag.git
   **Diffusion Model**: 

3. **Build Docker Containers:**  
   `docker-compose up --build`

4. **Deploy Kubernetes Cluster:**  
   `kubectl apply -f k8s/`

5. **Access the UI:**  
   Open `http://localhost:4200` in your browser.

## Report Plan

### **Chapter 1: Introduction**
- Project background
- Problem statement
- Objectives

### **Chapter 2: Literature Review**
- Cybersecurity chatbots
- Language Understanding Models
- Diffusion Models in threat prediction
- Retrieval-Augmented Generation (RAG)

### **Chapter 4: Implementation**
- Development of chatbot services
- Integration of diffusion models
- RAG pipeline implementation
- DevOps/MLOps setup (CI/CD, containerization)

### **Chapter 5: Testing and Evaluation**
- Functional testing of services
- Threat prediction accuracy

### **Chapter 7: Conclusion**
- Summary of findings
- Limitations
- Future improvements

## Contribution
Feel free to contribute by submitting issues or pull requests.

