# CyberGuard: AI-Powered Cybersecurity Chatbot

## Submission Details
**Title:** CyberGuard: Combining Diffusion Models and Language Understanding Models in a Cybersecurity Chatbot with Advanced Retrieval-Augmented Generation (RAG) Using a Microservices Architecture in a DevOps/MLOps Context  
**Submission Date:** 2024-01-14  
**Professor:** EL AACHAK Lotfi  
**Master:** Cybersecurity and Big Data (Second Year)  
**Module:** Deep Learning  
**Team Members:**  
- AKZOUN Hafsa  
- BOULBEN Firdaous  
- EL HAYANI Adnan  
- EL YAHYAOUY Imane  
- TOUYEB Zakaria  

## Table of Contents
1. Introduction  
2. Retrieval-Augmented Generation (RAG) Model  
3. Diffusion Model for Threat Forecasting  
4. System Implementation  
5. Testing and Evaluation  
6. Conclusion  

---

## Chapter 1: Introduction
Cybersecurity threats are becoming increasingly complex, requiring innovative solutions for timely detection and response. The need for intelligent, scalable, and adaptive systems has led to the development of **CyberGuard**, a chatbot designed to handle cybersecurity-related inquiries. This project integrates advanced Language Understanding Models (LUM), Diffusion Models for threat forecasting, and Retrieval-Augmented Generation (RAG) to provide comprehensive, real-time insights. Built on a microservices architecture, CyberGuard ensures scalability and maintainability, supported by DevOps/MLOps practices for efficient deployment and operation.

### Objectives
- **Develop a Cybersecurity-Focused Chatbot:** Intelligent response system for cybersecurity inquiries.
- **Integrate Diffusion Models for Threat Forecasting:** Predict the spread of threats in network environments.
- **Leverage Language Understanding Models (LUM):** Use models like GPT-4 and BERT for accurate user input comprehension.
- **Implement Advanced RAG:** Enhance chatbot responses with real-time data retrieval.
- **Adopt Microservices Architecture:** Modular system design for scalability.
- **Apply DevOps/MLOps Practices:** CI/CD, model management, and infrastructure automation.

---

## Chapter 2: Retrieval-Augmented Generation (RAG) Model
### Overview
The CyberGuard Retrieval-Augmented Generation (RAG) microservice is designed to intelligently handle cybersecurity-related queries. It integrates Google’s Generative AI for advanced language understanding and utilizes document retrieval to provide accurate, context-rich responses. This service is built using Flask and MongoDB and is part of the larger CyberGuard microservices ecosystem.

### Key Features
- **Retrieval-Augmented Generation (RAG):** Combines AI-generated responses with document retrieval for accurate answers.
- **Google Generative AI Integration:** Uses Google Gemini Pro for natural language understanding and response generation.
- **PDF Knowledge Base:** Automatically loads and processes cybersecurity-related PDFs for context-aware responses.
- **Vector Database (Chroma):** Embeds and stores document vectors for efficient information retrieval.
- **MongoDB Integration::** Tracks user conversations and interactions for session continuity.
- **REST API with CORS:** Allows smooth interaction with the Angular frontend through secure API calls.
  
### Technology Stack
- Dynamic data retrieval for accurate response generation
- Backend: Python, Flask
- AI Models: Google Generative AI (Gemini Pro)
- Vector Database: Chroma for document indexing and retrieval
- Database: MongoDB for storing conversations

---

## Chapter 3: Diffusion Model for Threat Forecasting
### Overview
The Diffusion Model simulates and predicts how cybersecurity threats propagate through network systems. This predictive capability helps security analysts anticipate and mitigate risks.

### Implementation
- **Technology:** Python-based simulation
- **Framework:** Flask microservice
- **Functionality:** Real-time threat forecasting and analysis

### Features
- Visualization of threat spread
- Early detection and proactive defense mechanisms

---

## Chapter 4: System Implementation
### Backend Development
- **Spring Boot:** Manages user authentication and registration using Spring Security with JWT.
- **Flask:** Hosts Python-based services for RAG and diffusion models.

### Frontend Development
- **Angular:** Provides an interactive user interface for seamless interaction with the chatbot.

### DevOps/MLOps Integration
- **CI/CD Pipelines:** Automated testing, deployment, and monitoring with GitHub Actions.
- **Containerization:** Docker for service isolation and Kubernetes for orchestration.

### Repository Links
- **Frontend:** [CyberGuard Frontend](https://github.com/firdaous-boulben/CyberGuard.git)  
- **Backend (Spring Boot):** [ChatBoot Security](https://github.com/hafsakzoun/ChatBoot-security.git)  
- **RAG Model:** [Chatbot RAG](https://github.com/adnanelhayani/chatbot_rag.git)  
- **Diffusion Model:** *(Link to be added)*  

### Setup Instructions
1. **Clone the Repositories:**
   ```bash
   git clone <frontend-repo>
   git clone <backend-repo>
   git clone <rag-repo>
   ```
2. **Build Docker Containers:**  
   ```bash
   docker-compose up --build
   ```
3. **Deploy Kubernetes Cluster:**  
   ```bash
   kubectl apply -f k8s/
   ```
4. **Access the UI:**  
   Open `http://localhost:4200` in your browser.

---

## Chapter 5: Testing and Evaluation
- **Functional Testing:** Ensures individual microservices operate correctly.
- **Integration Testing:** Validates service interactions.
- **Performance Testing:** Measures response times and scalability.
- **Threat Prediction Accuracy:** Evaluates the effectiveness of the diffusion model.

---

## Chapter 6: Conclusion
CyberGuard successfully combines language understanding models, diffusion models, and advanced RAG techniques to create an intelligent, scalable cybersecurity chatbot. By leveraging a microservices architecture and DevOps/MLOps practices, the system achieves high performance, scalability, and maintainability. Future enhancements could involve expanding data sources for RAG, refining diffusion model algorithms, and introducing real-time incident response capabilities.

## Contribution
Contributions are welcome through issues and pull requests.

## License
[MIT License](LICENSE)  

## Contact
For any inquiries, contact the project team at [your.email@example.com].
