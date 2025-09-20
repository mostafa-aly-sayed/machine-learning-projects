# 🕵️‍♂️ NeoSilk: AI-Enhanced Dark Web Threat Intelligence Framework

## 🕸️ Introduction
The dark web is a hidden segment of the internet accessible only through specialized software like Tor. It hosts thousands of anonymous marketplaces and forums that facilitate a wide range of illicit activities, including:

- Drug trafficking

- Stolen data trade

- Hacking services

- Counterfeit goods

- Cybercrime-as-a-service offerings

Unlike the surface web, the dark web is highly unstructured, constantly changing, and protected by layers of anonymity and anti-crawling defenses such as CAPTCHAs and session controls. These characteristics make it incredibly challenging for cybersecurity professionals and researchers to track threats or extract intelligence in a reliable and scalable manner.

NeoSilk is an **AI-powered framework** designed to collect, analyze, and visualize darknet marketplace data for cybersecurity threat intelligence. It combines automated web scraping, advanced NLP modeling, and interactive dashboards to uncover patterns and monitor illegal activity across `.onion` sites on the dark web.

---
## 🎯 Project Aim

NeoSilk aims to provide a modular and intelligent framework for dark web threat intelligence. By combining advanced scraping, natural language processing (NLP), and interactive dashboards, the system enables cybersecurity analysts to:

- Detect and monitor illicit activities (e.g., drugs, fraud, digital contraband)

- Extract meaningful insights from hidden marketplaces

- Transform unstructured darknet content into actionable intelligence

- This project bridges the gap between the dark web’s anonymity and the visibility needed for proactive cyber defense.

---

## 🚀 What NeoSilk Does

NeoSilk delivers a full-stack AI pipeline that enables:

🔍 **Secure Scraping of Darknet Marketplaces**

Using Python scrapers over the Tor network, with support for manual CAPTCHA-solving. Scraped marketplaces include:

- Hidden Market (no CAPTCHA)

- MGM Grand (CAPTCHA-protected; dataset of 5K CAPTCHA images available)

🧠 **NLP-Based Threat Classification**

- Classifies products into high-risk domains: Drugs, Digital, Tutorials

- Performs sentiment analysis on product reviews

- Explores RAG-based QA for content understanding

- Powered by models like BERT, DarkBERT, RoBERTa, and DistilGPT-2

- Integrated with Explainable AI (XAI) using SHAP

📊 **Visual Threat Intelligence Dashboards**

- Interactive dashboards using Power BI 

- Showcasing KPIs, product category trends, vendor performance, shipping locations, and conversion funnels

- Tailored insights for cybersecurity professionals

---

## 📦 Datasets

| Marketplace   | Description                     | Data Source | Notes                         |
|---------------|----------------------------------|-------------|-------------------------------|
| Hidden Market | No CAPTCHA, full scraping       | `.onion`    | Drugs, Digital, Tutorials     |
| MGM Grand     | CAPTCHA-protected, solved manually | `.onion` | Most are Drugs |


A separate dataset of 5,000 Alphanumeric CAPTCHAs — collected directly during scraping from the MGM Grand darknet marketplace — is also [here](https://kaggle.com/datasets/a41e9c53e1189b91c7afb507f2335b6c148d46822729fe8f0cebbde39070958e) to support training of CAPTCHA-solving models.

---


## 🔐 Ethical Use

This project was developed **for educational and cybersecurity research purposes**. All data scraping was conducted with careful supervision by our academic advisors and follows ethical guidelines. This tool is not intended for malicious use.

---

## 📚 Team

Developed by:

- Mostafa Aly Hashem
- Nour El-Dien Mostafa Mohammed
- Mohammed Hassanien Sayed
- Adham Tarek Abdelaziz
- Abdelhamid Mahmoud Ahmed

**Cairo University Faculty of Computers and Artificial Intelligence - AI Departement-Graduation Project 2025**

---

## 🔗 Project Links

- 📊 **Kaggle Dataset (CAPTCHAs)**: [[Dataset-5K](https://kaggle.com/datasets/a41e9c53e1189b91c7afb507f2335b6c148d46822729fe8f0cebbde39070958e)]

- 👨‍💻 **Full Repository**: [NeoSilk](https://github.com/mostafa-aly-sayed/NeoSilk.git)
---

