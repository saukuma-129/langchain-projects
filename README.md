🚀 LangChain Projects

This repository contains hands-on projects built using LangChain and OpenAI APIs, focusing on real-world applications of Large Language Models (LLMs).

📌 Projects Included
🔹 Q&A Assistant

A simple chatbot that provides concise and controlled answers using prompt engineering.

🔹 Prompt Template Demo

Demonstrates dynamic prompt generation using LangChain’s ChatPromptTemplate.

🔹 Resume Analyzer

Analyzes resumes and provides structured feedback including strengths, weaknesses, and improvement suggestions.

🛠️ Tech Stack
Python
LangChain
OpenAI API
python-dotenv
📁 Project Structure
langchain-projects/
│
├── apps/              # Entry point applications
├── chains/            # Prompt templates and chains
├── utils/             # Helper functions
├── data/              # Sample inputs
│
├── requirements.txt
├── README.md
├── .gitignore
⚙️ Setup Instructions
1. Clone the repository
git clone https://github.com/saukuma-129/langchain-projects.git
cd langchain-projects
2. Create virtual environment
python -m venv venv
venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt
4. Add environment variables

Create a .env file:
OPENAI_API_KEY=your_api_key_here

▶️ Running the Projects

Example:
python apps/qa_assistant.py

🎯 Learning Objectives
Understand LLM integration using LangChain
Implement prompt engineering techniques
Build real-world AI-powered applications
Structure scalable Python projects

⚠️ Notes
.env file is excluded from version control
Ensure you have valid OpenAI API credits

👨‍💻 Author
Saurabh Kumar
Staff Software Engineer | Distributed Systems | AI Enthusiast
