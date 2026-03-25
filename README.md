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

<img width="1919" height="863" alt="chat-ui" src="https://github.com/user-attachments/assets/e55200f3-749e-40d9-aa52-b16c7aad2fba" />
<img width="1536" height="1024" alt="Architecture" src="https://github.com/user-attachments/assets/fffd9421-7fe7-43fa-a56c-a5fe8d35aaa2" />
<img width="1893" height="861" alt="lambda-code" src="https://github.com/user-attachments/assets/f2f8cd1d-340a-4049-84e9-a59197c14eff" />
<img width="1918" height="870" alt="api-gateway" src="https://github.com/user-attachments/assets/508a9ba6-d981-4c5a-9d7c-072da088544a" />
<img width="1919" height="879" alt="DynamoDB" src="https://github.com/user-attachments/assets/e2761fb8-ded1-4e5c-be3b-da16064e31be" />
<img width="1919" height="868" alt="S3 Hosting" src="https://github.com/user-attachments/assets/af8f83e1-8a4e-47fc-acf6-38465949c540" />
<img width="1919" height="859" alt="API stage invoke url" src="https://github.com/user-attachments/assets/5f0f3238-37fc-4f70-b234-8f390869582f" />
<img width="1919" height="874" alt="attach integration to method" src="https://github.com/user-attachments/assets/c77712fa-175a-40eb-91c3-b214b2ba702e" />


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
