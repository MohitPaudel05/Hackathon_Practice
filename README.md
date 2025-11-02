# 🤖 OG CODE - AI Detection Coding Platform

## 🚀 Overview
**OG CODE** is a coding platform where users can practice and test their programming skills.  
Unlike traditional platforms, TradeCode integrates an **AI Detection System** powered by a **Random Forest model** that evaluates how much of a submitted code is **AI-generated** versus **human-written**.

Our goal is to promote authentic learning and fair coding practices while providing organizations with a new way to **evaluate real coding skills**.

---

## 🧠 Core Features

- 🧩 **AI Detection System** – Analyzes submitted code to determine the percentage of AI-generated vs human-written content.  
- 🧮 **Custom RandomForest Model** – Trained on real-world data using advanced code features such as:
  - Code repetition patterns  
  - Comment density  
  - Variable naming style  
  - Submission timing  
  
- 🔐 **No Copy-Paste System** – Encourages genuine problem-solving and originality.  
- 🏆 **Leaderboard System** – Users earn points for each submission. Higher points are awarded for more *human-like* solutions.  
- 💻 **Skill Testing Environment** – Users can attempt coding challenges similar to LeetCode and get instant AI evaluation feedback.  
- 🔁 **Dual Backend System**
  - **.NET Backend** – Handles user management, authentication, and question distribution.  
  - **FastAPI Backend** – Processes AI detection using the trained model.

---

## ⚙️ Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | React  |
| **Backend (Main)** | ASP.NET Core (.NET 8) |
| **Model Backend** | FastAPI (Python) |
| **Machine Learning Model** | Random Forest Classifier |
| **Database** | SQL Server / PostgreSQL |
| **Version Control** | Git + GitHub |
| **API Testing** | Postman / Ngrok for tunneling |

---

## 🔄 Workflow

1. **User Login/Register**  
2. **Attempt Coding Challenge** (questions served via .NET backend)  
3. **Submit Code**  
4. **AI Detection**  
   - Code is analyzed via FastAPI using RandomForest Model.  
   - Returns % of AI vs Human-written content.  
5. **Leaderboard Update**  
   - Points are awarded based on the *human originality score*.  
6. **No Copy-Paste Enforcement**  
   - Promotes fair code submission.

---

## 💡 Future Vision
- 📈 **Multi-language Support** – Extend AI detection beyond JavaScript. 
- 📈 **Sell AI Detection API** to hiring companies for code authenticity checks.  
- 🧑‍💼 **Monetize Platform** by offering premium coding tests and enterprise APIs.  
- 🤝 **Partner with Tech Platforms** for integration into online hiring and learning systems.  
- 📊 **Expand Model Accuracy** by including more advanced features and datasets.

---

## 🏁 Demo Pitch Summary

> “OG CODE is an AI-driven coding platform that not only tests your skill but also validates your authenticity.  
> It detects AI-written code, promotes fair learning, and can even serve as a code authenticity API for tech companies.”

---

## 🧩 Contributors

- **Team Void** – Hackathon Project 2025  
  - Backend Developer – .NET  
  - AI Engineer – FastAPI & Model Training  
  - Frontend Developer – UI/UX  

---



This project is developed for **Hackathon demo purposes only**.  




