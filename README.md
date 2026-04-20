
---

## README.md

# IT Support Assistant Agent

## Overview

The IT Support Assistant Agent is a structured IT troubleshooting system designed to help users identify, diagnose, and resolve common IT issues. It provides step-by-step guidance, classifies issues, and escalates unresolved cases to the appropriate IT support teams.

---

## Features

### 1. Guided Troubleshooting
- Step-by-step assistance
- One instruction at a time
- User confirmation required before continuing

### 2. Issue Classification
Automatically categorizes issues into:
- Network
- Hardware
- Software
- Account
- Access

Each issue is assigned:
- Priority (High / Medium)
- Responsible support team

### 3. Structured Ticketing
Generates:
- Ticket Summary
- Escalation Ticket (if needed)

### 4. SOP Integration
- Uses standardized troubleshooting procedures
- Simplifies SOP guidance for users

### 5. Escalation System
Routes unresolved issues to:
- Network Support
- Desktop Support
- Service Desk
- IT Security

---

## How to Use

### Step 1: Report Issue
Describe the problem clearly (e.g., “My internet is not working”).

### Step 2: Clarify Details
You may be asked:
- When did the issue start?
- What device are you using?
- Any error messages?

### Step 3: Follow Instructions
- Follow one step at a time
- Confirm after each step
- Example steps:
  - Restart device
  - Check connection
  - Retry login

### Step 4: Confirmation
The assistant will ask if the issue is resolved.

### Step 5: Escalation (if needed)
If unresolved, provide:
- Name
- Device type
- Issue description

---

## Architecture
### System Flow

<img width="1407" height="768" alt="Gemini_Generated_Image_ko6pmpko6pmpko6p" src="https://github.com/user-attachments/assets/05cae524-592c-4238-8945-3b1c19fa96cb" />


---

## Testing Results

### Network Issue
- Input: WiFi not working
- Result: Network Issue (High Priority)
- Outcome: Resolved / Escalated

### Login Issue
- Input: Cannot log in
- Result: Account Issue (High Priority)
- Outcome: Password reset / Escalation

### Performance Issue
- Input: Laptop slow
- Result: Software Issue (Medium Priority)
- Outcome: Optimization steps applied

### Access Issue
- Input: Cannot access system
- Result: Access Issue (High Priority)
- Outcome: Escalated to IT Security

---

## Purpose

This project standardizes IT support processes by combining:
- Structured troubleshooting
- Automated classification
- Consistent escalation handling
- SOP-based guidance

---
