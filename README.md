# ⚖️ AI Legal Document Generator

A **team-developed AI-powered web application** that generates **professional legal document templates** based on user instructions.  
The system uses a Large Language Model (LLM) to create **industry-standard, reusable legal drafts** with editable placeholders.

---

## 👥 Team Project

**Project Title:** AI Legal Document Generator  
**Team Name:** TEAM-16  
**Project Type:** Academic / Mini Project  
**Domain:** Artificial Intelligence, NLP, Legal Tech  

---

## 🚀 Project Overview

Legal document drafting is time-consuming and requires precise structure and formal language.  
This project automates the generation of **legal document templates** such as agreements, contracts, and notices using AI.

The user only specifies the **type of legal document**, and the system generates a **complete, structured legal template** in `.docx` format.

---

## ✨ Key Features

- ⚖️ AI-powered legal document generation
- 📄 Generates **complete legal templates**
- 🧩 Uses editable placeholders instead of real data
- 📝 Professional legal language and structure
- 📥 Downloadable Word document (.docx)
- 🌐 Simple web interface using Flask

---

## 🧠 How It Works

1. User enters the **type of legal document** (e.g., NDA, Lease Agreement)
2. The system sends a structured prompt to the AI model
3. The AI generates a **standard legal document template**
4. The output is saved as a **Word (.docx) file**
5. User downloads the generated document

---

## 🛠️ Tech Stack

- **Python**
- **Flask** – Web framework
- **Groq API** – Large Language Model (LLM)
- **LLaMA 3.3 (70B)** – Text generation
- **python-docx** – Word document creation
- **dotenv** – Environment variable management
- **HTML/CSS** – Frontend templates

---

## 📂 Project Structure

ai-legal-doc-generator/
│
├── app.py
├── templates/
│ └── index.html
├── .env
├── requirements.txt
├── README.md



---

## ⚙️ Installation & Setup

1️⃣ Clone the Repository
bash
git clone https://github.com/your-username/ai-legal-doc-generator.git
cd ai-legal-doc-generator
2️⃣ Create Virtual Environment (Optional)
bash

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
3️⃣ Install Dependencies
bash
pip install flask groq python-docx python-dotenv
🔐 Environment Variables
Create a .env file in the root directory:

env

GROQ_API_KEY=your_api_key_here
⚠️ Do not upload .env to GitHub

▶️ Run the Application
bash

python app.py
Open in browser:


http://127.0.0.1:5000
📄 Supported Output
Legal document templates in .docx (Word format)

Uses placeholders like:


[PARTY_NAME]
[DATE]
[ADDRESS]


🎯 Use Cases
Law students & legal research

Legal documentation assistance

Contract drafting templates

AI + Legal Tech academic projects

NLP-based automation systems


⚠️ Disclaimer
This application does not provide legal advice.
Generated documents are templates and should be reviewed by a qualified legal professional before real-world use.


📌 Future Enhancements

User authentication

Multiple document formats (PDF)

Clause-level customization

Cloud deployment

Multi-language legal documents

👤 Team Members

Kishore

Team Member 2

Team Member 3

Team Member 4

