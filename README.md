# AI Lead Qualification & Sales Assessment Automation

An AI-powered business workflow built with **n8n and Google Gemini** that automatically analyzes incoming business leads and converts them into structured sales insights.

## Project Overview

This project automates the initial qualification of business leads.

Instead of manually reviewing every incoming inquiry, the workflow uses an AI Agent to analyze the lead and generate actionable sales information.

## Workflow Architecture

```text
Lead Form Submission
        ↓
      n8n
        ↓
    AI Agent
        ↓
 Google Gemini
        ↓
Structured Output Parser
        ↓
   Google Sheets
