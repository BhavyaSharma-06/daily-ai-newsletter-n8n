# 🧠 Daily AI Newsletter Automation (n8n)

This project automates a daily AI news digest using `n8n`. It reads top headlines from an RSS feed, summarizes them with GPT-4, and sends a beautifully formatted newsletter to your email.

---

## ✨ Features

- 🔄 Triggered manually or on schedule
- 🗞 Pulls fresh articles from an AI news RSS feed (e.g., VentureBeat)
- 🤖 Summarizes each article using OpenAI GPT (via contentSnippet)
- 🧹 Combines all summaries into a clean HTML newsletter
- 📬 Sends the email directly via Gmail integration
- 📦 All logic built using n8n's visual workflow builder — no code required!

---

## 🧰 Tech Stack

| Layer         | Tools Used                 |
|--------------|----------------------------|
| Workflow Tool | n8n (self-hosted/cloud)    |
| AI Model      | OpenAI GPT-4 / GPT-4o-mini |
| News Source   | RSS Feed (VentureBeat)     |
| Email Sender  | Gmail (OAuth2 Auth)        |
| HTML Editor   | n8n built-in Code + Set    |

---

## 📂 Folder Structure

daily-ai-newsletter-n8n/
├── workflow.json # Exported n8n workflow (importable)
├── README.md # Project overview and documentation


---

## 🚀 How to Use

### 1. Clone the Project

```bash
git clone https://github.com/your-username/daily-ai-newsletter-n8n.git
cd daily-ai-newsletter-n8n
