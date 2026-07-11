# AI Interview Platform 🚀

An AI-powered interview preparation platform that analyzes a candidate's resume and target job description to generate personalized interview preparation material.

## Features

- Upload Resume (PDF)
- Extract resume content using PDF parsing
- AI-powered interview analysis using Google Gemini
- Match score generation
- Technical interview questions
- Behavioral interview questions
- Skill gap analysis
- Personalized preparation roadmap
- ATS-friendly resume generation
- Resume PDF export

## Tech Stack

### Frontend
- React.js
- Vite
- SCSS
- Context API

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Multer
- PDF-Parse
- Puppeteer

### AI Integration
- Google Gemini API

## Project Workflow

1. User uploads resume and enters job description.
2. Resume text is extracted using `pdf-parse`.
3. Candidate profile and job description are sent to Gemini.
4. Gemini generates:
   - Match Score
   - Technical Questions
   - Behavioral Questions
   - Skill Gaps
   - Preparation Plan
5. Results are stored in MongoDB.
6. User can generate an ATS-friendly resume PDF.

## Installation

### Backend

```bash
cd Backend
npm install
npm start
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## Author

Anushka Tiwari

<img width="949" height="412" alt="Screenshot 2026-07-11 164337" src="https://github.com/user-attachments/assets/1c3d3fd6-d0ab-436a-83d1-87b60c33fc03" />
<img width="929" height="410" alt="Screenshot 2026-07-11 164327" src="https://github.com/user-attachments/assets/ab613974-9808-44f3-b28a-9cfdfaa9c4ac" />
<img width="959" height="434" alt="Screenshot 2026-07-11 164202" src="https://github.com/user-attachments/assets/3cf1b427-090d-4860-9b13-bf50531768a4" />
