# vice-ai
code Markdown
downloadcontent_copy
expand_less
   # Vice AI - Project Vision & Technical Blueprint

**Tagline:** Engineered for Genuine Connection.

This repository contains the project vision, technical architecture, and development plan for Vice AI, submitted for the OpenAI x NxtWave Hackathon.

---

### 1. Core Problem

Current social platforms are engineered for addiction, not connection. This has led to a global rise in loneliness and a decline in deep, meaningful friendships.

### 2. Our Solution

Vice AI is a "personality-first" platform that uses a sophisticated AI to understand users on a deep level. We engineer connections based on true psychological compatibility, forcing substance over superficiality.

### 3. Proposed Tech Stack

*   **Frontend:** React.js (with Vite)
*   **Backend:** Python with FastAPI
*   **Database:** Supabase (for Auth, DB, and Storage)
*   **AI APIs:** OpenAI GPT-4 and Whisper API
*   **Deployment:** Vercel

### 4. User Flow & API Integration

1.  **Onboarding:** User engages in a "Diagnostic Conversation" with our AI.
    *   **Frontend** sends user's text/voice to our **Backend**.
    *   If voice, **Backend** calls **Whisper API** to transcribe.
    *   **Backend** sends the transcript to **GPT-4 API** to generate a "Personality Blueprint."
2.  **Matching:**
    *   The Blueprint is stored in **Supabase**.
    *   A backend script compares Blueprints to find optimal matches.
3.  **Match Reveal:**
    *   The match data is sent to **GPT-4 API** to generate the "Why you're compatible" summary, which is then displayed to the user.

---

### 5. Project Status

This project is currently in the **conceptual and architectural planning stage**. The next step is to build the MVP as outlined in our feasibility plan.

