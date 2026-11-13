# AI-Powered-Email-Campaign-Generator
An n8n-powered AI automation that generates personalized email campaigns using Google Gemini and automatically delivers them through Gmail based on user-submitted form data. An AI-powered email campaign automation built with n8n, Google Gemini, Google Forms, Google Sheets, and Gmail.

This workflow collects user information through a Google Form, processes the submitted data, generates personalized email campaign content using an AI Agent powered by Google Gemini, and automatically delivers the generated campaign through Gmail.

## Project Overview

Creating personalized email campaigns manually can be time-consuming. This automation streamlines the process by combining workflow automation with generative AI.

Users submit their information through a form, and the system uses their inputs to generate customized email campaign content without requiring manual content creation.

## Workflow Architecture

1. Google Forms: Collects user information and campaign requirements.
2. Google Sheets: Stores form responses and serves as the backend data source.
3. Campaign Data Processing: Retrieves and organizes the submitted information.
4. Data Extraction: Extracts relevant information for AI processing.
5. AI Prompt Generation: Dynamically builds an AI prompt using the submitted details.
6. AI Agent: Uses Google Gemini to generate personalized email campaign content.
7. Data Cleaning: Processes and cleans the AI-generated response.
8. Gmail Integration: Automatically sends the generated email to the user.

## Technologies Used

- n8n: Workflow orchestration and automation.
- Google Gemini: AI-powered content generation.
- Google Forms: User input collection.
- Google Sheets: Backend data storage.
- Gmail: Automated email delivery.

## Workflow Highlights

- Automated form submission processing.
- Dynamic AI prompt generation.
- Personalized email campaign creation.
- Google Gemini integration through an AI Agent node.
- Automated email delivery using Gmail.
- Reduced manual effort in campaign creation.

## Workflow Structure
<img width="968" height="302" alt="Screenshot 2026-11-13 162322" src="https://github.com/user-attachments/assets/b0145e13-e5c0-40b9-a3b7-e4ad01f64eca" />

Google Form
     |
     
Google Sheets
     |
     
Campaign Data Processing
     |
     
Data Extraction
     |
     
Dynamic AI Prompt Generation
     |
     
AI Agent (Google Gemini)
     |
     
Data Cleaning
     |
     
Gmail
     |
     
Personalized Email Delivery

## Setup and Configuration

1. Set up an n8n instance.
2. Connect Google Forms to Google Sheets.
3. Configure Google Sheets credentials in n8n.
4. Connect Google Gemini credentials.
5. Configure the AI Agent and prompt-generation logic.
6. Connect Gmail credentials.
7. Configure the email recipient and message content.
8. Activate the workflow and test it using a form submission.

## Requirements

- An n8n instance (self-hosted or cloud).
- Google account.
- Google Gemini API access.
- Google Sheets and Forms access.
- Gmail account with the required permissions.

## Security Notes

- Never upload API keys, OAuth credentials, access tokens, or personal user data.
- Use n8n credentials to securely manage integrations.
- Remove sensitive information before sharing workflow exports publicly.

## Project Purpose

This project demonstrates how AI and workflow automation can work together to simplify repetitive marketing tasks, generate personalized content, and automate communication.

Built with n8n + Google Gemini.
