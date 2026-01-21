# Secret Shopper-Automated UX Audit System


## 📋 Overview

This n8n workflow implements an AI-powered UX research system based on the mystery shopper methodology.

The system simulates multiple user personas, interacts with a website’s live support chat, and uses Large Language Models (LLMs) to identify UX issues and improvement opportunities.
The final UX audit is automatically generated and delivered to Telegram.

## ⚙️ Main Steps

### Trigger & Configuration
Defines the website URL, chat selectors, API keys, and experiment parameters.

### Persona Creation
Generates multiple user personas with different goals, motivations, and behaviors.

### LLM-based Question Generation
Uses an LLM to generate realistic, persona-specific questions for the support chat.

### Browser Automation (Real Interaction)
Simulates each persona asking questions in the live website chat using Browserless.

### Chat Log Extraction
Collects real responses from the support system.

### Individual UX Analysis (per Persona)
LLM analyzes each chat interaction to identify:

- UX friction points

- Missing or unclear information

- Concrete improvement recommendations

### Cross-Persona UX Synthesis
Aggregates individual analyses into a unified UX audit highlighting:

- Critical UX issues

 -Patterns across personas

- Quick wins for improvement

### Report Delivery
Sends the final UX audit report to a specified Telegram chat.



## 🧠 Key Concepts

Persona-based user simulation

LLM-driven qualitative UX analysis

Real interaction data (not synthetic)

Fully automated research pipeline


## 📬 Outputs

Automated UX audit reports delivered to Telegram

<img width="932" height="1148" alt="image" src="https://github.com/user-attachments/assets/afbc1b5b-e9e7-4285-ab0a-61520dcd7057" />

<img width="933" height="1211" alt="image" src="https://github.com/user-attachments/assets/82d61430-3d06-41ad-b023-44741643d1c4" />

<img width="1002" height="1005" alt="image" src="https://github.com/user-attachments/assets/5160b258-e123-443a-92e0-7b5c2f5a5bea" />

<img width="935" height="1205" alt="image" src="https://github.com/user-attachments/assets/f5501551-164b-4791-8b47-3a09cca004bd" />

<img width="905" height="1207" alt="image" src="https://github.com/user-attachments/assets/4125b8c8-58cc-49c9-9b1f-bddb78a4800d" />

<img width="1075" height="1102" alt="image" src="https://github.com/user-attachments/assets/d7504fd4-372c-4b45-ae4d-9e161d3de271" />

## 🛠️ Tech Stack

n8n

Google Gemini (LLMs)

LangChain Agents

Browserless

Telegram Bot API
