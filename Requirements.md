# Requirements Specification – AI-Powered Career Roadmap Platform

## 1. Overview

This document defines the functional, non-functional, and AI-specific requirements for an AI-powered web application that generates personalized career roadmaps, curates learning resources, guides projects, and connects users to relevant job opportunities. The system is designed in alignment with **AI for Bharat – Hack2Skill** guidelines.

----------

## 2. Problem Statement

Learners face confusion due to:

-   Lack of structured learning paths
    
-   Information overload from unverified resources
    
-   Poor alignment between learning and job requirements
    

The platform must use **meaningful AI reasoning**, not rule-based logic, to solve these issues at scale.

----------

## 3. Target Users

-   Students (college / self-learners)
    
-   Fresh graduates
    
-   Career switchers
    
-   Learners from Tier-2 and Tier-3 cities (Bharat-focused)
    

----------

## 4. Functional Requirements

### FR-1: Career Goal Input

-   Users shall be able to enter career goals in **natural language** (e.g., “I want to become an ML Engineer”).
    

### FR-2: AI-Based Roadmap Generation

-   The system shall generate a **personalized, micro-level learning roadmap**.
    
-   Roadmaps must include logical topic dependencies (beginner → advanced).
    

### FR-3: Resource Recommendation

-   For each topic, the system shall recommend:
    
    -   Free YouTube videos
        
    -   Open PDFs / articles
        
    -   Books
        
    -   Premium courses
        
    -   Research papers
        

### FR-4: Subscription Management

-   The system shall support **Free, Silver, and Gold** tiers.
    
-   Feature access shall vary based on subscription level.
    

### FR-5: Project Guidance (Premium)

-   The system shall suggest **industry-relevant project ideas**.
    
-   Projects shall be mapped to real job skill requirements.
    

### FR-6: Skill-to-Job Matching

-   The system shall recommend suitable job roles based on acquired skills.
    
-   The system shall fetch and display **real-time job listings**.
    

### FR-7: Notifications

-   Users shall receive job alerts via email or in-app notifications.
    

### FR-8: Multilingual Support

-   The system shall support English and Hindi initially.
    
-   Architecture must allow easy addition of regional languages.
    

----------

## 5. AI-Specific Requirements

### AIR-1: Use of LLMs

-   Large Language Models (e.g., Gemini) shall be used for:
    
    -   Career understanding
        
    -   Roadmap reasoning
        
    -   Contextual explanations
        

### AIR-2: Non-Rule-Based Logic

-   Roadmap generation must rely on **AI reasoning**, not static rules or templates.
    

### AIR-3: Recommendation Intelligence

-   Resource recommendations must be context-aware and relevance-ranked using AI.
    

### AIR-4: Responsible AI

-   The system shall not make automated hiring decisions.
    
-   AI outputs must be explainable and user-controllable.
    

----------

## 6. Non-Functional Requirements

-   Scalability: Support large user base across India
    
-   Usability: Simple, clear, mobile-friendly UI
    
-   Performance: Roadmap generation within acceptable response time
    
-   Security: Secure authentication and data protection
    
-   Accessibility: Low-bandwidth and low-cost usage
    

----------

## 7. Constraints & Assumptions

-   Internet access required
    
-   Job data availability depends on third-party APIs
    
-   AI outputs may require continuous tuning
    

----------

## 8. Success Metrics

-   User roadmap completion rate
    
-   Number of projects built
    
-   Job application conversion rate
    
-   User engagement and retention
    

----------

## 9. Conclusion

This requirements document ensures the solution remains **AI-driven, scalable, responsible, and Bharat-focused**, fulfilling Hack2Skill hackathon expectations.
