# 📰 Automated Daily Sports & Tech News (n8n)

This project is a **fully automated, deployed news delivery system** built using **n8n workflow automation**.  
It fetches the latest **Sports and Technology news**, formats them into a structured **HTML email**, and delivers them **automatically on a scheduled basis**.

---

## 🚀 Features
- ⏰ Scheduled daily execution using **Cron (IST timezone)**
- 🌐 Fetches live Sports & Tech news from **NewsAPI**
- 🔀 Merges multiple API responses into a single workflow
- 🧠 Transforms raw data using **JavaScript**
- 📨 Generates clean, readable **HTML email content**
- 🔐 Secure email delivery using **Gmail OAuth 2.0**
- ☁️ Deployed on **Render** for continuous execution

---

## 🛠 Tech Stack
- **n8n** – Workflow Automation
- **NewsAPI** – REST API for live news
- **JavaScript** – Data transformation & HTML generation
- **Cron** – Time-based scheduling
- **Gmail OAuth 2.0** – Secure email delivery
- **Render** – Cloud deployment
- **GitHub** – Version control & documentation

---

## 📊 Workflow Architecture
The automation is designed as a **modular, scalable pipeline**:

1. **Cron Trigger**  
   - Triggers the workflow daily at a fixed IST time

2. **Fetch Sports News**  
   - Calls NewsAPI with sports-related queries

3. **Fetch Technology News**  
   - Calls NewsAPI with tech-related queries

4. **Merge News Results**  
   - Appends Sports & Tech responses into a unified dataset

5. **Format Email Content (JavaScript)**  
   - Converts raw JSON into structured HTML  
   - Handles missing titles and descriptions safely

6. **Send Email (Gmail OAuth)**  
   - Sends formatted news directly to the inbox

---

## 🖼 Workflow Design (n8n)

![Workflow Design](assets/workflow-design.png)

---

## ☁️ Deployment
- The n8n instance is deployed as a **Web Service on Render**
- Workflows persist across restarts
- OAuth callback configured for secure Gmail authentication

**Live Instance:**
https://n8n-daily-news.onrender.com

> Access requires authenticated login to protect workflows and credentials.

---

## 📌 Use Cases
- Daily personal news digest
- Automated email newsletters
- Scheduled reporting systems
- No-code / low-code automation demos
- Workflow orchestration showcase

---

## 🔐 Security & Best Practices
- OAuth 2.0 used instead of app passwords
- No secrets committed to GitHub
- `.env` and credentials excluded via `.gitignore`
- Workflow export is safe to share

---

## 🧠 Key Learnings
- Designing event-driven workflows
- Integrating multiple APIs in automation
- Handling OAuth in production systems
- Deploying workflow tools to cloud platforms
- Structuring automation projects for maintainability

---

## 👤 Author
**Shravani Kairamkonda**  
GitHub: https://github.com/Shraa98

---

⭐ If you found this project useful, feel free to star the repository!



