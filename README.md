# AI Resume Scanning

AI-powered resume screening workflow built with n8n.
This automation scans uploaded CVs, detects programming languages using Google Gemini AI, shortlists candidates automatically, and sends notifications via Telegram and Email.

## Features

* Automated CV processing every minute
* Resume download from Google Drive
* AI-based programming language detection
* Candidate shortlisting logic
* Google Sheets integration
* Telegram notifications
* Automated email responses
* Prevents duplicate processing

## Workflow

1. Fetch candidate data from Google Sheets
2. Check if the CV is already processed
3. Download resume from Google Drive
4. Analyze resume using Gemini AI
5. Count unique programming languages
6. Update shortlist status in Google Sheets
7. Send Telegram alert and confirmation email

## Tech Stack

* n8n
* Google Gemini AI
* Google Sheets API
* Google Drive API
* Telegram Bot API
* SMTP Email

## Shortlisting Criteria

Candidates with more than **2 programming languages** detected in their resume are automatically shortlisted.

## Setup

1. Import the workflow JSON into n8n
2. Configure all API credentials
3. Connect:

   * Google Sheets
   * Google Drive
   * Gemini API
   * Telegram Bot
   * SMTP Email
4. Activate the workflow

## File

* `AI Resume Scanning.json` → Main n8n workflow file

## Author

Developed by Muhammad Hassaan Irshad
