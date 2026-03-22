# 🤖 AI Legislative Analyzer

> Making legal information simple, accessible, and understandable for everyone 🇮🇳

---

## 📌 Overview
The **AI Legislative Analyzer** is an advanced web-based platform designed to simplify complex legal documents such as parliamentary bills, government regulations, and court judgments.

It uses **Artificial Intelligence (Google Gemini model)** to convert dense legal text into:
- ✅ Easy-to-understand language  
- 🌐 Multilingual explanations  
- 📊 Structured summaries  

---

## 🎯 Objectives

- 🔹 Simplify complex legal language  
- 🔹 Improve accessibility for common citizens  
- 🔹 Enable quick information retrieval  
- 🔹 Promote legal awareness and civic engagement  

---

## ⚙️ Features

- 📄 Legal Document Summarization  
- 🌍 Multilingual Support  
- 🔍 Key Insights Extraction  
- 🧠 AI-Powered Analysis  
- 💡 User-Friendly Interface  

---

## 🛠️ Tech Stack

- **Framework:** Next.js(App Router,v14.2),React 18  
- **Language:** Typescript  
- **Styling:** Custom CSS(Glassmorphic UI,animations)
- **API Integration:** Google Gemini API(gemini-2.0-flash)
- **File Parsing:** pdf-parse library
---

## ⚙️ Core Features

### 📖 Plain Language Translation
Converts complex legal jargon into simple English.

### 📝 Actionable Summaries
- Bullet-point insights  
- Includes *TL;DR* summary

---

## 📷 Screenshots
*![WhatsApp Image 2026-03-22 at 20 24 12](https://github.com/user-attachments/assets/fabba717-26b8-46d8-9abb-42540fc32e0e)
*<img width="1600" height="999" alt="image" src="https://github.com/user-attachments/assets/59e3df3f-4e83-4a96-b7a0-68856e650b5c" />


---

## 📂 Project Structure
AI-Legislative-Analyzer/
├── app/
├── lib/
├── public/
├── README.md
├── package.json
├── next.config.js
└── next-env.d.ts
### 🔍 Key Insight Extraction
Automatically identifies:
- 📌 Key Provisions  
- ⚡ Law Changes  
- 🛡️ Citizen Rights  
- ⚖️ Penalties  
- 📅 Important Dates  

### 🌍 Multilingual Support (10 Languages)
Supports:
English, Hindi, Tamil, Telugu, Bengali, Marathi, Gujarati, Kannada, Malayalam, Punjabi  

### ⚖️ Bill Comparison Tool
Compare two versions of a bill side-by-side.

### 🔊 Accessibility
Built-in *Text-to-Speech (Voice Player)*  

---

## 🔄 How It Works

### 1️⃣ Input Stage
Users can:
- Paste text  
- Upload PDF/TXT  
- Provide website URL  

### 2️⃣ API Authentication
Users enter their own *Gemini API Key*

### 3️⃣ Smart Processing (Backend)
- Parses document  
- Handles size limits  

#### 📊 Strategy:
- Small docs → Single prompt  
- Large docs (80,000+ chars) → Chunking system
