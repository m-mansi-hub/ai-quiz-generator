AI Quiz Generator
An intelligent quiz generation application powered by LLaMA 3.1 via Groq API — COMP 491 Final Project
________________________________________
Overview
The system uses LLM technology to create quiz questions from any text input. A user needs to paste text into the system and choose their desired question type and number of questions to receive an instant complete quiz. The project was developed through the COMP 491 course which focuses on Machine Learning at Almaarefa University.
________________________________________
Features
•	3 Question Types: Multiple Choice and True/False and Short Answer
•	Generate 1–10 questions 
•	Instant Output: Powered by LLaMA 3.1 (8B) via Groq's fast inference API
•	Copy-Ready
•	Shareable
________________________________________
Tech Stack
Component	Technology
Language	Python 3
UI Framework	Gradio
LLM Provider	Groq API
Model	LLaMA 3.1 (llama-3.1-8b-instant)
Platform	Google Colab
________________________________________
Getting Started
1. Clone the Repository
git clone https://github.com/m-mansi-hub/ai-quiz-generator
2. Get a Free Groq API Key
•	Go to console.groq.com
•	Sign up → API Keys → Create API Key
3. Set Up in Google Colab
•	Open the notebook in Google Colab
•	Go to Secrets (left sidebar)
•	Add a new secret: GROQ_API_KEY → paste your key
•	Enable Notebook access for the secret
4. Run the Cells
Run all 3 cells in order. The last cell create a public shareable link.
________________________________________
How to Use
1.	Paste any in the Input Text box
2.	Select Question Type
3.	Set the Number of Questions 
4.	Click Generate Quiz
5.	See the result
________________________________________
Project Structure
ai-quiz-generator/
├── quiz_generator.ipynb   # Main Colab notebook
└── README.md              # Project documentation
________________________________________
Responsible AI Practices
•	No hardcoded API keys — keys are stored in Colab Secrets
•	Error handling — all API calls wrapped in try/except blocks
•	Model transparency — model name and provider clearly documented
•	Privacy — no user input is stored or logged
________________________________________
Example
Input Text:
Machine learning is a subset of artificial intelligence that enables systems to learn from data without being explicitly programmed...
Question Type: Multiple Choice | Count: 3
Generated Output:
1. What is machine learning a subset of?
   A) Data Science
   B) Artificial Intelligence ✅
   C) Statistics
   D) Computer Networks

2. In supervised learning, the algorithm is trained on:
   A) Unlabeled data
   B) Random data
   C) Labeled data ✅
   D) Compressed data

3. What is a key component of deep learning?
   A) Decision Trees
   B) Neural Networks ✅
   C) Linear Regression
   D) K-Means Clustering
________________________________________
Team
Name
Mohammad mansi
Mohammed Saeed
Course: COMP 491 — Machine Learning
University: Almaarefa University
Semester: 2024–2025

