<div align="center">

# Akshay Mahajan

**Full-Stack Developer** · Web Apps · APIs · AI-Powered Products

I build and ship full-stack applications: typed frontends, clean REST APIs,
relational data models, and LLM features that do something useful.

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-akshaymahajan24.vercel.app-111827?style=flat-square&logo=vercel&logoColor=white)](https://akshaymahajan24.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshaymahajan1274)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:akshaymahajan730@example.com)

</div>

---

## About

I'm a full-stack developer based in Ahmedabad, India. I like taking an idea from an empty repo to a deployed product: designing the data model, exposing it through an API, and building an interface people actually enjoy using.

My recent work sits at the intersection of **web applications** and **AI integration**: a resume analyzer backed by the Gemini API, and a hybrid website builder that turns natural-language prompts into editable React layouts. I also have hands-on backend experience from a Python developer internship, building REST APIs with Git, GitHub, and Docker.

**What I care about**

- Typed, maintainable code (TypeScript, schema validation)
- Clear API boundaries between frontend, backend, and AI services
- Interfaces that are polished, responsive, and accessible
- Shipping working software, not just demos

---

## Tech Stack

| | |
|---|---|
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-1F2937?style=flat-square) ![Auth.js](https://img.shields.io/badge/Auth.js-7C3AED?style=flat-square) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB_(basic)-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| **DevOps / Cloud** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |
| **AI & Tools** | ![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white) |

---

## Featured Projects

### [AI Resume Analyzer](https://github.com/akshaymahajan2004/AI_Resume_Analyzer) · [Live](https://ai-resume-analyzer-coral-ten.vercel.app)

Upload a PDF resume and a job description; get an ATS score, matched and missing skills, improvement suggestions, and generated interview questions.

- **Architecture:** Next.js + TypeScript client talking to a separate **FastAPI** service over REST
- **Pipeline:** PDF parsing with PyPDF → structured prompt → **Gemini API** analysis → typed results in the UI
- **Stack:** Next.js, TypeScript, Tailwind CSS, Framer Motion, Axios, FastAPI, Uvicorn

### [Buildify](https://github.com/akshaymahajan2004/ai_website_builder-buildify), AI Website Builder

A hybrid builder that combines AI generation with manual control: describe a layout in plain language, then refine it visually.

- **Prompt-to-code:** generates modular React components from text input
- **Visual editor:** real-time control over margins, padding, and colors
- **Project management:** save, view, and publish projects to a community showcase
- **Stack:** PERN (PostgreSQL, Express, React, Node.js)

### [EstateX](https://github.com/akshaymahajan2004/Estate-X) · [Live](https://estate-x-in.vercel.app)

A luxury real-estate platform with a public discovery experience and an authenticated admin console.

- **App Router architecture:** Next.js 15, TypeScript, Server Actions, Prisma + PostgreSQL
- **Auth & validation:** Auth.js v5 with role-based access; Zod schemas for form and API validation
- **Hybrid data service:** falls back to a mock dataset when no `DATABASE_URL` is set, so the app runs out of the box
- **Product features:** synced Leaflet map, 2D/3D floor-plan viewer, multi-step visit booking, saved-property comparison, lead pipeline (`NEW → CONTACTED → QUALIFIED → CLOSED`)
- **SEO:** JSON-LD structured data, dynamic sitemap

### [Portfolio](https://github.com/akshaymahajan2004/akshay-mahajan-portfolio) · [Live](https://akshaymahajan24.vercel.app)

An editorial-style personal site with a custom rendering layer and a small CMS.

- **Canvas cursor trails:** custom HTML5 Canvas effect using Catmull-Rom splines
- **JSON-backed CMS:** password-protected admin dashboard with CRUD for projects
- **Stack:** TypeScript, Tailwind CSS, deployed on Vercel

---

## Currently Focused On

- Building AI-powered products: LLM integrations, prompt-to-UI workflows, and clean service boundaries
- Strengthening backend fundamentals: API design, authentication, and data modeling with PostgreSQL and Prisma
- Learning cloud and data engineering concepts to complement my full-stack work

---

## GitHub Stats

<div align="center">

<img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=akshaymahajan2004&show_icons=true&hide_border=true&theme=transparent&title_color=0A66C2&icon_color=0A66C2&text_color=6B7280" />
<img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akshaymahajan2004&layout=compact&hide_border=true&theme=transparent&title_color=0A66C2&text_color=6B7280" />

<img alt="Contribution streak" src="https://streak-stats.demolab.com?user=akshaymahajan2004&hide_border=true&theme=transparent&ring=0A66C2&fire=0A66C2&currStreakLabel=6B7280&sideLabels=6B7280&currStreakNum=6B7280&sideNums=6B7280&dates=6B7280" />

</div>

---
## Contribution Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/akshaymahajan2004/akshaymahajan2004/output/github-contribution-grid-snake.svg" alt="Snake Contribution Animation" width="100%" />
</div>

## Open Source & Collaboration

My projects are public and I welcome feedback. If you spot a bug, have an architecture suggestion, or want to build something together, open an issue or a pull request, or just reach out.

I'm interested in contributing to projects involving **full-stack web development, developer tools, and AI integrations**.

---

## Let's Connect

I'm open to developer roles and internships, and to collaborating on interesting projects.

[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=vercel&logoColor=white)](https://akshaymahajan24.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshaymahajan1274)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:akshaymahajan730@example.com)
