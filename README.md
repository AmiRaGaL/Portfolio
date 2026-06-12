# Deva Sai Kumar Bheesetti Portfolio

Personal portfolio website for Deva Sai Kumar Bheesetti, a Software Engineer focused on backend and full-stack product development, React Native apps, cloud deployments, and applied AI/RAG systems.

Live site: https://portfolio-deva-sai.vercel.app/

## Overview

This repository contains a static portfolio website designed to present Deva's software engineering experience, production work, and applied AI projects to recruiters and hiring teams. The site emphasizes backend APIs, full-stack product development, mobile engineering, cloud deployment workflows, and RAG/LLM systems.

Do not commit directly to `main`. Portfolio updates should be made through feature branches such as `portfolio-polish-recruiter-funnel` and reviewed through pull requests.

## Featured Work

- **TrustOps Platform**: Full-stack moderation operations platform with multi-tenant RBAC, moderation queues, audit logs, workflow automation, NestJS, Next.js, PostgreSQL, Prisma, Docker, GitHub Actions, Vercel, Render, and Supabase.
- **VitaScan**: AI-powered symptom checker and health assistant using Next.js, React Native/Expo, NestJS, Supabase, PostgreSQL, pgvector, RAG, OpenAI/Gemini, LangChain, Vercel, Render, and Supabase.
- **Support RAG Evaluator**: Full-stack RAG evaluation platform with document ingestion, pgvector retrieval, grounded answers with citations, refusal behavior, query logs, eval runs, OpenAPI docs, and deterministic CI-safe testing.
- **SDoH Prediction Thesis**: Graduate healthcare NLP research using transformer models and LLMs to predict Social Determinants of Health severity from opioid-related clinical notes.
- **OurFreedomAI Production Social Platform Experience**: Production engineering work across NestJS APIs, MongoDB data models, React Native screens, privacy controls, content moderation, voice communication, CI/CD, and release workflows.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Animation/UI**: AOS, custom responsive styling
- **Hosting**: Vercel
- **Portfolio Architecture**: Static `index.html` with dynamically loaded section HTML files
- **AI Integration**: Floating AI chat widget and resume-aware chat experience backed by API routes

## Site Sections

- **Home**: Recruiter-focused software engineering positioning and core skill badges
- **About**: Backend, full-stack, cloud, and applied AI background
- **Skills**: Organized by backend, frontend/mobile, cloud/devops, databases, AI/RAG, data automation, and enterprise/Pega
- **Experience**: Production engineering, graduate research, automation, and enterprise platform work
- **Projects**: Featured software engineering and AI/RAG projects ordered by hiring signal
- **Chat**: Resume-aware AI assistant
- **Contact**: Contact form and professional links

## Local Development

Because this is a static site with dynamically loaded HTML sections, serve it with a lightweight static server instead of opening `index.html` directly.

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Deployment

The portfolio is deployed on Vercel. Static assets, section files, API routes, and the AI chat widget are served from this repository's deployed project.

## Contact

- Portfolio: https://portfolio-deva-sai.vercel.app/
- GitHub: https://github.com/AmiRaGaL
- LinkedIn: https://www.linkedin.com/in/deva-sai-kumar-bheesetti-34380812b
