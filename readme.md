# VitalGPT-Tasks
Your Health, Watched by Intelligent AI Agents.

## Vision
An AI-powered healthcare ecosystem that prevents health risks, manages medications, analyses medical reports and supports smarter health decisions through nine specialised agents.

## Problem
Fragmented health data, missed medications, undetected early risks, hard-to-read reports, limited preventive care.

## Solution
Nine agents: Risk Detection, Medication, Health Records, Nutrition, Fitness, Emergency, Appointment, Mind Wellness, Report Analysis.

## Files
index.html (demo deck and screens), requirements.md, readme.md, tasks.md, VitalGPT-Tasks_Pitch_Deck.pdf

## Author
Gundluru Rajasekhar - https://github.com/Gundlururajasekhar

## Run it
1. Open `index.html` (or deploy to GitHub Pages / Vercel).
2. Create an account, then Settings: paste a Gemini API key (aistudio.google.com).
3. Optional: paste a Firebase web config for Firebase Auth and Firestore history.

## Implemented
- 9-agent orchestrator: Gemini JSON router with keyword fallback, per-agent system prompts
- Chat with voice input and spoken replies (browser speech APIs)
- Medical report upload (image, PDF, text) analysed by Gemini
- Vitals log with transparent rule-based risk score plus Gemini explanation
- Medicine reminders with adherence tracking, emergency screen with location sharing
- Dashboard analytics: risk, adherence, heart-rate trend, agent calls and latency
- Auth and history: local accounts (hashed) or Firebase Auth and Firestore

## Not yet
- Gemini Live (WebSocket streaming audio); voice currently uses browser speech APIs plus Gemini text
- Gemma on-device mode; wearable integration
