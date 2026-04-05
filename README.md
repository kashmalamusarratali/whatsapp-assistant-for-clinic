# AI WhatsApp Clinic Assistant

An intelligent AI-powered WhatsApp assistant that automates clinic operations, from answering patient queries to booking appointments , just like a real receptionist.

 # Overview

This project is an end-to-end AI automation system built using n8n + Gemini + Google Sheets + WhatsApp API.

It enables clinics to:

Respond to patient queries instantly
Recommend doctors based on symptoms
Answer FAQs using structured data
Book appointments in a guided conversational flow

# Key Features

✅ AI-Powered Conversations

Natural, human-like responses

Context-aware (remembers user inputs)

✅ Smart Doctor Recommendation

Suggests specialists based on symptoms

Falls back to General Physician if needed


✅ Automated Appointment Booking

Collects details step-by-step

Confirms before final booking


✅ FAQ Retrieval (RAG-style)

Answers clinic-related queries using Google Sheets

✅ WhatsApp Integration

Real-time messaging via WhatsApp API

# Tech Stack

Automation: n8n

LLM: Gemini 2.5 Flash

Database: Google Sheets

Messaging: WhatsApp API

How It Works

User sends a message on WhatsApp

n8n workflow is triggered

Message is processed using Gemini (LLM)

# AI:

Understands intent

Fetches relevant data (Doctors / FAQ)

Responds accordingly

If booking is requested:

Collects details step-by-step

Confirms appointment

Stores data in Google Sheets

 # Workflow Architecture

WhatsApp Message → n8n Trigger → Gemini AI Processing
                     ↓
         Google Sheets (Doctors / FAQ / Appointments)
                     ↓
           AI Response → WhatsApp Reply
           
 # Data Sources

1. Doctors Data

Doctor Name

Specialization

Availability

2. FAQ Knowledge Base
   
Common clinic-related questions

Predefined answers

3. Appointments Data
   
Patient Name

Doctor

Date & Time

Contact Info



# Key Capabilities:

Recommends doctors based on symptoms

Answers FAQs using available data

Books appointments step-by-step

Maintains a polite and conversational tone

# Example Behavior:

“Based on your symptoms, I recommend a Cardiologist.”

“Would you like me to book an appointment?”

“May I have your name, please?”

 # Constraints & Safety

❌ No medical advice or diagnosis

✅ Only suggests relevant specialists

✅ Uses only provided data sources

✅ Handles unknown queries gracefully

# Demo




https://github.com/user-attachments/assets/96ccb55e-d28f-409f-827d-977b886182eb





 # Use Cases

Clinics

Hospitals

Diagnostic Labs

Telemedicine Services

 # Business Impact

Reduces manual receptionist workload

Improves response time

Enhances patient experience

Enables 24/7 support

 # Future Improvements

Voice AI integration

CRM integration (HubSpot, GoHighLevel)

Multi-language support

Appointment reminders via WhatsApp

👩‍💻 Author


Kashmala Musarrat Ali

AI Automation | Data Analytics | LLM Applications
