# aws-serverless-chat-app
# 💬 Serverless ChatBot App using AWS

## 🚀 Project Overview

This project is a **Serverless Chat Application** built using **Amazon Web Services (AWS)**.
It allows users to send messages and receive automated replies using a keyword-based chatbot.

---

## 🧠 Features

* 💬 Real-time chat interface
* 🤖 Auto-reply chatbot (keyword-based)
* ☁️ Fully serverless architecture
* 📦 Messages stored in database
* 🌐 Hosted frontend using S3
* ⚡ Fast and scalable

---

## 🏗️ Architecture

User → API Gateway → Lambda → DynamoDB → Response → UI (S3)

---

## 🛠️ Technologies Used

* AWS Lambda (Backend logic)
* API Gateway (API handling)
* DynamoDB (Database)
* S3 (Frontend hosting)
* HTML, CSS, JavaScript (Frontend)

---

## 🔧 Setup Instructions

### 1️⃣ Create DynamoDB Table

* Table Name: `ChatMessages`
* Partition Key: `messageId` (String)

---

### 2️⃣ Create Lambda Function

* Runtime: Python 3.11
* Add DynamoDB permissions
* Paste chatbot code

---

### 3️⃣ Create API Gateway

* Create HTTP API
* Add Routes:

  * POST `/send`
  * GET `/messages`
* Connect Lambda
* Deploy API

---

### 4️⃣ Frontend Setup

* Create `index.html`
* Add API URL
* Upload to S3

---

### 5️⃣ Enable S3 Hosting

* Enable static website hosting
* Make bucket public

---

## 🔗 API Endpoints

* POST → `/send` → Send message
* GET → `/messages` → Get chat messages

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 💡 Future Improvements

* 🔐 User authentication
* ⚡ Real-time chat (WebSockets)
* 🎨 Better UI (React / Tailwind)
* 🤖 AI-based chatbot

---

## 👩‍💻 Author

**Pratiksha Lavand**

---

## ⭐ Acknowledgement

Thanks to AWS for providing serverless services.

---
