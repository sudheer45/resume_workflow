This project contains an n8n workflow that automates the job-search process. It retrieves recent LinkedIn job postings, extracts job details, analyzes each job with AI, compares it with your resume, and stores the results in Google Sheets and Google Docs.

Features

Scrapes LinkedIn for new job postings

Filters jobs based on keywords, location, and experience level

Uses AI to evaluate job descriptions and match them to your resume

Generates a match score, suggested improvements, cover letter, and updated resume

Saves results into Google Sheets and Google Docs

Sends an email notification after completion

Requirements

n8n (cloud or self-hosted)

Google Drive, Docs, Sheets, and Gmail API credentials

Gemini API key

Resume uploaded to Google Drive

Google Sheet with search filters

Basic Setup

Upload your resume PDF to Google Drive and copy its shareable link

Set up a Google Sheet with filter fields and a result sheet

Add Google API credentials and your Gemini key to n8n

Import the workflow JSON file

Update nodes with your file IDs, links, and credentials

Run manually or enable the schedule trigger

Purpose

This workflow saves time by automating job discovery, evaluation, and application document preparation.
