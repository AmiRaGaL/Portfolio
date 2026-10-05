# Deva Sai Kumar Bheesetti · Portfolio

Source for my personal portfolio site, covering backend APIs, full-stack and React Native product work, cloud deployments, and applied AI/RAG systems.

**Live site:** [portfolio-deva-sai.vercel.app](https://portfolio-deva-sai.vercel.app/)

## Overview

A lightweight static site: `index.html` loads each section from `sections/*.html`, and a resume-aware AI chat assistant is served from the `api/` routes. It is aimed at recruiters and engineering teams who want a quick read on my production experience, projects and skills.

## Featured Work

- **TrustOps Platform**: Multi-tenant moderation operations platform with RBAC, workflow queues, audit logs, NestJS, Next.js, PostgreSQL, Prisma, Docker, GitHub Actions, Vercel, Render, and Supabase.
- **VitaScan**: AI-powered symptom checker and health assistant across web and mobile using React Native/Expo, NestJS, Supabase, PostgreSQL, pgvector, RAG, OpenAI/Gemini, and LangChain.
- **Support RAG Evaluator**: RAG evaluation platform for document ingestion, retrieval quality, grounded answers, refusal behavior, citations, logs, eval runs, OpenAPI docs, and CI-safe backend tests.

Additional gallery items cover healthcare NLP research, production social-platform engineering, clinical analytics, IoT/mobile ML, enterprise Pega Decisioning, automation, and NLP projects.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap 4
- **Architecture**: Static `index.html` with dynamically loaded `sections/*.html`
- **Styling**: Custom chocolate/brown/cream design system, responsive CSS grids, glass-style cards, warm shadows, and accessible contrast
- **Animation/UI**: AOS plus subtle CSS transitions
- **AI Integration**: Floating AI chat widget and resume-aware chat section backed by API routes
- **Hosting**: Vercel

## Site Sections

- **Hero**: Recruiter-focused positioning, credibility metrics, resume CTA, and profile card
- **Featured Work**: Three strongest project cards with technology chips, live links, GitHub links, and proof statements
- **About**: Concise professional summary with current focus, education, AI depth, and enterprise background
- **Skills**: Grouped panels for backend, frontend/mobile, cloud/devops, databases, AI/RAG, data automation, and enterprise/Pega
- **Experience**: Timeline led by current work as a Full-Stack Software Engineer at OurFreedom.ai (Jan 2026 – Present)
- **Projects**: Clean gallery ordered by hiring signal with category labels and concise summaries
- **Chat**: Resume-aware AI assistant for role-fit and experience questions
- **Contact**: Direct links and contact form

## Design

A warm chocolate, brown, gold and cream palette with custom buttons, chips and responsive cards. The page leads with credibility and the strongest recent projects, then supports deeper review through experience, skills, chat and contact.

## Local Development

Because the site dynamically fetches section HTML files, serve it with a local static server instead of opening `index.html` directly.

```bash
python3 -m http.server 3000
```

Then open http://localhost:3000.

## Deployment

The portfolio is deployed on Vercel. Static assets, section files, API routes, and the AI chat widget are served from this repository's deployed project.

## Contact

- Portfolio: [portfolio-deva-sai.vercel.app](https://portfolio-deva-sai.vercel.app/)
- GitHub: [@AmiRaGaL](https://github.com/AmiRaGaL)
- LinkedIn: [Deva Sai Kumar Bheesetti](https://www.linkedin.com/in/deva-sai-kumar-bheesetti-34380812b)
