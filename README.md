# MailMate-AI
Smart Email Assistant Backend

A Spring Boot backend application that generates AI-powered professional email replies using the Google Gemini API.
This project demonstrates my skills in Java, Spring Boot, REST API development, and AI/ML integration by building a real-world productivity tool.

**🔹 Key Highlights**

-  **AI Integration** – Uses Google Gemini for natural language email generation.

-  **Custom Tone Control** – Generates replies in different tones (e.g., professional, casual, friendly).

-  **RESTful API** – Exposes a clean endpoint /api/email/generate for frontend or third-party integration.

-  **Scalable Design** – Built with Spring Boot + WebClient, ready for production-level workloads.

-  **CORS Enabled** – Can seamlessly connect with React, Angular, or mobile clients.

**🛠️ Tech Stack**

-  **Java (Spring Boot)** – Core backend & REST API

-  **Google Gemini API** – AI-powered email generation

-  **Lombok** – Clean, boilerplate-free Java code

-  **Maven** – Build & dependency management

**📌 Example Usage**

-  **Endpoint:** POST /api/email/generate

{
  "emailContent": "Hello, I would like to schedule a meeting with you next week.",
  "tone": "professional"
}


**✅ Response:** AI-generated professional reply.

**🚀 Real-World Applications**

-  Customer support automation

-  Smart business communication tools

-  Personal AI email assistant

-  Integration with CRM or productivity platforms
