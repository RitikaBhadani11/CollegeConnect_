# 💼 College Connect – Networking Platform for Students, Alumni & Faculty

<div align="center">

![College Connect](https://img.shields.io/badge/College-Connect-blue?style=for-the-badge&logo=graduation-cap)
![React](https://img.shields.io/badge/React-18.3-blue?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-18-green?style=for-the-badge&logo=nodedotjs)
![MongoDB](https://img.shields.io/badge/MongoDB-8.15-green?style=for-the-badge&logo=mongodb)

**A Professional Networking Platform Connecting Students, Alumni & Faculty**

[![Watch Live Demo]([https://img.shields.io/badge/🚀_Watch_Live_Demo-Click_Here-red?style=for-the-badge&logo=netlify](https://drive.google.com/file/d/1kKbI1X-LZMf8w7kSG_o8ZeXcFBPlrmjF/view?usp=sharing)]


</div>

## 📖 Introduction

**College Connect** is a full-stack web application built to connect students, alumni, and faculty members of a college on a single, reliable platform. It allows users to create professional profiles, share their experiences, and explore opportunities — whether it's for career growth, collaborations, or staying updated with the college network.

### 🎯 Project Overview
College Connect provides a complete networking ecosystem with:
- Professional profile management and connections
- Real-time chat and messaging system
- Job opportunities and career postings
- Event management and college updates
- AI-powered smart recommendations

## 🏗️ System Architecture

```mermaid
graph TD
    U[🎓 User] -->|🌐 HTTP Requests| R[⚛️ React Frontend]
    R -->|🔐 REST API| N[🍃 Node.js Backend]
    N -->|💾 Data Storage| M[🗄️ MongoDB Atlas]
    N -->|☁️ File Storage| C[🌩️ Cloudinary]
    N -->|🤖 AI Features| G[🧠 Google Generative AI]
    R -->|⚡ Real-time| S[🔌 Socket.io Server]
    S -->|🔄 Live Updates| N
    G -->|💡 Smart Recommendations| R
    
    style U fill:#4F46E5,color:white
    style R fill:#61DAFB,color:black
    style N fill:#339933,color:white
    style M fill:#47A248,color:white
    style C fill:#3448C5,color:white
    style G fill:#4285F4,color:white
    style S fill:#010101,color:white
