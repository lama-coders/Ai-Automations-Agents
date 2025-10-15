# Ai-Automations-Agents
In this respository there is several workflows about different tasks.

1. Form Submission Automation

Purpose: Automates the collection and organization of data from online form submissions into Google Sheets or a CRM.
Stack: n8n, Google Forms, Google Sheets API, Webhooks.
Highlights:

Automatically records new submissions into structured sheets.

Sends notification emails to admins.

Includes error handling and timestamp logging.
![Workflow Screenshot](./screenshots/20251016_001505.jpg


2. Workshop Entries Summarizer

Purpose: Summarizes workshop registration or feedback data using an AI model to generate insights.
Stack: n8n, Google Sheets, Email integration.
Highlights:

Fetches workshop data from Sheets.

The custom code function count the entries and enter it in gmail automatically on basis of thier workshop.

Automatically sends summaries to organizers.
📸 Screenshot: /screenshots/20251016_001132.jpg

Purpose: An AI-powered workflow that analyzes structured data and returns insights, charts, or summaries.
Stack: n8n, OpenAI API, Python (for data preprocessing), CSV import/export.
Highlights:

Parses uploaded datasets and performs quick analytics.

Uses prompt engineering to produce AI-generated insights and summaries.

Outputs results to Sheets or email.
📸 Screenshot: /screenshots/20251016_002140.jpg

4. Invoice Tracker

Purpose: Automates invoice tracking by collecting payment records and generating status reports.
Stack: n8n, Google Sheets, Email, PDF Parser / OCR API.
Highlights:

Extracts data from uploaded invoices or forms.

Updates Google Sheet with payment status and totals.

Sends automatic reminders for pending invoices.
📸 Screenshot: /screenshots/20251016_002541.jpg

