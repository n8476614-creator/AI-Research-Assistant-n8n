# 🤖 AI Research Assistant using n8n

## 📌 Project Overview

The **AI Research Assistant** is an AI-powered workflow automation project developed using **n8n**, **OpenAI**, **Google Sheets**, **Google Docs**, and **Gmail**. It automates the complete research management process, from registering research topics and collecting research papers to generating AI-powered summaries, managing references, and sending weekly research digest emails.

The project reduces manual effort, saves time, and helps researchers stay updated with the latest research publications through intelligent automation.

# 📖 Problem Statement

Researchers and students spend significant time searching for research papers, reading lengthy documents, organizing references, and tracking new publications.

Common challenges include:

- Manual research paper collection
- Reading long research papers
- Organizing references
- Missing newly published papers
- Repetitive weekly reporting
- Lack of automation in research management

# 🎯 Objectives

The objectives of this project are:

- Automate research topic registration
- Search and collect research papers automatically
- Generate AI-powered summaries
- Extract important keywords
- Store research references in Google Docs
- Send automated weekly research digest emails
- Reduce manual work using workflow automation


# 🚀 Features

- ✅ Research Topic Registration
- ✅ Automated Research Paper Search
- ✅ AI-powered Summarization
- ✅ Automatic Keyword Extraction
- ✅ Google Docs Repository Creation
- ✅ Weekly Research Digest Email
- ✅ Scheduled Workflow Execution
- ✅ Google Sheets Database Integration
- ✅ AI Automation using OpenAI


# 🏗️ System Architecture

```text
User
   │
   ▼
Workflow 1
Research Topic Registration
   │
   ▼
Google Sheets Database
   │
   ▼
Workflow 2
Research Paper Search & Collection
   │
   ▼
Workflow 3
AI Summarization & Keyword Extraction
   │
   ▼
Workflow 4
Reference Management & Repository
   │
   ▼
Workflow 5
Weekly Research Digest & Notifications
   │
   ▼
Gmail
```

# 🔄 Workflow Description

## Workflow 1 – Research Topic Registration

Registers the research topic entered by the user and stores it in Google Sheets.

### Technologies Used
- n8n
- Google Sheets

---

## Workflow 2 – Research Paper Search & Collection

Searches for research papers related to the registered topic and stores research details inside Google Sheets.

### Technologies Used

- Google Sheets
- AI Search API
- n8n

---

## Workflow 3 – AI Summarization & Keyword Extraction

Uses OpenAI to generate concise research summaries and automatically extract keywords.

### Technologies Used

- OpenAI
- n8n

---

## Workflow 4 – Reference Management & Repository

Automatically creates a Google Document containing:

- Paper Title
- Authors
- Publication Year
- DOI
- Paper URL
- AI Summary
- Keywords

---

## Workflow 5 – Weekly Research Digest & Notifications

Generates a weekly digest from all research papers and emails the digest automatically using Gmail.

---

# 💻 Technologies Used

- n8n
- OpenAI GPT
- Google Sheets
- Google Docs
- Gmail
- JSON
- Workflow Automation

---

# 📂 Repository Contents

# 📂 Repository Contents

```text
AI-Research-Assistant-n8n
│
├── 01-Research Topic Registration.json
├── 02-Research Paper Search & Collection.json
├── 03-AI Summarization & Keyword Extraction.json
├── 04-Reference Management & Repository.json
├── 05-Weekly Research Digest & Notifications.json
├── README.md
├── Project_Report.pdf
├── Architecture_Diagram.png
├── Presentation.pptx
└── screenshots
    ├── workflow1.png
    ├── workflow2.png
    ├── workflow3.png
    ├── workflow4.png
    ├── workflow5.png
    ├── google-sheets.png
    ├── google-docs.png
    └── weekly-email.png
```



# ▶️ How to Run the Project

1. Import all workflow JSON files into n8n.
2. Connect Google Sheets, Google Docs, Gmail, and OpenAI credentials.
3. Configure the spreadsheet and Google Drive folder.
4. Execute the workflows in sequence.
5. Enable the Schedule Trigger for automated weekly execution.


# 📧 Expected Output

The project automatically:

- Registers research topics
- Collects research papers
- Generates AI summaries
- Extracts keywords
- Creates a Google Docs repository
- Sends a weekly research digest email


# ⭐ Advanced Features

- AI-powered decision making
- Conditional branching
- Scheduled workflows (Cron)
- Automated document creation
- Automated email notifications
- Centralized research repository


# 🔮 Future Enhancements

- Human approval workflow
- Webhook integration
- Research paper recommendation engine
- Dashboard for analytics
- Multi-user support
- Citation generation
- PDF report generation
- Semantic search


# 📚 Learning Outcomes

Through this project, I learned:

- Workflow automation using n8n
- AI integration with OpenAI
- Google Workspace automation
- Prompt engineering
- JSON workflow management
- AI-based document generation
- Email automation


# 👩‍💻 Author

**Nancy Choudhary**

AI & Workflow Automation Enthusiast
Built as part of an AI Automation & n8n Capstone Project.


# ⭐ If you found this project useful, consider giving it a star!
