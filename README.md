# Oussama Faiz Portfolio

A production-style personal portfolio built with React and Vite for Oussama Faiz, a software engineer focused on full-stack systems, AI-enabled products, and cloud delivery. This repository powers the public site and consolidates current experience, featured work, certifications, freelance services, and contact channels into a single responsive interface.

<p align="left">
  <a href="https://faizoussama.vercel.app"><strong>Live site</strong></a> ·
  <a href="https://github.com/faiz-oussama">GitHub</a> ·
  <a href="https://linkedin.com/in/oussama-faiz">LinkedIn</a> ·
  <a href="mailto:faizouss123@gmail.com">Email</a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React 18" />
  <img src="https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 6" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4" />
  <img src="https://img.shields.io/badge/Framer_Motion-Animation-black?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" />
  <img src="https://img.shields.io/badge/Vercel_Analytics-Integrated-black?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Analytics" />
</p>

## Overview

This repository powers the public portfolio and presents a current snapshot of work across backend engineering, AI product integration, cloud infrastructure, and frontend implementation. The application is designed as a responsive single-page experience with animated transitions, theme switching, rich project storytelling, and a service/business layer beyond a standard developer portfolio.

## Highlights

- Responsive single-page portfolio with desktop navigation and mobile menu handling
- Dark/light mode powered by a shared React context and custom MUI switch
- Motion-heavy hero using Framer Motion, React Spring text effects, Swiper carousels, and count-up statistics
- Detailed sections for technologies, featured projects, freelance services, case studies, experience, certifications, and contact
- External project links to live demos and GitHub repositories
- Vercel Analytics integration for usage tracking

## Current Snapshot

- Based in Morocco and currently contributing to applied AI research at Oracle's AI Services Team
- Recent work includes AI voice-agent platforms, RAG workflows, LLM-assisted test generation, and cloud-native deployment pipelines
- Certifications include Oracle Certified Professional Java SE 11 Developer, OCI Architect Professional 2024, OCI DevOps Professional 2024, OCI Foundations Associate, and Generative AI Professional 2026

## Experience Snapshot

| Role | Organization | Focus |
| --- | --- | --- |
| Research Assistant | Oracle | Applied AI research, service-oriented experimentation, and evaluation of AI-driven workflows |
| Full-Stack Software Engineer | E-Call Services | No-code/low-code AI voice-agent SaaS with FastAPI, Next.js, RAG, vector stores, and telecom APIs |
| Java Backend Engineer | Univade Technology | Low-code Spring Boot generation and AI-assisted JUnit 5 test generation with Spring AI and GPT-4o |

## Featured Projects

| Project | Summary | Stack |
| --- | --- | --- |
| MoroccoGuide-AI | AI-powered travel assistant for personalized Morocco itineraries, day plans, recommendations, and cultural insights. | React, Node.js, Express, MongoDB, Gemini API |
| Match Ticket Platform | End-to-end DevOps implementation for online ticket sales and reservations with CI/CD and cloud deployment. | Spring Boot, Docker, Jenkins, AWS, Nginx, PostgreSQL |
| NLP Annotation Platform | Collaborative platform for annotation quality control and inconsistency detection using BERT models. | Spring Boot, Flask, MariaDB, BERT |
| Multi-Layer Unit Tests Generator | AI-driven tool that generates repository, service, and controller tests from prompts and templates. | Java, Spring AI, GPT-4o, FreeMarker, JUnit 5 |
| LogFlow Analytics | Real-time log streaming and analytics platform with anomaly detection and enterprise monitoring workflows. | Java, ELK Stack, Kafka, JavaFX |

## Freelance Focus

- Full-stack web development for dashboards, secure APIs, admin systems, and production-ready business platforms
- Mobile app delivery with backend integration and cross-platform workflows
- Deployment, DevOps, and AI integration covering CI/CD, monitoring, LLM workflows, and automation
- Portfolio case studies currently include Achkid Bot, Wafy Bot, and an AI email backoffice for call-center operations

## Stack

### Application Stack

| Area | Technologies |
| --- | --- |
| Frontend | React 18, Vite 6, Tailwind CSS 4, custom CSS |
| Interaction | Framer Motion, React Spring, Swiper |
| UI Utilities | MUI, Styled Components, tech-stack-icons |
| Analytics | @vercel/analytics |

### Engineering Stack Represented in the Portfolio

| Area | Technologies |
| --- | --- |
| Languages | Java, Python, C#, C++, JavaScript, TypeScript, PHP |
| Frameworks | Spring, Spring Boot, Flask, .NET, React, React Native, Next.js, Laravel |
| Data | PostgreSQL, MySQL, MongoDB, Firebase, Oracle, Elasticsearch |
| DevOps & Cloud | Git, GitLab CI, Docker, Kubernetes, Terraform, Jenkins, AWS |

## Local Development

```bash
npm install
npm run dev
```

The development server is started by Vite. Production assets can be built and previewed locally with the commands below.

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Create a production build |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint across the project |

## Project Structure

```text
.
├── public/
│   ├── tech-stack/     # stack icons used in the technologies section
│   ├── videos/         # looping video assets for the skills showcase
│   ├── bg.webp         # contact section background
│   ├── main.jpeg       # about/profile image
│   └── icon.png
├── src/
│   ├── assets/         # animated text, counters, icon helpers, visual effects
│   ├── components/     # portfolio sections, theme provider, loader, toggle
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

## Content Management

Most portfolio content is currently defined in `src/components/Portfolio.jsx`, including:

- featured projects and external links
- work experience and certifications
- freelance services, proof points, and case studies
- technology categories and contact links

Theme behavior lives in `src/components/DarkModeProvider.jsx` and `src/components/ToggleButton.jsx`, while reusable motion and UI primitives live in `src/assets/`.

## Contact

- Website: [faizoussama.vercel.app](https://faizoussama.vercel.app)
- GitHub: [faiz-oussama](https://github.com/faiz-oussama)
- LinkedIn: [oussama-faiz](https://linkedin.com/in/oussama-faiz)
- Email: [faizouss123@gmail.com](mailto:faizouss123@gmail.com)
