# MediPulse AI — Clinical Vision, Triage & SBAR Intelligence Platform

![Status](https://img.shields.io/badge/Platform-Live_Web_App-10b981?style=for-the-badge)
![AI Engine](https://img.shields.io/badge/AI-Google_Gemini_Vision-38bdf8?style=for-the-badge)
![Clinical Standard](https://img.shields.io/badge/Report_Format-PDF_SBAR-8b5cf6?style=for-the-badge)
![Market](https://img.shields.io/badge/Built_For-Bangladesh_Clinics_%26_Telehealth-06b6d4?style=for-the-badge)

**MediPulse AI** is an AI-first clinical & patient health assistant platform built for diagnostic centers, outpatient clinics, and telehealth partners. It bridges the gap between complex medical reports, handwritten prescriptions, and everyday patient understanding—turning raw lab sheets and symptoms into hospital-standard **PDF SBAR Clinical Reports** in seconds.

> **Investor & Partner Pitch Deck:** Download [`MediPulse-AI-Pitch-Deck.pptx`](./MediPulse-AI-Pitch-Deck.pptx) directly from this repository for our 5-slide clinical & telehealth partnership overview.

---

## Core Clinical AI Modules

1. **Multimodal Lab Report, Scan & Prescription Vision AI**
   * Patients upload photos of blood tests, diagnostic reports, or handwritten prescriptions.
   * Powered by **Google Gemini Vision**, the platform extracts biomarkers, highlights out-of-range readings, and translates medical terminology into clear patient guidance.

2. **AI Symptom Triage & Specialist Routing**
   * Evaluates patient-reported symptoms and visible condition photos to identify red-flag emergency signs early.
   * Routes patients directly to the exact specialist specialty (e.g., Cardiologist, Endocrinologist, Dermatologist, General Physician), eliminating wasted consultation fees and wrong-department queues.

3. **Medication & Drug Interaction Checker**
   * Analyzes medicine strips or typed medication lists to clarify dosage timing, food rules, side effects, and potentially dangerous drug-to-drug interactions.

4. **One-Click Download / Print PDF SBAR Clinical Report**
   * Automatically structures every AI consultation into a clean, print-ready hospital **SBAR** sheet (**Situation, Background, Assessment, Recommendation**) that patients can download as a PDF and hand directly to their doctor.

5. **Daily / Weekly Auto AI Voice Follow-Up & Real-Time History Maker**
   * Builds a longitudinal cloud health record for every patient alongside automated daily/weekly chronic-care check-in schedules and **AI Voice Follow-Up / Tele-Call** readiness.

6. **Centralized Admin Gemini API Vault**
   * Designed for enterprise clinic and telehealth governance: a single platform administrator (`orinmashruqe@gmail.com`) centrally manages the master Google Gemini API key and model selection (`gemini-2.5-flash` / `gemini-2.5-pro`)—removing USD card or API key barriers for patients.

---

## Commercial & Market Value (Bangladesh Healthcare Ecosystem)

* **Prevents Delayed Emergency Care:** Flags critical symptoms early and guides patients straight to the right specialist on their first visit.
* **Complete Hybrid Care Funnel:** Clinics and telehealth operators offer free AI lab report explanations to acquire patients at the exact moment they receive test results, converting high-need cases into paid specialist consultations.
* **Saves 5–7 Minutes Per Doctor Visit:** Pre-structured SBAR PDF summaries give doctors immediate clinical context before the consultation begins.
* **Hospital-Grade SaaS Polish Out of the Box:** Responsive frosted-glass clinical UI (`index.html`), zero mobile app install friction, and live cloud persistence ready for 30-day diagnostic center pilots.

---

## Repository Structure

```text
├── index.html                        # Complete MediPulse AI live web application
├── MediPulse-AI-Pitch-Deck.pptx      # 5-slide Investor & Clinic Partnership Pitch Deck
└── README.md                         # Product overview, clinical modules & market value
```

---

## Quick Deployment

1. **Database Setup:** Run the MediPulse SQL schema (`medipulse_settings`, `medipulse_profiles`, `medipulse_records`, `medipulse_followups`, `medipulse_chat`) in your Supabase SQL Editor.
2. **Hosting:** Deploy `index.html` via GitHub + Vercel (or any static web host).
3. **AI Activation:** Sign in with the designated platform administrator account (`orinmashruqe@gmail.com`), open **Admin Gemini Vault**, and save your Google Gemini API key.

---

*Disclaimer: MediPulse AI provides informational clinical decision support and structured SBAR summaries. It does not replace professional medical diagnosis or emergency care.*
