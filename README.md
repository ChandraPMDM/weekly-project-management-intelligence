# 📬 Weekly Project Management Intelligence

> An AI-powered workflow that automatically collects the latest Project Management trends, generates a professional weekly newsletter using OpenAI, and delivers it via Gmail.

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-EA4B2C?logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1-10A37F?logo=openai&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-Email-D14836?logo=gmail&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

# 📖 Overview

**Weekly Project Management Intelligence** is an AI-powered automation built using **n8n**, **OpenAI GPT-4.1**, **RSS feeds**, JavaScript, and Gmail.

Every weekend, the workflow automatically:

- 📰 Collects the latest Project Management news
- 🤖 Uses AI to generate a structured newsletter
- 📬 Emails the newsletter to subscribers
- 📚 Highlights Agile, Scrum, AI, Leadership, Risk Management, and PM Best Practices

The solution is designed for:

- Technical Delivery Managers
- Project Managers
- Scrum Masters
- PMO Professionals
- Agile Coaches
- Program Managers

---

# ✨ Features

- ⏰ Weekly scheduled execution
- 📰 RSS feed aggregation
- 🤖 OpenAI-powered newsletter generation
- 📧 Automatic Gmail delivery
- 🧠 AI-generated executive summary
- 🔥 Top Project Management trends
- 🚀 Agile & Scrum best practices
- 🤖 AI in Project Management
- 📚 Learning resources
- 💼 Interview preparation section
- ✍️ LinkedIn-ready content generation

---

# 🏗 Solution Architecture

```text
                    Every Saturday

                          │
                          ▼

                 Schedule Trigger (n8n)

                          │
                          ▼

                  Project Management RSS

                          │
                          ▼

             JavaScript Data Processing

                          │
                          ▼

             OpenAI GPT-4.1 Mini

                          │
                          ▼

          AI Generated HTML Newsletter

                          │
                          ▼

                 Gmail Email Delivery
```

---

# ⚙ Workflow

```text
Schedule Trigger
        │
        ▼
RSS Feed Reader
        │
        ▼
JavaScript Processing
        │
        ▼
OpenAI GPT
        │
        ▼
Gmail
```

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| OpenAI GPT-4.1 Mini | AI Newsletter Generation |
| JavaScript | Data Processing |
| Gmail | Email Delivery |
| RSS | News Aggregation |

---

# 📬 Newsletter Includes

Each weekly newsletter contains:

- Executive Summary
- Top Project Management Trends
- Industry News
- Agile & Scrum Best Practices
- AI in Project Management
- Risks & Challenges
- Learning Resources
- Interview Questions
- LinkedIn Article
- References

---

# 💼 Business Value

This solution helps Project Management professionals stay updated without spending hours reading multiple websites.

### Benefits

- Saves research time
- Delivers curated Project Management insights
- Supports continuous learning
- Generates LinkedIn-ready content
- Encourages knowledge sharing across teams

---

# 🚀 Future Enhancements

### Version 1.1
- Professional documentation
- HTML email formatting

### Version 2.0
- Multiple RSS feeds (PMI, Scrum.org, Atlassian, InfoQ)
- Duplicate article removal
- AI relevance ranking

### Version 3.0
- Google Drive archive
- Google Sheets history
- Weekly trend dashboard

### Version 4.0
- LinkedIn post automation
- AI-generated social media graphics

### Version 5.0
- AI Project Management Knowledge Base
- Chat with historical newsletters
- Interactive analytics dashboard

---

# 📸 Screenshots

> Screenshots will be added soon.

- Workflow
- Sample Newsletter
- Execution History

---

# 📂 Repository Structure

```text
weekly-project-management-intelligence/

├── README.md
├── LICENSE
├── workflow/
│   └── Weekly_PM_Intelligence.json
├── docs/
├── prompts/
├── screenshots/
└── assets/
```

---

# 🚀 Getting Started

## Prerequisites

- n8n Cloud or Self-hosted n8n
- OpenAI API Key
- Gmail Account

## Installation

1. Clone this repository.
2. Import the workflow JSON into n8n.
3. Configure your OpenAI credentials.
4. Configure Gmail OAuth.
5. Activate the workflow.
6. Test the execution.

---

# 📈 Project Roadmap

- [x] Weekly AI Newsletter
- [x] Gmail Integration
- [x] OpenAI Integration
- [x] HTML Email Support
- [ ] Multi-source News Aggregation
- [ ] Google Drive Archive
- [ ] Google Sheets Dashboard
- [ ] LinkedIn Automation
- [ ] PM Knowledge Base

---

# 🎯 Skills Demonstrated

This project showcases practical experience with:

- AI Workflow Automation
- Prompt Engineering
- Low-Code Development
- API Integration
- Workflow Orchestration
- JavaScript
- Email Automation
- AI Content Generation
- Technical Documentation

---

# 👨‍💻 Author

**Chandra Shekar D**

Technical Delivery Manager | Agile Practitioner | AI Automation Enthusiast

GitHub: https://github.com/ChandraPMDM

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Feedback and suggestions are always welcome.

---

## 📜 License

This project is licensed under the MIT License.
