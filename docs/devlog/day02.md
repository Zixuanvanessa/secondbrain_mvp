# Day 02 – Minimal Backend + LLM Integration

**Goal:**  
Introduce a minimal backend layer and connect the system to a Large Language Model (LLM) API.

---

## What I Built

### 1. Minimal Node.js Backend
- Set up a lightweight Node.js server using Express
- Introduced a `/reflect` POST endpoint to handle user input
- Established a clear frontend → backend boundary

**Rationale:**  
Separating the backend allows the system to evolve beyond a static interface and enables AI-powered reflection.

---

### 2. LLM API Integration
- Connected the backend to an LLM API (OpenAI / DeepSeek interchangeable)
- The backend sends user speech text to the LLM
- Receives structured reflective responses (e.g. summary, assumptions, questions)

**Rationale:**  
This transforms the interface from a passive transcription tool into an active thinking partner.

---

### 3. Environment Configuration & Security
- Added `.env` support for storing API keys securely
- Ensured API keys are not exposed to the frontend or committed to GitHub

---

### 4. Local End-to-End Flow Verified
- Frontend runs on `localhost:3000`
- Backend API runs on `localhost:3001`
- Verified full request/response loop:
  - browser → backend → LLM → backend → browser

---

## Technical Notes
- Express for backend routing
- dotenv for environment variable management
- CORS enabled for local development
- Node.js runtime

---

## Outcome
By the end of Day 02, the project evolved from a standalone frontend prototype into a full-stack MVP with:

- A minimal backend layer
- Secure AI integration
- A working end-to-end reflective loop

This marked the transition from interface experimentation to system architecture.
