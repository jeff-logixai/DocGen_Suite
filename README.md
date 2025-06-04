# DocGen Suite

**AI-Powered Clinical Documentation Tools**

DocGen is a Python-based suite of tools designed to streamline and improve clinical documentation workflows for healthcare professionals. Built by a practicing clinician with over a decade of experience, the suite combines NLP, custom UI, and automation to reduce friction in SOAP note generation and medical transcription tasks.


### 🧩 Modules Included


### 📄 **docgen/**

An AI-assisted tool that helps clinicians generate SOAP notes from free text or bullet-point summaries using GPT integration.

**Features:**
- Custom PySide6 GUI for clean clinical workflow
- Accepts flexible inputs (dictation summaries, bullet notes)
- Outputs SOAP-formatted notes with contextual logic
- Designed for real-world documentation, referrals, and insurance



### 📁 **vtt/**

Parses .vtt transcription files—such as those created via Whisper or other tools—and extracts clinically relevant content.

**Features:**
  - Identifies and highlights SOAP-relevant segments
  - Converts raw text into structured summaries
  - Flags unclear or fragmented phrases for manual review
  - Modular design for future integration with DocGen



### 🧪 **auditlab/ (concept phase)**

A planned documentation auditing tool that will analyze full EHR documents for quality, clarity, and reimbursement readiness.

**Planned Features:**
  - Graphs tracking patient-reported pain across visits
  - Subjective scoring system based on richness and clarity
  - Redundancy detection across SOAP sections
  - Summary quality alerts before submission to payers



### 💻 **Built With**

  - Python 3.x
  - PySide6 (custom GUI)
  - OpenAI API (GPT-4)
  - `whisper`, `pyaudio`, `mutagen` (for VTT + audio parsing)

### 📦 Getting Started

1. Clone the repo:

