# Deva Sai Kumar Bheesetti Portfolio

Modern professional software engineering portfolio for Deva Sai Kumar Bheesetti, focused on backend APIs, full-stack product development, React Native apps, cloud deployments, and applied AI/RAG systems.

Live site: https://portfolio-deva-sai.vercel.app/

## Overview

This repository contains a static portfolio website designed for recruiters, hiring managers, and engineering teams evaluating Deva's production engineering experience. The redesigned site keeps the lightweight section-loader architecture while presenting the work as a polished modern portfolio instead of a basic one-page Bootstrap scroll.

The portfolio emphasizes backend ownership, product judgment, cloud delivery, mobile/full-stack range, AI/RAG evaluation, and enterprise engineering experience.

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
- **Experience**: Polished timeline highlighting current production engineering work at OurFreedom.ai
- **Projects**: Clean gallery ordered by hiring signal with category labels and concise summaries
- **Chat**: Resume-aware AI assistant for role-fit and experience questions
- **Contact**: Direct links and contact form

## Design Direction

The redesign uses a premium warm chocolate, brown, gold, and cream identity. It replaces generic Bootstrap blue accents with custom buttons, chips, borders, typography, section rhythm, and responsive cards intended to feel recruiter-friendly and software-engineer professional.

The goal is conversion-oriented: quickly establish credibility, surface the strongest recent GitHub projects, then support deeper review through experience, skills, chat, and contact paths.

## Local Development

Because the site dynamically fetches section HTML files, serve it with a local static server instead of opening `index.html` directly.

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Deployment

The portfolio is deployed on Vercel. Static assets, section files, API routes, and the AI chat widget are served from this repository's deployed project.

## Branch and PR Notes

Portfolio changes should be made through feature branches and reviewed through pull requests.

Recommended PR title:

```text
Modernize portfolio design and recruiter-focused project showcase
```

Recommended PR body highlights:

- Modernized visual design using the chocolate/brown theme
- Added featured project showcase
- Reordered site sections for recruiter conversion
- Added recent GitHub projects
- Updated README
- Improved SEO, hero, about, skills, experience, and projects
- Preserved static architecture and AI chat widget

## Contact

- Portfolio: https://portfolio-deva-sai.vercel.app/
- GitHub: https://github.com/AmiRaGaL
- LinkedIn: https://www.linkedin.com/in/deva-sai-kumar-bheesetti-34380812b
