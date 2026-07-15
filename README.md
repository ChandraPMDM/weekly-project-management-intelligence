[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1-10A37F?logo=openai&logoColor=white)](https://platform.openai.com/)
[![n8n](https://img.shields.io/badge/n8n-Workflow-EA4B71?logo=n8n&logoColor=white)](https://n8n.io/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![MIT License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success)](#)

# 📬 Weekly Project Management Intelligence

Automate your weekly Project Management intelligence with AI, n8n, OpenAI GPT-4.1, RSS feeds, and Gmail—delivering curated insights directly to your inbox every week.

---
<p align="center">
  <img src="assets/architecture.png" width="95%" alt=" Architecture">
</p>

## 📖 Overview

This project automates the creation and delivery of a professional weekly Project Management newsletter using AI and workflow automation.

Instead of manually browsing multiple Project Management websites every week, this workflow automatically:

- Collects articles from leading PM websites using RSS feeds
- Filters relevant content
- Uses OpenAI GPT-4.1 to summarize and categorize insights
- Generates a professional HTML newsletter
- Sends the newsletter automatically via Gmail every Saturday

The solution is built completely in **n8n**, making it easy to customize, extend, and deploy.

---

## ✨ Features

- 🤖 AI-powered newsletter generation
- 📚 Collects articles from multiple PM RSS feeds
- 📰 Weekly automated digest
- 📧 Automatic Gmail delivery
- 🧠 GPT-4.1 summarization
- ⚡ Built completely in n8n
- 📈 Easily extensible
- 🔒 Uses OAuth authentication
- 💰 Low-cost execution

---

## 🏗 Workflow

The automation executes in the following sequence:

1. Schedule Trigger
2. RSS Feed Collection
3. JavaScript Processing
4. OpenAI Analysis
5. HTML Newsletter Generation
6. Gmail Delivery

---

## 📸 Screenshots

### Workflow

![Workflow](screenshots/workflow/workflow.png)

### Newsletter

![Newsletter](screenshots/Newsletter.png)

### Execution

![Execution](screenshots/Execution.png)

---

## 🚀 Installation

1. Clone this repository.

```bash
git clone https://github.com/ChandraPMDM/weekly-project-management-intelligence.git
```

2. Import

```
workflow/Weekly_PM_Intelligence_Template.json
```

into n8n.

3. Configure:

- OpenAI API
- Gmail OAuth
- Schedule Trigger

4. Activate the workflow.

---

## 📂 Repository Structure

```
.
├── assets/
├── docs/
├── screenshots/
├── workflow/
│   └── Weekly_PM_Intelligence_Template.json
├── README.md
├── LICENSE
└── CHANGELOG.md
```

---

## 🛠 Technologies Used

- n8n
- OpenAI GPT-4.1
- JavaScript ES6
- RSS
- Gmail API
- HTML

---

## 📅 Roadmap

- LinkedIn Post Generator
- PDF Newsletter Export
- Teams Integration
- Slack Notifications
- Microsoft Outlook Support
- Power BI Dashboard
- Multi-language Support

---

## 🤝 Contributing

Contributions are welcome.

Feel free to submit Issues, Forks, or Pull Requests.

---

## 📜 License

This project is licensed under the MIT License.

See LICENSE for details.
