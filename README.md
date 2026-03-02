![Workflow Diagram](workflow-diagram.png)
# Social Media Automation Pipeline

## What It Does
An end-to-end automation workflow built with n8n that monitors a Google Sheet 
for new article links, summarizes them using OpenAI GPT, and automatically 
publishes tailored posts to LinkedIn and X (Twitter).

## Tools & Technologies
- n8n (workflow automation)
- OpenAI GPT API
- Google Sheets API
- LinkedIn API
- Twitter/X API

## How It Works
1. Google Sheets Trigger detects a new article link
2. GPT summarises the article into key insights
3. A LinkedIn-optimised post is generated and published
4. A concise X/Twitter post is generated and published simultaneously

## Business Impact
Reduces manual content creation time and ensures consistent, 
platform-specific messaging across professional social channels.
