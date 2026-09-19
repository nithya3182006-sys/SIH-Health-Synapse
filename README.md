# SIH Health Synapse 🚑

**Smart India Hackathon 2026 Project – Hexora Team**

## 📌 Overview
Health Synapse is an intelligent healthcare resource connectivity platform that provides:
- Quick hospital & doctor discovery
- Emergency ambulance support
- Real-time blood & bed availability
- Appointment booking
- AI chatbot assistance

## 🏆 Goal
Reduce healthcare access time and improve patient support by bringing essential medical services together in one user-friendly platform.

## 📂 Repository Structure
SIH-Health-Synapse/
│── README.md                → Project overview
│── SIH HEALTH SYNAPSE.pdf   → Hackathon project document
│── src/
    └── HealthSynapseDemo.java → Sample Java demo code
## Backend

Health Synapse is designed with a Java-based backend architecture using Spring Boot and RESTful APIs.

### Backend Technologies

- Java
- Spring Boot
- RESTful APIs
- MySQL
- Spring Data JPA / Hibernate
- Spring Security
- AI API Integration
- Google Maps API

### Backend Modules

- Hospital Management
- Doctor Management
- Appointment Management
- Blood Availability
- Bed Availability
- Ambulance and Emergency Management
- AI Chatbot
- User Authentication

### Backend Responsibilities

The backend acts as the communication layer between the frontend and healthcare services. It is responsible for:

- Processing user requests
- Managing hospital and doctor information
- Handling appointment bookings
- Managing blood and bed availability
- Processing ambulance requests
- Authenticating users
- Connecting with AI services
- Storing and retrieving healthcare data
- Providing REST APIs to the frontend

### System Architecture

```text
User
  |
  v
Frontend
HTML + CSS + JavaScript
  |
  | REST API / JSON
  v
Java Spring Boot Backend
  |
  +-- Hospital Service
  +-- Doctor Service
  +-- Appointment Service
  +-- Blood Service
  +-- Bed Service
  +-- Ambulance Service
  +-- AI Chatbot Service
  |
  v
MySQL Database

