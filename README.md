# AI-Lead-Calling-CRM-Automation
# AI Lead Calling & CRM Automation System

An AI-powered outbound lead qualification workflow built using n8n, OpenAI, Vapi AI, Zoho CRM, and Google Sheets.

This system automates the complete lead calling and qualification pipeline — from reading leads to AI-powered calling, transcript analysis, CRM updates, and follow-up automation.

---

## Features

- Reads leads dynamically from Google Sheets
- AI Voice Agent makes outbound calls
- Retrieves complete call transcripts
- Uses AI to analyze customer intent
- Automatically classifies leads as:
  - INTERESTED
  - NOT_INTERESTED
  - NO_RESPONSE
- Updates Zoho CRM automatically
- Updates lead status in Google Sheets
- Sends automated follow-up emails
- Handles multi-lead workflows dynamically

---

## Workflow Overview

text
Google Sheets
      ↓
AI Outbound Call
      ↓
Transcript Retrieval
      ↓
AI Intent Analysis
      ↓
IF Condition
   ↙        ↘
Interested   Not Interested
      ↓
Zoho CRM Update
      ↓
Google Sheet Update
      ↓
Email Automation
