# n8n Automation Workflows

A collection of production-grade automation workflows built on self-hosted n8n. Each workflow is designed to eliminate repetitive manual tasks by combining web scraping, AI model routing, and smart data pipelines.

These workflows were built and tested in real operational environments.

---

## Workflows

### 🔍 [Job Hunter](./job-hunter/)
An end-to-end AI-powered job hunting pipeline that scrapes job listings, evaluates each one against a CV using an AI agent, scores matches from 1 to 10, and logs the best opportunities to a Google Sheets tracker automatically.

**Stack:** n8n · OpenRouter · Google Drive · Google Sheets · JavaScript

---

### 🦷 [Dental Appointment Booking](./dental-appointment-booking/)
An automated appointment booking system built for a dental hospital. Handles inbound appointment requests end-to-end — captures caller details, checks availability, books the slot, and sends confirmations. Runs 24/7, eliminating missed calls outside business hours and saving 40+ hours of receptionist time per week.

**Stack:** n8n · Twilio · Google Calendar · JavaScript

*Workflow file coming soon*

---

### 📞 [Call Quality Reviewer](./call-quality-reviewer/)
An AI-powered call quality review pipeline built for a financial institution. Automatically processes 100% of call center calls — transcribing, scoring agent performance, flagging customer concerns, and surfacing compliance issues. Replaced 50+ hours of manual QA analyst work per week and gave leadership visibility across the entire call volume for the first time.

**Stack:** n8n · OpenRouter · Whisper · Google Sheets · JavaScript

*Workflow file coming soon*

---

## About

Built by **Jeremiah Mutinda** — AI Operations Specialist and Virtual Assistant based in Nairobi, Kenya.

All workflows run on a self-hosted local n8n instance. Credentials are never included in exported workflow files.

- 🌍 [LinkedIn](https://linkedin.com/in/mambomutinda)
- 🐦 [@jdanmambo](https://twitter.com/jdanmambo)
