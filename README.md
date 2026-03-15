# 🤖 AI-Powered Organizational Chatbot

An intelligent chatbot built using **Deep Learning** and **Natural Language Processing (NLP)** to help employees of large organizations quickly find answers to their questions related to **HR policies, IT support, company events, and other organizational information**.

The chatbot also includes **document processing capabilities**, allowing users to upload documents and extract useful information such as summaries and keywords.

---

## 📌 Problem Statement

Develop a chatbot using **Deep Learning and Natural Language Processing techniques** that can understand and respond to queries from employees of a large public sector organization.

The chatbot should:

- Answer questions related to **HR policies**
- Provide **IT support guidance**
- Share **company events and announcements**
- Process uploaded documents to extract useful information
- Support multiple users simultaneously
- Maintain security through **Two-Factor Authentication (2FA)**
- Filter inappropriate language

---

## 🚀 Features

### 🧠 Intelligent NLP Chatbot
- Understands natural language queries from employees
- Provides automated responses
- Handles queries related to:
  - HR policies
  - Leave rules
  - IT support issues
  - Company events
  - Organizational guidelines

---

### 📄 Document Processing
Employees can upload documents to the chatbot for analysis.

Supported capabilities:

- **Text extraction**
- **Keyword extraction**
- **Document summarization**

For demonstration, an **8–10 page document** is used to show how the chatbot processes uploaded files.

---

### 👥 Multi-User Support
The chatbot architecture is designed to be **scalable**.

- Supports **minimum 5 users simultaneously**
- Optimized response time
- **Response time ≤ 5 seconds per query** (unless affected by connectivity issues)

---

### 🔐 Two-Factor Authentication (2FA)
Security is enhanced using **Email-based Two Factor Authentication**.

Authentication process:

1. User logs in to the chatbot
2. A verification code (OTP) is sent to the registered email
3. User enters the OTP
4. Access is granted after verification

---

### 🚫 Bad Language Filtering
The chatbot includes a **bad language detection system**.

- Uses a **system-maintained dictionary**
- Detects offensive words
- Prevents inappropriate communication

---

## 🏗 System Architecture

User → Login + 2FA → Chatbot Interface → NLP Processing Engine → Knowledge Base → Response Generation → User

If a document is uploaded:

Document Upload → Text Extraction → Keyword Extraction / Summarization → Output to User

---

## 🛠 Technologies Used

- **Python**
- **Natural Language Processing (NLP)**
- **Deep Learning**
- **Flask / FastAPI**
- **HTML, CSS, JavaScript**
- **NLTK / SpaCy**
- **Transformers (for summarization)**
- **PyPDF / PDFMiner (for document text extraction)**
- **Email API (for 2FA authentication)**

---

## 📂 Project Structure

```
organizational-chatbot
│
├── chatbot
│   ├── model
│   ├── training_data
│   └── response_engine
│
├── document_processing
│   ├── text_extraction
│   ├── summarization
│   └── keyword_extraction
│
├── authentication
│   └── email_2fa
│
├── frontend
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 📊 Performance Requirements

- Supports **minimum 5 concurrent users**
- **Response time ≤ 5 seconds**
- Scalable architecture for future expansion

---

## 📄 Sample Data Sources

Publicly available sample information is used for demonstration purposes, including:

- HR policy documents
- IT support guidelines
- Organizational information

---



---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/organizational-chatbot.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the chatbot:

```bash
python app.py
```

---

## 🔐 Security Features

- Email-based **Two-Factor Authentication**
- Offensive language filtering
- Secure query handling

---

## 👨‍💻 Author

**Deepak G**  
Hackathon Project Submission
