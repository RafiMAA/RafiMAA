<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,25:0EA5E9,50:22D3EE,75:14B8A6,100:22C55E&height=210&section=header&text=ABDUL%20RAFI&fontSize=52&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Computer%20Science%20and%20Engineering%20%7C%20Artificial%20Intelligence&descSize=16&descAlignY=57" width="100%" />


<br/>

<a href="https://github.com/RafiMAA?tab=repositories"><img src="https://img.shields.io/badge/Explore_My_Projects-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/abdul-rafima"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:abdulr.23@cse.mrt.ac.lk"><img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=RafiMAA&label=PROFILE+VIEWS&color=7c3aed&style=for-the-badge"/>
<img src="https://img.shields.io/github/followers/RafiMAA?label=FOLLOWERS&style=for-the-badge&color=00b8d9"/>

</div>

---

# 👨‍💻 About Me

I'm a **Computer Science & Engineering undergraduate at the University of Moratuwa, Sri Lanka**. I build **full-stack applications and AI-powered systems**, including a production attendance platform for a school of ~700 students (React, FastAPI, Supabase) and an LLM-based RAG system.

I also work on **distributed systems** (Kafka, MQTT, Kubernetes).

<div align="center">

<img src="https://img.shields.io/badge/Full--Stack-React_%7C_FastAPI-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/LLM_%26_RAG-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Robotics-00AEEF?style=for-the-badge"/>

</div>

> ### 🎯 Current Focus
> **Full-Stack Development + AI / LLM Applications + Distributed Systems**

---

# 🚀 Featured Projects

### 🎓 School Management System
**Real Client Project • React • FastAPI • Supabase • PostgreSQL • Mobile + Push Notifications**

A production attendance and student management platform built for **Al Meera Ahadiya School, Matara**, a school of around 700 students. Teachers mark weekly attendance, administrators manage students, classes and yearly promotions, and everyone gets automated reminders.

**Highlights**
- Full-stack system used by real staff at a real school: React + TypeScript web app, React Native mobile app, FastAPI REST backend and Supabase (PostgreSQL) database
- Role-based access for teachers, admins, principals and super admins, with a full audit log
- Scheduled push notifications (Web Push, FCM, APNs) driven by GitHub Actions
- Excel import wizard with row-level validation, plus automated PDF (ReportLab) and Excel (OpenPyXL) reports
- End-to-end ownership: requirements, UI, API design, database schema, deployment and client support

<a href="https://github.com/RafiMAA/School_Student_Management_System.git"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

`React` `TypeScript` `React Native` `FastAPI` `Supabase` `PostgreSQL` `Python` `Web Push` `GitHub Actions`

---

### 💊 Easy Pharma — Prescription OCR Pipeline
**Healthcare AI • OCR • React PWA • FastAPI • Computer Vision**

A prescription-scanning web application that converts prescription images into structured, reviewable medicine lists. It uses a hybrid OCR pipeline with local processing by default and an optional cloud fallback for low-confidence scans.

**Highlights**
- React + Vite Progressive Web App with camera capture, mobile-responsive design and offline app-shell support
- FastAPI backend with OpenCV preprocessing: orientation correction, resizing, optional deskewing, adaptive thresholding and denoising
- Local Tesseract OCR with optional AWS Textract fallback for low-confidence extraction
- Prescription parser extracts dosage values such as `mg`, `mcg`, `g` and `ml`
- RapidFuzz-based medicine matching corrects likely OCR spelling errors against a medicine dataset
- Evaluation utilities for OCR quality (CER/WER), structured recognition and end-to-end latency

<a href="https://github.com/RafiMAA/Easypharma_OCR_Pipeline"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

`React` `TypeScript` `Vite PWA` `FastAPI` `Python` `OpenCV` `Tesseract OCR` `AWS Textract` `RapidFuzz`

---

# 🤝 Group Projects

### 🚚 Kandypack Distribution System
**Semester 03 Group Project • React • Node.js • Express • MySQL • REST API**

A full-stack logistics and distribution management system developed for a hybrid rail-and-road supply chain, replacing manual Excel-based operations with a centralized web-based platform.

**Highlights**
- Built a React-based dashboard with a Node.js/Express REST API and MySQL relational database
- Designed the database schema with triggers and stored procedures to enforce business rules and maintain data consistency
- Implemented order lead-time validation, train capacity constraints, staff working-hour limits and schedule conflict prevention
- Developed JWT-based role-based access control for Admins, Drivers and Assistants
- Implemented automated order-to-train-trip allocation and reporting for sales, driver working hours and truck utilization

<a href="https://github.com/DinuuCoder/kandypack_project"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

`React` `JavaScript` `Node.js` `Express.js` `MySQL` `REST API` `JWT`

---

### 🚌 OnTime Distributed Transit System
**Semester 04 Group Project • Distributed Systems • Kafka • MQTT • FastAPI • Redis • Kubernetes**

A distributed public-transit platform built using an event-driven architecture. I contributed to the messaging backbone responsible for real-time transport telemetry, inter-service communication and live data delivery across distributed services.

**Highlights**
- Developed the messaging backbone using HiveMQ MQTT, Apache Kafka, WebSockets and Redis for real-time telemetry and inter-service communication
- Configured Apache Kafka in KRaft mode with partitioned and replicated topics for raw telemetry, cleaned telemetry, anomaly alerts, dead-letter messages and trip lifecycle events
- Integrated an MQTT-to-Kafka ingestion pipeline for forwarding incoming transport telemetry into Kafka
- Integrated a FastAPI WebSocket service with Redis pub/sub to support real-time data delivery to downstream services
- Contributed to Docker Compose and Kubernetes-based deployment, service integration, smoke testing and end-to-end messaging verification

<a href="https://github.com/OnTime-SE-G/ontime-g4"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/OnTime-SE-G/ontime-g4/tree/main/epic-01-messaging"><img src="https://img.shields.io/badge/Messaging_Epic-View_Work-0EA5E9?style=for-the-badge&logo=apachekafka&logoColor=white"/></a>

`Apache Kafka` `KRaft` `HiveMQ` `MQTT` `FastAPI` `WebSockets` `Redis` `Docker` `Kubernetes` `Distributed Systems`



# Other Projects

### 🦾 Unitree G1 EDU Robot
**Humanoid Robotics • ROS 2 • Localization • Navigation • LLM + RAG**

Working with the Unitree G1 humanoid robot on robotic localization and navigation, integrating perception, sensing and autonomous behaviours, together with an LLM-powered Retrieval-Augmented Generation (RAG) system.

**Highlights**
- ROS 2 integration
- Humanoid robotics
- Robot localization & autonomous navigation
- Sensor integration
- LLM-based RAG system that grounds model responses in retrieved knowledge
- Real-world robotic experimentation

<a href="https://github.com/RafiMAA/Unitree_G1_EDU_Robot"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/RafiMAA/Unitree_G1_EDU_Robot/blob/main/docs/report/g1_paper.pdf"><img src="https://img.shields.io/badge/Report-Read_PDF-0EA5E9?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>

`Unitree G1` `ROS 2` `Python` `Robotics` `Navigation` `LLM` `RAG`

---

### 🚗 QBot Mapping & Navigation
**ROS 2 • SLAM • LiDAR • Autonomous Navigation**

Autonomous indoor navigation project focused on mapping an environment and navigating a mobile robot toward target locations.

**Highlights**
- ROS 2 navigation stack
- LiDAR-based mapping & SLAM
- Localization
- Goal navigation

<a href="https://github.com/RafiMAA/Qbot_mapping_and_navigating_to_the_goal"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/RafiMAA/Qbot_mapping_and_navigating_to_the_goal/blob/main/docs/report/qbot_paper.pdf"><img src="https://img.shields.io/badge/Report-Read_PDF-22C55E?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>

`ROS 2` `SLAM` `LiDAR` `Nav2` `Python`

---

### 🚁 Autonomous Bathymetric Survey System
**ROS 2 • ArduPilot • Computer Vision • Autonomy**

An autonomous reservoir-survey platform integrating mission planning, robotic navigation, environmental sensing, computer vision and bathymetric mapping.

**Highlights**
- ROS 2 + ArduPilot integration
- Autonomous survey missions & waypoint navigation
- Sonar depth acquisition
- Real-time telemetry & 3D visualization

<a href="https://github.com/RafiMAA/ROS2_Autonomous_Bathymetric_Survey_System_with_Ardupilot"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://github.com/RafiMAA/ROS2_Autonomous_Bathymetric_Survey_System_with_Ardupilot/blob/main/docs/report/bathymetric_survey_paper.pdf"><img src="https://img.shields.io/badge/Report-Read_PDF-14B8A6?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>

`ROS 2` `ArduPilot` `Gazebo` `OpenCV` `React`

---

### 🖥️ Nano Processor
**VHDL • FPGA • Digital Systems**

A hardware-oriented processor implementation built as a digital systems and FPGA engineering project.

**Highlights**
- Digital logic & processor architecture
- VHDL implementation
- FPGA verification
- System-level digital design

<a href="https://github.com/RafiMAA/Nano_Processor"><img src="https://img.shields.io/badge/GitHub-View_Project-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

`VHDL` `FPGA` `Digital Systems` `Processor`

---

# 🎓 Education

<div align="center">

### University of Moratuwa

**B.Sc. Engineering — Computer Science & Engineering**

Sri Lanka

</div>

---

# 🤝 Let's Build Something Interesting

<div align="center">

<a href="mailto:abdulr.23@cse.mrt.ac.lk"><img src="https://img.shields.io/badge/EMAIL_ME-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/abdul-rafima"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/RafiMAA?tab=repositories"><img src="https://img.shields.io/badge/MY_PROJECTS-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22C55E,25:14B8A6,50:22D3EE,75:0EA5E9,100:0F172A&height=140&section=footer" width="100%" />

</div>
