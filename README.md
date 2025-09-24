# BwellAi - AI-Powered Health Monitoring Platform

## Overview
BwellAi is a health and wellness platform designed to **track physical, sleep, and body health metrics**. It integrates **IoT devices, wearable health trackers**, and AI-powered analysis to provide personalized health insights.

## Features
- Track physical health (heart rate, steps, BMI, water/muscle/bone composition).
- Monitor sleep patterns including deep sleep, light sleep, and sleep efficiency.
- AI-generated insights and personalized recommendations.
- Secure user authentication using JWT tokens.
- Integration with third-party health devices and APIs.
- REST API endpoints for retrieving and storing health data.
- Real-time alerts for health anomalies.

## Tech Stack
- **Backend:** Java, Spring Boot, Spring Security, Spring Data JPA
- **Database:** MySQL, MongoDB
- **Microservices:** HealthData, SleepData, User Service
- **AI/ML:** Vertex AI for health data analysis
- **Tools:** Swagger, Jenkins (CI/CD), Docker, Kubernetes
- **Deployment:** AWS Ubuntu Server, Dockerized microservices

## Project Highlights
- Uses **Vertex AI** for generating health insights and content based on sleep, physical, and body data.  
- Implements **token-based user authentication** across multiple microservices.  
- Health data is standardized using **JSON objects and mapping** for uniform storage and processing.  
- **CI/CD pipeline** for automated deployment and scaling on AWS with Docker and Kubernetes.  

## Future Enhancements
- Mobile app integration for real-time notifications.
- Integration with additional wearable devices.
- AI-based predictive health alerts.

## Live Demo
Click here to visit the website.(https://app.bwellai.com)
