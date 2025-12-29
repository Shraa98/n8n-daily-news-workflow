# 📰 Automated Daily Sports & Tech News (n8n)

This project automates the delivery of daily Sports and Technology news using **n8n workflow automation**.

## 🚀 Features
- Scheduled daily execution using Cron
- Fetches live news from NewsAPI
- Separates Sports and Technology articles
- Formats content into HTML emails
- Sends automated emails via Gmail

## 🛠 Tech Stack
- n8n (Workflow Automation)
- NewsAPI (REST API)
- JavaScript (Data transformation)
- Cron Scheduling
- Gmail OAuth

## 📂 Workflow Overview
1. Cron Trigger starts the workflow at a fixed IST time
2. Sports and Tech news are fetched using REST APIs
3. Data is merged and transformed using JavaScript
4. HTML email is generated
5. Email is sent automatically

## 📌 Use Cases
- Daily news digest
- Automated reporting
- Newsletter automation
- Personal productivity automation
