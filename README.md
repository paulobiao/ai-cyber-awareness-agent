# Should I Worry? — An AI Cyber Awareness Assistant

## Problem
Cybersecurity incidents affect real people — not just companies.

Non-technical users, students, and small organizations are exposed to digital threats every day, but most security tools are built for experts. This creates a gap where **critical incidents are misunderstood, ignored, or escalated too late**, while harmless alerts can cause unnecessary panic.

## Solution
**Should I Worry?** is an AI-assisted cyber awareness & incident triage assistant that turns confusing security signals into **clear, understandable severity levels**.

It simulates real-world cyber events, automatically classifies them by severity, and visualizes them in a simple way so anyone can understand:
- when to act
- when to stay calm
- what type of incident they might be facing

## How It Works
1. **Cyber events are generated** (simulated incidents such as unauthorized access, outages, warnings).
2. **AI-style severity classification** labels events as:
   - Info
   - Warning
   - Critical
3. Events are sent to **Elasticsearch** as structured documents.
4. Results can be explored in **Discover**, and critical signals can be correlated into **Elastic Security Cases**.

## Why It Matters
Cyber awareness should be accessible. This project focuses on **clarity, education, and visibility** — empowering people who are usually left out of cybersecurity tools.

## Tech Stack
- Python
- Elastic Cloud / Elasticsearch
- Elastic Security (Cases)
- Kibana (Discover)

## Status
✅ Working prototype with real-time event generation and visualization.

## Demo
- Video: (add your Devpost/YouTube link here)
- Repo: (this repository)

## Run Locally
1. Create a virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux
   pip install -r requirements.txt
