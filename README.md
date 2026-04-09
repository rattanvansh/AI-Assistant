# 🤖 AI Assistant with Flask

An AI-powered web application that functions as a personal assistant, capable of answering user queries and generating concise email summaries in real time. The system leverages Large Language Models (LLMs) through OpenAI APIs to produce context-aware and human-like responses, providing a seamless conversational experience via a web interface.

---

## 🚀 Overview

This project is designed to demonstrate the integration of modern AI capabilities into a full-stack web application. It combines a lightweight Flask backend with a responsive frontend to enable dynamic interaction between users and an AI model.

The assistant supports two primary functionalities:
- General-purpose question answering through a conversational interface  
- Email summarization into short, meaningful outputs  

By utilizing prompt-based interactions with LLMs, the application adapts its responses based on the context of user input.

---

## ✨ Key Features

- **AI-powered Question Answering:**  
  Responds to user queries with contextually relevant and coherent answers using GPT-based models.

- **Email Summarization:**  
  Converts lengthy email content into concise summaries (2–3 sentences) while preserving key information.

- **Real-time Interaction:**  
  Enables smooth communication between frontend and backend using asynchronous requests.

- **Task-Specific Prompting:**  
  Uses different system instructions for distinct tasks (assistant vs email summarizer) to improve output quality.

- **Interactive User Interface:**  
  Provides a clean and structured UI with input forms, response sections, and loading indicators.

- **Secure Configuration:**  
  API keys are managed using environment variables to ensure safe and flexible deployment.

---

## 🧠 Tech Stack

- **Backend:** Flask (Python)  
- **AI/ML:** OpenAI GPT Models (Large Language Models - LLMs)  
- **Frontend:** HTML, CSS, JavaScript  
- **Environment Management:** python-dotenv  

---

## ⚙️ System Architecture

The application follows a simple client-server architecture:

1. **User Interaction:**  
   The user enters a query or email content through the web interface.

2. **Request Handling:**  
   The frontend sends a POST request to the Flask backend (`/ask` or `/summarize`).

3. **Processing Layer:**  
   The backend constructs a prompt and forwards the request to the OpenAI API.

4. **Model Inference:**  
   The LLM processes the input and generates a response based on the provided instructions.

5. **Response Delivery:**  
   The generated output is returned to the frontend and displayed dynamically.

---

## 🔗 Core Functionalities

### ➤ AI Assistant (Q&A)
- Accepts user questions  
- Generates conversational responses  
- Designed to simulate a helpful personal assistant  

### ➤ Email Summarization
- Accepts long email content  
- Produces concise summaries  
- Focuses on extracting key information  

---

## 🎯 Design Considerations

- **Modular Backend:** Separate routes for different functionalities ensure scalability  
- **Prompt Engineering:** Customized prompts enhance response relevance and accuracy  
- **Asynchronous Communication:** Improves user experience by preventing UI blocking  
- **Minimalistic UI:** Focuses on usability and clarity  

---

## 📌 Use Cases

- Personal productivity assistant  
- Quick summarization of emails or long text  
- Demonstration of LLM integration in web applications  
- Educational project for understanding AI + Web development  

---

## 📜 License

This project is intended for educational and learning purposes.
