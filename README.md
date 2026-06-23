# AI Customer Support Ticket Triage System

## Problem

Companies receive customer emails every day.

Manually reading emails, categorizing issues, forwarding them to the right team and sending acknowledgements consumes time and introduces delays.

## Solution

An AI-powered workflow that automatically classifies customer queries, assigns priority, stores tickets and sends acknowledgement emails.

## Workflow Architecture

Gmail Trigger
↓
Set Node
↓
OpenAI Node
↓
IF Node
↓
Google Sheets
↓
Gmail

## Categories

* Complaint
* Support Request
* Refund Request
* Sales Inquiry

## Priority Levels

* High
* Medium
* Low

## Tools Used

* n8n
* OpenAI
* Gmail
* Google Sheets

## Business Value

* Reduces manual work
* Faster response times
* Better customer experience
* Automatic ticket categorization
* Improved operational efficiency

## Concepts Learned

* Trigger
* Input / Output
* Data Flow
* JSON
* APIs
* HTTP Requests
* Webhooks
* Set Node
* OpenAI Node
* IF Conditions

## Future Improvements

* Slack notifications
* CRM integration
* Dashboard and analytics
* Ticket escalation system

## Status

Project Architecture Completed

Implementation in Progress
