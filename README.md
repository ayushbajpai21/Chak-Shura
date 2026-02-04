# 🚀 Chak-Shura — AI-Powered Defense Technology Analytics

An **AI-driven analytics platform** designed to identify, analyze, and summarize emerging **defense technology trends** from structured datasets.  
The system converts complex data into **actionable insights** using intelligent summarization and dashboard-style visual analytics.

---

## 🧠 Key Features

### 🔍 AI-Based Trend Identification
- Analyzes structured datasets to identify **emerging and critical defense technologies**
- Automatically generates **categorized insights, summaries, and key highlights**

### 📊 Technology Readiness Level (TRL) Analysis
- Visualizes technologies across **TRL stages (1–9)**
- Helps assess **technology maturity and deployment readiness**

### 📈 Interactive Dashboard Visualizations
- Dashboard-style charts and analytics views
- Simplifies **technology evaluation and decision-making**

### 🧾 Categorized Insights & Summaries
- Groups technologies into meaningful domains
- Produces **evaluation-ready summaries** for analysts and stakeholders

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite, Tailwind CSS  
- **Backend:** Node.js, Express  
- **AI & Data Processing:** Python-based analytics logic  
- **Visualization:** Dashboard charts & analytics components  
- **Data Source:** Structured datasets (CSV / JSON)

---

## 🎯 Use Cases

- 🛡️ Defense technology assessment  
- 📑 Research & innovation analytics  
- 🧠 Strategic decision support  
- 📊 Technology maturity tracking  

---

## 📌 Project Highlights

- Clean and modular architecture  
- Scalable analytics pipeline  
- Built for **real-world defense analytics scenarios**  
- Resume & placement-ready full-stack + AI project

---

# ⚙️ Project Setup & Run Guide

This section explains how to set up and run the project locally on your system.

---

## ✅ Prerequisites

Ensure the following tools are installed:

- **Node.js** (v18 or above recommended)
- **npm** (comes with Node.js)
- **Visual Studio Code (VS Code)**

---

## 🧩 Step-by-Step Setup

### 1️⃣ Open the Project in VS Code
1. Launch **Visual Studio Code**
2. Open the **project root folder**

---

### 2️⃣ Create Required Configuration Files

Inside the **project root directory**, create the following files **exactly with these names**:

- `.env`
- `.env.local`
- `.gitignore`

> ⚠️ File names (including dots) must be exactly the same.

---

### 3️⃣ Configure `.env` File

Add the following content to the `.env` file:

```env
VITE_FIREBASE_API_KEY=YOUR_FIREBASE_API_KEY
VITE_FIREBASE_AUTH_DOMAIN=chak-shura.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=chak-shura
VITE_FIREBASE_STORAGE_BUCKET=chak-shura.firebasestorage.app
VITE_FIREBASE_MESSAGING_SENDER_ID=616434260720
VITE_FIREBASE_APP_ID=1:616434260720:web:a1d6678358c4ce45878035

MONGO_URI=YOUR_MONGO_CONNECTION_STRING
MONGO_DB_NAME=intel_dashboard
PATENTS_COLLECTION=patents
PATENT_DOMAINS_COLLECTION=patent_domains

PUBLICATIONS_DB=intel_dashboard
PUBLICATIONS_COLLECTION=publications
PUBLICATIONS_CSV=ml/publication_intel/data/public.csv
VITE_API_BASE_URL=http://localhost:5001
# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
pnpm-debug.log*

node_modules
dist
dist-ssr
*.local
.env

# Editor files
.vscode/*
!.vscode/extensions.json
.idea
.DS_Store
npm install
cd server
npm run dev
http://localhost:5173

