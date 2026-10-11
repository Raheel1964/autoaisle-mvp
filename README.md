# AutoAisle | Permissioned Marketplace Infrastructure for AI Agents

**Live Demo:** [https://shoppingagent.online](https://shoppingagent.online)  
**REST API Endpoint:** `https://jlkokewquvyeqsoajnnr.supabase.co/rest/v1/live_agent_catalog`

---

## 📌 Problem Statement
E-commerce marketplaces like Amazon charge independent sellers up to 25%+ in ad taxes, referral fees, and sponsored placement costs. Simultaneously, traditional e-commerce platforms actively block third-party AI shopping agents (ChatGPT, Gemini, Claude) from scraping real-time inventory.

## 🚀 The Solution: AutoAisle
**AutoAisle** provides independent merchants with a direct, zero-ad channel to list their inventory for autonomous AI shopping agents. Instead of paying advertising taxes, sellers pay a flat **8% success fee** only when an AI agent completes a validated transaction.

---

## 🛠️ Key Platform Features

1. **Merchant Onboarding Portal:**
   - Instant store registration mapping merchant profiles directly to PostgreSQL database records.
   - Simplified inventory listing form for standard product SKUs, landed pricing, shipping rates, and guaranteed delivery dates.

2. **Real-Time REST API Feed:**
   - Serverless database backend powered by Supabase.
   - Publicly accessible, low-latency REST endpoints exposing live product inventory directly to AI agents.

3. **Dynamic Agent Briefing Engine:**
   - Auto-generates structured context prompts tailored for LLM reasoning engines (ChatGPT, Claude, Gemini).
   - Allows agents to compare landed pricing, evaluate delivery promises, filter out late-shipping merchants, and execute purchases.

---

## 🏗️ Technical Architecture

- **Frontend:** Single-page web application built with HTML5, CSS3, and Vanilla JavaScript (`index.html`).
- **Backend / Database:** PostgreSQL with REST API integration via Supabase.
- **Hosting & Deployment:** Serverless edge distribution via Netlify.
- **Custom Domain:** Configured with SSL termination via GoDaddy DNS and Netlify edge networking.

---

## 📜 Intellectual Property & Ownership
This repository contains the official source code, database interface scripts, and frontend assets for **AutoAisle**. 

© 2026 AutoAisle. All rights reserved.
