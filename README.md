AdmitCrew — Agentic Admissions Team

AdmitCrew is an AI-powered admissions assistant built with n8n and Google Sheets for Nowshera Study Abroad Consultants.

What It Does
Collects and manages student information.
Saves student leads in Google Sheets.
Answers university and program questions using the approved university list.
Checks student document status.
Identifies document problems such as expired documents.
Creates staff escalations when the AI cannot answer.
Generates follow-up reminders for quiet students.
Requires staff approval before staff-controlled messages are sent.
Logs student conversations and agent responses.
Prevents the AI from making unsupported admission claims.
Technology
n8n — Workflow orchestration and AI agents
Google Sheets — Data storage
OpenAI — AI model
GitHub — Workflow version control
Data Sheets

The workflow uses Google Sheets for:

Universities
Leads
Documents
Staff Approvals
Chat Logs
Messages
Workflow
Student
   ↓
n8n AI Agent
   ↓
Google Sheets
   ├── Leads
   ├── Universities
   ├── Documents
   ├── Staff Approvals
   └── Chat Logs
   ↓
Staff Review
   ↓
Approved Message
Important Rules

The AI agent:

Uses only information available in the approved university list.
Does not invent fees, deadlines, requirements, or programs.
Does not promise or confirm admission.
Does not claim an application was submitted unless an actual workflow performs that action.
Does not invent upload links, file-size limits, or other unsupported instructions.
Requires staff approval for staff-controlled outbound messages.
Project Structure
Admin-Crew-1/
├── README.md
└── AdmitCrew-n8n-workflow.json
Status

Project: AdmitCrew — Agentic Admissions Team
Client: Nowshera Study Abroad Consultants
Platform: n8n + Google Sheets
Repository: Private/Public depending on repository settings

This repository contains the n8n workflow configuration for the AdmitCrew admissions automation system.
