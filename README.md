# Healthcare-Appointment-Chatbot-Dialogflow-CX
AI-powered patient scheduling chatbot built using Dialogflow CX and Google Cloud Platform.
# 🏥 AI Healthcare Appointment Scheduling Agent  
Built using Google Cloud Dialogflow CX

## 📌 Project Overview
This project is a conversational AI system designed to automate patient appointment scheduling, rescheduling, and cancellation for small healthcare clinics.

The system leverages:
- Dialogflow CX (Conversational Agents)
- Custom Entity Modeling
- Modular Flow Architecture
- Parameterized Confirmation Logic
- Structured Data Model

## 🎯 Business Problem
Small clinics face:
- Long patient wait times
- Manual scheduling inefficiencies
- Administrative overload
- Missed appointment revenue loss

This AI agent provides 24/7 automated scheduling support.

---

## 🔁 Core Dialogue Flows

### 1️⃣ Schedule Appointment Flow
- Collect patient information
- Collect appointment preferences
- Confirm summary
- Generate confirmation number

### 2️⃣ Reschedule Appointment Flow
- Verify confirmation number
- Redirect to scheduling flow
- Update appointment

### 3️⃣ Cancel Appointment Flow
- Verify confirmation number
- Confirm cancellation
- End session

---

## 🧠 NLP & Design Features

- Custom Entity Types:
  - Patient Information
  - Provider Information
  - Appointment Type
  - Appointment Reason
  - Clinic Location
  - Insurance Provider
  - Cancellation Reason
  - Reschedule Reason

- Structured state machine logic
- Conditional routing
- Confirmation intent handling
- Modular flow-based architecture

---

## 📊 Technical Architecture

- Default Start Flow
- Schedule_Appointment_Flow
- Reschedule_Appointment_Flow
- Cancel_Appointment_Flow

Designed with:
- Pages
- Routes
- Parameters
- Intent matching
- Custom payloads (rich UI buttons)

---

## 🚀 Skills Demonstrated

- Conversational AI Design
- Dialogflow CX
- NLP Intent Modeling
- Entity Extraction
- State Machine Architecture
- UX-focused bot design
- Cloud-based AI deployment

---

## 👩‍💻 Authors
Sarika Gaind  
Bhawana Rohile  
Aamir Omar

---

## 📌 Future Improvements
- Backend database integration
- HIPAA-compliant API integration
- Real-time provider calendar sync
- SMS reminder automation
