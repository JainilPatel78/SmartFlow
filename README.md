# SmartFlow 📋

SmartFlow is an intelligent task management web application that goes beyond simple to-do lists. Built with Django and integrated with GenAI, it analyzes broad user tasks and automatically generates structured workflows and prioritizes them.

## 🚀 Key Features

* **AI Auto-Plan:** Input a broad goal (e.g., "Prepare for a Java interview"), and the LLM integration will automatically break it down into a step-by-step execution workflow.
* **Smart Prioritization:** Utilizing text analysis, the application scans task descriptions for urgency keywords and automatically assigns priority levels (High/Medium/Low).
* **Secure User Management:** Features robust user authentication and session management built natively with Django.
* **REST API Endpoints:** Designed with a scalable architecture, exposing endpoints for seamless interaction between the frontend and backend.

## 💻 Tech Stack

* **Backend:** Python, Django
* **Database:** SQLite (or mention PostgreSQL/MySQL if you configured it)
* **AI Integration:** LLM API (Gemini/OpenAI) for task breakdown and text analysis
