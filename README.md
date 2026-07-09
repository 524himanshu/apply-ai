# OfferForge — AI Career Prep & Evaluation Suite

OfferForge is a professional candidate preparation dashboard designed to audit resumes, practice for mock technical interviews, draft personalized outreach templates, and research target job positions.

---

## 🌟 Key Features

- **Evaluate (Match Scorer)**: Renders instant compatibility index ratings (A-F grade scale) of user resumes against target Job Descriptions using Groq LLM pipelines.
- **Outreach Generator**: Generates clean, personalized recruiter email templates tailored to target companies and job roles.
- **Interview Prep Sandbox**: Runs dynamic custom interview training sessions with adaptive technical Q&As.
- **Job Finder & Tracker**: Search for positions and log application state milestones in an interactive tracker.

---

## 🛡️ Privacy Guard: DrishtiAI PII Redactor Integration

OfferForge incorporates the client-side **DrishtiAI PII Redaction** shield:
- All user-pasted **CV (Resume)** and **Job Description** fields are sanitized in the browser prior to request execution.
- Auto-detects and redacts sensitive parameters (like candidate emails, telephone numbers, and street addresses) to prevent accidental data leakage to public third-party endpoints.

---

## 📂 Tech Stack

- **Frontend**: Next.js App Router (TypeScript, React 19)
- **API Models**: Llama-3.3-70b-versatile (via Groq API key client)
- **Document Export**: docx & file-saver

---

## 🚀 Local Setup

1. Clone and navigate to the directory:
   ```bash
   cd career-ops-ui
   ```
2. Install npm packages:
   ```bash
   npm install
   ```
3. Run the Next.js development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000). Enter your Groq API key in the sidebar panel to begin!
