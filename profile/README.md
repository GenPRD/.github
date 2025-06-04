![genprd_logo](https://github.com/user-attachments/assets/01a5b4a1-932b-423f-959c-ac01d2d9ed3d)

# **GenPRD: PRD Maker with LLM**  

## **Overview**
**GenPRD** is a web-based application designed to simplify and accelerate the creation of Product Requirements Documents (PRD). By leveraging a user-friendly input form and a powerful Large Language Model (LLM), the application generates optimized PRDs tailored to project needs. Users can edit the generated PRD for accuracy and download the finalized document as a professionally styled PDF.

- **User-Friendly Interface**: Input project details like version, product name, and timeline easily.  
- **AI-Driven PRD Generation**: Generate structured PRDs using LLM-powered optimization (OpenAI API).  
- **Editable Outputs**: Ensure completeness and correctness with a editing functionality after PRD is generated.  
- **Downloadable PDF**: Save finalized PRDs as styled PDF documents.  

## **Team Members**
We are a team of Bangkit 2024 Cohorts from different learning paths and universities:

| **Name**                | **Role**   | **University**           |
|:-----------------------:|:-------------------:|:------------------------:|
| Fizio Ramadhan Herman   | Machine Learning    | Universitas Telkom       |
| Muhammad Daffa Arigoh   | Machine Learning    | Universitas Sriwijaya    |
| Rafi Muhamad Nabil      | Frontend Developer     | Universitas Pakuan       |
| Mustafa Fathur Rahman   | Software Engineer  | Universitas Andalas      |

## **Tech Stack**

| **Technology**        | **Purpose**                                  |
|-----------------------|---------------------------------------------|
| ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) | Frontend Framework  |
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) | API and Routing |
| ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) | Backend Framework |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | Programming Language for Backend (Flask) |
| ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) | Backend for LLM API |
| ![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) | For Modern Styling  |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | For Containerizing the Backend Application |
| ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) | Cloud Technology for Deployment       |

## GCP Architecture: Bangkit 2024 Capstone Project Company Case Algo Network - PRD Maker with LLM
![GenPRD GCP Architecture](https://github.com/user-attachments/assets/3e2252a8-e0d2-41c8-97c9-42bdc35770b4)

### 1. User Interaction with the Frontend

The user interacts with the application through the React Frontend. This frontend component serves as the main interface for the user to interact with the application's functionality.

### 2. User Authentication with OAuth 2.0

The user can perform authentication using the OAuth 2.0 protocol. This allows the user to securely authenticate and authorize the application to access their data and perform actions on their behalf.

### 3. Frontend React Interaction with Express Backend

The Frontend React component interacts with the Express Backend for data and functional operations. The React frontend sends requests to the Express backend, which then handles the necessary data processing and functionality.

### 4. Backend Express Interaction with Google Cloud Storage

The Express Backend stores the PRD (Product Requirements Document) PDF document to the Google Cloud Storage. This allows the application to securely store and manage the generated PRD files.

### 5. Backend Express Interaction with Cloud SQL

The Express Backend interacts with the Cloud SQL database for data storage and operations. The backend uses the Cloud SQL service to store and retrieve data as needed for the application's functionality.

### 6. Backend Express Interaction with Backend Flask

The Express Backend interacts with the Backend Flask specifically for the PRD Generation API. The Backend Flask component is responsible for generating the PRD document using a Large Language Model (LLM) API, which in this case, is the OpenAI model.

## **Project Workflow**

### **Frontend**:
1. Users fill in the PRD form via a React-based UI.

### **Backend**:
1. **Express** stored the User PRD data input and send it to the Flask API.
1. **Flask** processes the PRD data input via an LLM API (OpenAI).
2. LLM generates optimized PRD content.
3. Generated output sended back to Express and stored in the database.

### **Output**:
1. The generated PRD is displayed in real-time on the frontend (editable).
2. Finalized PRDs are downloadable as PDFs with professional styling.
