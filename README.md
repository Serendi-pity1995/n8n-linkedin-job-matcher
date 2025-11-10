# n8n-linkedin-job-matcher
Automated LinkedIn job-matching workflow using n8n + DeepSeek

# 🤖 LinkedIn Job Matcher (n8n Workflow)

This is an automated **LinkedIn job-matching workflow** built in [n8n](https://n8n.io).

It:
- Fetches your latest LinkedIn job listings (via HTML extraction)
- Parses your resume (PDF → text)
- Uses DeepSeek AI to score job matches (0–100)
- Updates a Google Sheet with scores
- Sends a daily summary email 📧

---

## 🧠 Components
- Google Drive (to download your resume)
- Google Sheets (for job filters and results). You can use this [template spreadsheet](https://docs.google.com/spreadsheets/d/10V_2mwCetqVRULSMRfxnp5B2neqIeVMPJC-CeBXWms4/edit?usp=sharing) to get started.
- DeepSeek Chat Model (for AI scoring)
- Gmail (for daily summary)
- HTML extractors (for LinkedIn scraping)

---

## 🚀 How to Use
1. Import `JobMatcherWorkflow.json` into your own n8n instance
2. Replace:
   - Google Drive file IDs with your own
   - Google Sheet links
   - Gmail recipient address
   - DeepSeek credentials
3. Execute Workflow

---


