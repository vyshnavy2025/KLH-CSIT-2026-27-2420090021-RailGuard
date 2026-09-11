# 🚆 RailGuard – Smart Emergency Response Platform

## 📌 Project Title

**ADAPTIVE RAILWAY EMERGENCY MANAGEMENT SYSTEM**

---

## 👥 Team Members

| **S. No.** | **Team Member Name**      |  **ID Number** |
| ---------: | ------------------------- | -------------: |
|      **1** | **JOSRITHA DUGGIREDDY**   | **2420030493** |
|      **2** | **PRATHIGADAPA VYSHNAVY** | **2420090021** |
|      **3** | **JASRITHA VEMULAPALLI**  | **2420090136** |

### 👩‍🏫 Supervisor

**G. LAVANYA**

---

## 📖 Abstract

The **Adaptive Railway Emergency Management System** is designed to improve the **speed and effectiveness of railway emergency response**. The system allows passengers and railway staff to report emergencies such as **fire, medical issues, accidents, overcrowding, and suspicious activities** through a web or mobile application.

Based on the **emergency type, severity, and location**, the system assigns an appropriate priority level and sends targeted notifications to **railway authorities, emergency response teams, and affected passengers**. A **centralized dashboard** enables authorities to monitor, assign, and track emergencies in real time.

The system aims to **reduce emergency response time, improve communication, enable effective emergency coordination, and enhance overall passenger safety** through an adaptive emergency management approach.

---

## 🎯 Objectives

* 🚨 Provide a **quick emergency reporting system**.
* 📊 Classify emergencies based on **type and severity**.
* ⚡ Assign appropriate **priority levels**.
* 🔔 Notify railway authorities and emergency teams.
* 👥 Assign suitable emergency response teams.
* 📍 Track emergency location and status.
* 🖥️ Provide a **centralized real-time dashboard**.
* 🗄️ Maintain emergency records in a centralized database.
* ⏱️ **Reduce emergency response time**.
* 🛡️ Improve overall railway passenger safety.

---

## 🛠️ Modern Tools and Technologies

| **Technology**            | **Purpose**                             |
| ------------------------- | --------------------------------------- |
| **React.js**              | Frontend and interactive user interface |
| **Node.js**               | Backend server-side processing          |
| **Express.js**            | REST API development                    |
| **MySQL**                 | Database management                     |
| **Docker**                | Application containerization            |
| **AWS / Microsoft Azure** | Cloud deployment and hosting            |
| **Git**                   | Version control                         |
| **Postman**               | REST API testing                        |
| **Visual Studio Code**    | Development environment                 |

---

## 🏗️ System Architecture

```text
                 👤 PASSENGER / STAFF
                         │
                         ▼
                  ┌──────────────┐
                  │   React.js   │
                  │  Frontend UI │
                  └──────┬───────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Node.js + Express.js│
              │    Backend / API    │
              └──────────┬──────────┘
                         │
                         ▼
                  ┌──────────────┐
                  │    MySQL     │
                  │   Database   │
                  └──────┬───────┘
                         │
                         ▼
              ┌────────────────────────┐
              │   Docker / AWS / Azure │
              │    Cloud Deployment    │
              └────────────────────────┘
```

---

## 📂 Project Structure

```text
ADAPTIVE-RAILWAY-EMERGENCY-MANAGEMENT-SYSTEM/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── server.js
│   ├── package.json
│   └── ...
│
├── database/
│   └── railway_emergency.sql
│
├── docker/
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── README.md
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 1. Install Required Software

Install the following:

* **Node.js and npm**
* **MySQL**
* **Visual Studio Code**
* **Git**
* **Docker Desktop**
* **Postman**

### 2. Clone the Repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
cd ADAPTIVE-RAILWAY-EMERGENCY-MANAGEMENT-SYSTEM
```

### 3. Setup MySQL Database

Start MySQL and create the database:

```sql
CREATE DATABASE railway_emergency;
```

The database can contain:

```text
users
emergency_reports
emergency_types
railway_staff
response_teams
locations
incident_status
notifications
```

---

## 🖥️ Backend Setup

```bash
cd backend
npm install
node server.js
```

The backend uses **Node.js + Express.js + MySQL**.

---

## 💻 Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the localhost URL displayed in the terminal.

Example:

```text
http://localhost:5173
```

---

## ▶️ Execution Instructions

```text
Start MySQL
     ↓
Start Backend
     ↓
Start Frontend
     ↓
Open Web Application
     ↓
Login / Register
     ↓
Report Emergency
     ↓
Select Emergency Type
     ↓
Enter Location & Details
     ↓
System Assigns Priority
     ↓
Admin Receives Report
     ↓
Response Team Assigned
     ↓
Emergency Status Updated
     ↓
Emergency Resolved
```

---

## 🚨 Emergency Management Flow

```text
Emergency Report
       ↓
Emergency Classification
       ↓
Severity & Location Analysis
       ↓
Priority Assignment
       ↓
Authority Notification
       ↓
Response Team Assignment
       ↓
Real-Time Monitoring
       ↓
Status Update
       ↓
Emergency Resolution
```

---

## 🗃️ Database

| **Table**             | **Purpose**                                |
| --------------------- | ------------------------------------------ |
| **Users**             | Stores passenger and staff information     |
| **Emergency_Reports** | Stores reported emergencies                |
| **Emergency_Types**   | Stores emergency categories                |
| **Railway_Staff**     | Stores railway staff details               |
| **Response_Teams**    | Stores emergency response team information |
| **Locations**         | Stores railway location information        |
| **Incident_Status**   | Tracks emergency progress                  |
| **Notifications**     | Stores notification information            |

---

## 🐳 Docker Execution

To build and run the application using Docker:

```bash
docker compose up --build
```

To stop the containers:

```bash
docker compose down
```

Docker can run:

```text
Docker
 ├── React Frontend
 ├── Node.js + Express Backend
 └── MySQL Database
```

---

## ☁️ Cloud Deployment

The application can be deployed using:

* **AWS**
* **Microsoft Azure**

Cloud deployment provides:

* Scalability
* Remote accessibility
* Reliable hosting
* Easy deployment
* Centralized management

---

## 🧪 API Testing

**Postman** can be used to test REST APIs.

Example API operations:

```text
POST   /api/emergencies
GET    /api/emergencies
GET    /api/emergencies/:id
PUT    /api/emergencies/:id
DELETE /api/emergencies/:id
```

---

## 📊 Current Phase Status

### **Phase 1 – Planning and Initial Development**

**Overall Status: 🔄 In Progress**

| **S. No.** | **Task**                  | **Status**         |
| :--------: | ------------------------- | ------------------ |
|    **1**   | Project Topic Selection   | ✅ **Completed**    |
|    **2**   | Problem Identification    | ✅ **Completed**    |
|    **3**   | Abstract Preparation      | ✅ **Completed**    |
|    **4**   | System Objectives         | ✅ **Completed**    |
|    **5**   | Module Identification     | ✅ **Completed**    |
|    **6**   | UI Design                 | 🔄 **In Progress** |
|    **7**   | Frontend Development      | 🔄 **In Progress** |
|    **8**   | Backend Development       | ⏳ **Pending**      |
|    **9**   | Database Integration      | ⏳ **Pending**      |
|   **10**   | Emergency Priority System | ⏳ **Pending**      |
|   **11**   | Notification System       | ⏳ **Pending**      |
|   **12**   | Admin Dashboard           | ⏳ **Pending**      |
|   **13**   | Testing                   | ⏳ **Pending**      |
|   **14**   | Final Deployment          | ⏳ **Pending**      |

---

## 🔮 Future Enhancements

* 📍 GPS-based emergency location tracking
* 🤖 AI-based emergency classification
* 📱 Mobile application
* 🔔 SMS and push notifications
* 🗺️ Live railway map integration
* 📊 Advanced analytics dashboard
* 🎥 CCTV integration
* 🧠 Predictive emergency analysis
* ☁️ Advanced cloud scalability
* 🔐 Improved authentication and security

---

## 🎯 Expected Outcome

The expected outcome is a **centralized, adaptive, and scalable railway emergency management platform** that enables:

**Fast Reporting → Smart Prioritization → Quick Notification → Team Assignment → Real-Time Monitoring → Emergency Resolution**

---

## 📌 Project Summary

| **Category**         | **Details**                                  |
| -------------------- | -------------------------------------------- |
| **Project Name**     | Adaptive Railway Emergency Management System |
| **Domain**           | Railway Safety & Emergency Management        |
| **Frontend**         | React.js                                     |
| **Backend**          | Node.js + Express.js                         |
| **Database**         | MySQL                                        |
| **Containerization** | Docker                                       |
| **Cloud**            | AWS / Microsoft Azure                        |
| **API Testing**      | Postman                                      |
| **Version Control**  | Git                                          |
| **Development Tool** | Visual Studio Code                           |
| **Current Phase**    | Phase 1 – Planning & Initial Development     |
| **Status**           | 🔄 **In Progress**                           |

---

## 👩‍💻 Team

**JOSRITHA DUGGIREDDY** — 2420030493
**PRATHIGADAPA VYSHNAVY** — 2420090021
**JASRITHA VEMULAPALLI** — 2420090136

### 👩‍🏫 Supervisor

**G. LAVANYA**

---

## ⭐ Project Goal

> **To develop a flexible and adaptive railway emergency management system that provides rapid emergency reporting, intelligent prioritization, real-time monitoring, and effective coordination between passengers, railway authorities, and emergency response teams.**
