# HuntHelper

## 🚀 Overview

HuntHelper is an AI-powered Resume & Cover Letter Generator that creates professional documents based on user input using OpenAI's GPT model.

## 🛠 Tech Stack

- **Frontend:** React (Vite), TailwindCSS, ShadCN UI
- **Backend:** Node.js (Express)
- **AI Integration:** OpenAI GPT API

## 🎯 Features

- Generate AI-powered **Resume & Cover Letter**
- Interactive UI with **ShadCN + TailwindCSS**
- API backend using **Node.js + Express**
- (Upcoming) Download as **PDF**

## 🚀 Setup

### 1️⃣ Clone & Install

```
git clone https://github.com/your-username/hunthelper.git
cd hunthelper
npm install

```

### 2️⃣ Run Frontend

```
npm run dev

```

### 3️⃣ Run Backend

```
cd backend
npm install
node server.js

```

## 📌 API Endpoint

**POST `/generate-resume`**

```
{
  "jobTitle": "Software Engineer",
  "skills": "React, Node.js, AI"
}

```

**Response:**

```
{
  "resume": "Generated Resume Content..."
}

```

## 🤝 Contributing

Fork & improve the project!

## 📜 License

MIT License © 2025 Sanidhya
