<!-- <p align="center"> <img src="./assets/banner-tech.png" alt="SwiftReply-AI Banner" width="100%" /> </p> -->

# SwiftReply-AI

AI WhatsApp Auto-Responder — FastAPI backend, LLM-powered AI, WhatsApp Cloud API integration, and a modern Next.js dashboard.

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)]()
[![Status: MVP](https://img.shields.io/badge/status-MVP-yellow.svg)]()
[![Built with FastAPI](https://img.shields.io/badge/backend-FastAPI-blue.svg)]()
[![LLM](https://img.shields.io/badge/AI-LLM-orange.svg)]()

## Overview
SwiftReply-AI helps small businesses automate WhatsApp conversations using Generative AI. It supports automated replies, catalog sharing, lead capture (Google Sheets / DB), and a lightweight admin dashboard.

---

## Features
- WhatsApp webhook receiver + sender (text, images, documents)
- LLM-driven intent classification and response generation (OpenAI / Claude)
- Conversation memory & session management
- Lead capture + Google Sheets export
- Admin dashboard (Next.js) for leads, settings, and analytics
- Serverless-ready (AWS Lambda + API Gateway)

---

## Quick Start (Local)

### Backend (FastAPI)
```bash
# Clone
git clone https://github.com/<your-username>/swiftreply-ai.git
cd swiftreply-ai/backend

# Create venv
python -m venv .venv
source .venv/bin/activate

# Install
pip install -r requirements.txt

# Run
uvicorn app.main:app --reload --port 8000
