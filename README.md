# Azure-AI-Career-Mentor-Agent
An AI-powered career coaching agent built using Microsoft Azure AI Foundry. The solution leverages Azure AI Agents, Retrieval-Augmented Generation (RAG), File Search, and Web Search to provide personalized career guidance, certification recommendations, interview preparation, and learning roadmaps.

# Project Overview
Many learners and professionals struggle with questions such as:

  Which Microsoft certification should I pursue next?
  What skills are required for Azure AI Engineer roles?
  How can I transition into AI-related careers?
  What roadmap should I follow to prepare for sample resume?
  How should I prepare for Azure AI interviews?
  
The Azure AI Career Mentor Agent addresses these challenges by providing personalized recommendations based on a custom knowledge base and real-time web information.

# Business Objective
Build an AI agent that can:

  Analyze user skills
  Recommend Microsoft certifications
  Identify skill gaps
  Generate learning roadmaps
  Create interview preparation plans
  Use private knowledge files and web search together

# Solution Architecture
                    User
                      │
                      ▼
        Azure AI Career Mentor Agent
                      │
          ┌───────────┴───────────┐
          │                       │
          ▼                       ▼

     File Search             Web Search
   (Knowledge Base)      (Current Information)

          │                       │
          └───────────┬───────────┘
                      ▼

                 Foundation Model
                    GPT Model

                      ▼
              Personalized Response  

# Technologies Used

Technology	Purpose

  Azure AI Foundry	Agent Development Platform
  Azure AI Agents	Conversational Agent
  GPT Foundation Model	Natural Language Reasoning
  File Search	Retrieval-Augmented Generation (RAG)
  Knowledge Base	Agent Grounding
  Web Search	Current Information Retrieval
  Application Insights	Agent Monitoring
  Prompt Engineering	Agent Behavior Design

# Features
Career Guidance
Provides tailored career advice for:

Azure AI Engineer
Data Scientist
Cloud Engineer
AI Consultant
AI Solutions Architect

# Certification Recommendations
Suggests suitable certifications:

AI-900
AI-102
AZ-900
AZ-204
DP-100

# Skill Gap Analysis
Evaluates:

Existing Skills
Missing Competencies
Learning Priorities
Career Readiness

# Learning Roadmap Generation
Creates:

3-Month Plans
6-Month Plans
12-Month Plans
based on the user's goals.

# Interview Preparation
Generates:

Technical Questions
Scenario-Based Questions
Certification-Oriented Questions
for Azure AI careers.

# Knowledge Base
The agent uses the following uploaded documents:

AI102_Skills_Outline.pdf
Azure_AI_Roadmap.pdf
Certification_Guide.pdf
Azure_AI_Interview_Questions.pdf
sample_resume.pdf

These documents are indexed and accessed using File Search to provide grounded responses.
# AI Concepts Demonstrated
This project demonstrates:

Agent Creation
Prompt Engineering
Retrieval-Augmented Generation (RAG)
Knowledge Grounding
File Search
Web Search
Tool Usage
AI Solution Design
Azure AI Foundry
Generative AI Applications

# Sample Prompts

Certification Recommendation
Which certification should I take after AI-900?

Skill Assessment
I know Python, SQL, and Power BI.
I want to become an Azure AI Engineer.
Analyze my skills and recommend next steps.
Roadmap Creation
Create a 6-month roadmap for becoming an Azure AI Engineer.
Interview Preparation
Generate Azure AI Engineer interview questions.
Resume Review
Review my resume and suggest improvements.

# Project Screenshots
Attached

# Learning Outcomes
Through this project, I gained practical experience with:

Azure AI Foundry
AI Agent Development
Knowledge Grounding
File Search Configuration
Web Search Integration
Prompt Engineering
AI Solution Architecture
Agent Testing and Evaluation

# Future Enhancements
Planned improvements:

Resume Upload Support
Azure AI Search Integration
Function Calling
Multi-Agent Architecture
Semantic Kernel Integration
Job Recommendation Engine
LinkedIn Profile Analysis
Evaluation Dashboards

# Author
Anuja Suresh

Azure AI Enthusiast | AI Agent Builder | Azure AI Foundry Learner

Currently preparing for the Microsoft Certified: Azure AI Apps and Agents Developer Associate certification while building practical AI applications using Microsoft Azure AI Foundry.

# Project Status

Project Designed
Azure AI Foundry Project Created
Agent Created
Knowledge Base Uploaded
File Search Configured
Web Search Enabled
Prompt Engineering Implemented
Agent Tested

# Key Takeaway
This project demonstrates how Azure AI Foundry can be used to build a production-style AI agent that combines private knowledge, retrieval capabilities, and real-time information to deliver intelligent career guidance.


