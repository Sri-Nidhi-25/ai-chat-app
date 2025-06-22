**Smart Chat Application**

Welcome to the Smart Chat Application repository! This project demonstrates a modern, AI-powered chat platform that stores user messages, answers questions using advanced AI, and leverages Astra DB for fast and reliable data storage.

Link to try the website - https://astra.datastax.com/langflow/f821e3a4-76a1-4344-88ea-2cac45e1d9c3/playground/4c11f27d-4027-44f4-ad2d-39894105283d

**Features**

Modular, production-grade React components (sourced from Astra DB's official UI library)

API endpoints for sending and receiving chat messages

User messages stored securely in Astra DB

AI-powered question answering using Groq’s state-of-the-art language models

Clean, scalable codebase ready for further enhancements


**Tech Stack**

Backend - Python

Database -Astra DB

AI Engine	- Groq

UI Components	- Astra DB Components



**How the App Works**


Send & Receive Messages: The API allows clients to send and retrieve chat messages.

Persistent Storage: All chat data is stored in Astra DB, ensuring high availability and scalability.

AI-Powered Answers: User questions are processed by Groq’s AI, providing intelligent and context-aware responses.

Component-Based UI: All UI components are sourced from Astra DB’s official component library for a professional and consistent look.



**API Testing**
You can test the API using the included Postman collection or with curl commands. Example:

curl --request POST \
  --url 'https://api.langflow.astra.datastax.com/lf/bcc998d0-5efd-4689-9c65-10b18ee0698b/api/v1/run/4c11f27d-4027-44f4-ad2d-39894105283d?stream=false' \
  --header 'Content-Type: application/json' \
  --header 'Authorization: Bearer <YOUR_APPLICATION_TOKEN>' \
  --data '{
  "input_value": "What is the document is about?",
  "output_type": "chat",
  "input_type": "chat"
}'


**Screenshots**
----



All Astra DB UI Components Included: Every component used in the application is included as a separate file in this repository for maximum modularity and reuse.

Clean & Documented Code: The codebase emphasizes readability and maintainability, with comments explaining key logic.

Impressive AI Integration: Harnesses Groq’s powerful AI models for natural and engaging user interactions.

Ready for Expansion: The architecture supports easy integration of additional features such as real-time messaging or caching layers.



**Notes**


This implementation focuses on Groq for AI and Astra DB for data storage, delivering a streamlined and robust chat experience.

While the original task suggested Redis for real-time updates or caching, this version prioritizes direct, high-performance access via Astra DB and Groq.

All UI components are directly sourced from Astra DB’s official component library for consistency and rapid development.
