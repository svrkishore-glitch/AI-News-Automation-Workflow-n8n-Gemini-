````md
# 📰 AI News Automation Workflow (n8n + Gemini)

An automated AI-powered news aggregation workflow built using **n8n**, **Google Gemini**, and **Gmail**.

This workflow automatically collects the latest AI and tech news from multiple RSS feeds, processes the content using **Google Gemini AI**, and sends summarized updates directly to your email.

---

## 🚀 Features

✅ Daily scheduled execution  
✅ Fetches news from multiple RSS sources  
✅ Merges and processes news automatically  
✅ AI-powered summarization using Gemini  
✅ Automatic Gmail delivery  

---

## 🛠️ Workflow Architecture

```text
Schedule Trigger
        ↓
RSS Feed (AI Business)
        ↓
RSS Feed (TechCrunch)
        ↓
Merge News Data
        ↓
Aggregate Content
        ↓
Google Gemini AI
        ↓
Email Notification (Gmail)
````

---

## 📌 Technologies Used

* **n8n** – Workflow Automation
* **Google Gemini API** – AI Processing
* **Gmail API** – Email Automation
* **RSS Feeds** – News Collection

---

## ⚙️ Workflow Overview

### 1. Schedule Trigger

Automatically starts the workflow every day.

### 2. RSS Feed Reader

Fetches latest AI and tech news from:

* AI Business RSS Feed
* TechCrunch RSS Feed

### 3. Merge & Aggregate

Combines all collected news into one structured flow.

### 4. Gemini AI Processing

Processes and summarizes the fetched content using **Google Gemini**.

### 5. Email Delivery

Sends the generated news summary directly to Gmail.

---

## 🔧 Setup Guide

### Prerequisites

Make sure you have:

* n8n installed
* Google Gemini API Key
* Gmail OAuth configured

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Open **n8n** and:

1. Import the workflow JSON file
2. Configure Gemini credentials
3. Configure Gmail OAuth
4. Activate the workflow

---

## 📧 Use Cases

* Daily AI News Updates
* Tech Monitoring
* Automated Research
* Productivity Automation

---

## 🔮 Future Improvements

* Add more RSS feeds
* Better AI prompts
* Telegram/WhatsApp notifications
* Save summaries to Notion or Google Sheets
* Personalized filtering

---

## 👨‍💻 Author

**Kishore**

GitHub: https://github.com/your-github-username

---

⭐ If you found this useful, give this repository a star!

```
```
