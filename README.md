# AI Email Generation Assistant

## Overview

This project is an AI-powered Email Generation Assistant built using **n8n (cloud)** and **OpenAI**.

It generates professional emails based on three structured inputs:

- Intent (purpose of the email)
- Key Facts (important points to include)
- Tone (communication style)

---

## Prerequisites

Before starting, make sure you have:

1. An n8n cloud account  
👉 https://n8n.cloud  

2. An OpenAI account with API access  
👉 https://platform.openai.com  

---

## Step 1 — Set Up n8n (Cloud)

1. Go to: https://n8n.cloud  
2. Click **Get Started**  
3. Create your account  
4. Open your n8n dashboard  

---

## Step 2 — Get OpenAI API Key

1. Go to: https://platform.openai.com/api-keys  
2. Click **Create new secret key**  
3. Copy the API key (you will need it in the next step)

---

## Step 3 — Import Workflow

1. In n8n dashboard, click **New Workflow**  
2. Click **Import**  
3. Select **Paste JSON**  
4. Paste the contents of `email-generator.json` from this repository  
5. Click **Import**  
6. Save the workflow  

---

## Step 4 — Connect OpenAI

1. Click on the **OpenAI node** inside the workflow  
2. Click **Credentials → Create New**  
3. Paste your OpenAI API key  
4. Save the credentials  


