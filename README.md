# AI-Powered User Feedback Loop (n8n + LLM)

## Overview
This project automates the intake and analysis of user research data. It bridges the gap between raw customer feedback and actionable product insights.

## The Logic
* **Trigger:** Google Sheets (via Google Forms).
* **Processing:** AI Agent (Gemini/GPT-4o) performs sentiment analysis and categorizes feedback into Bug, Feature, or UX improvement.
* **Output:** Generates an engineering "Action Item" and pushes it to Slack/Google Sheets.

## Why I Built This
To solve the problem of manual feedback triaging. By using a 'First Principles' approach, I automated the 'messy' part of user research so the product team can focus on scaling solutions rather than reading spreadsheets.

## Tools Used
* n8n (Workflow Automation)
* OpenAI API (LLM Logic)
* Google Workspace API
