# Privacy Policy for Linways Redmine Companion

**Effective Date:** March 9, 2026

## Introduction

This privacy policy explains how the Linways Redmine Companion ("we," "our," or "the extension") handles your data. We are committed to protecting your privacy and ensuring transparency about our data practices.

---

## What Data We Collect & Transmit

### 1. Local Device Storage
The extension stores specific configuration and preference data locally in your browser to function correctly:
- Your Redmine Server URL and API Key
- Daily time tracking sessions (including timestamps and issue numbers)
- Local UI preferences

### 2. Website Content (Context Detection)
When you navigate to a Redmine issue page, the extension reads the URL and basic issue elements (like the Issue ID, title, and status) to automate your time tracking and provide relevant context to the AI assistant. This data is only read when the extension is active on a recognized Redmine domain.

### 3. External Data Transmission
**The extension transmits select data off your device to the following three locations to provide its core functionality:**

**A. Linways Redmine (Primary)**
Your API Key, time log entries, and status updates are sent securely to your configured Redmine instance via API calls to synchronize your workflow.

**B. Active Sync Backend (Supabase)**
To provide features such as historical time summaries and cross-device timeline tracking, we sync certain workflow metrics to our secure backend database hosted on Supabase.
**Data Synced:** Your Redmine User ID, project IDs, issue IDs, tracked time, and status changes.
**Data NOT Synced:** Your Redmine API key and passwords. They never leave your device except to authenticate directly with your Redmine instance.

**C. AI Assistant Providers (GitHub Copilot / OpenAI)**
To power the AI-driven workflow assistance features, you can authorize third-party LLMs via the extension.
**Data Transmitted:** When you actively use the AI chat, the prompts you write, alongside context from the active Redmine issue (e.g., issue title, status, description, and issue ID), are transmitted to your authenticated AI provider (such as GitHub Copilot or OpenAI).
**Important:** We do not track your general browsing history. Only interactions explicitly made within the AI chat interface are processed.

---

## How We Use Your Data

We use the collected information solely for the extension's stated single purpose: **Managing Redmine issue status updates, automatically tracking time spent, and leveraging AI assistance to streamline your workflow.**

We do **not**:
- Sell, rent, or trade your data to third parties.
- Use your data for advertising or marketing.
- Use your data to determine creditworthiness or for lending purposes.
- Allow third parties to access the data except for the approved use cases mentioned above (Supabase infrastructure and AI processing).

---

## User Control & Data Deletion

### Authentication Revocation
You can revoke the extension's access at any time by:
- Deleting your Redmine API key from the extension settings.
- Signing out of the GitHub Copilot device flow within the chat interface.

### Data Removal
Removing the extension from your browser will instantly delete all locally stored data, API keys, and cached issue information.

---

## Compliance & Contact

This policy is designed to comply with the Google Chrome Web Store Developer Program Policies, particularly regarding the handling of personal and sensitive user data.

If you have questions about this privacy policy or data handling, please contact us:
- **Developer:** Sibin C Baby
- **Email:** sibincbaby219@gmail.com
