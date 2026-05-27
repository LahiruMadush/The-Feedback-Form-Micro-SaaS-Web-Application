# The Feedback Form

A production-grade Micro SaaS application that delivers a lightweight, customizable, and embeddable feedback widget for websites and apps[cite: 18, 27]. [cite_start]It is integrated with a dedicated administrative dashboard for seamless feedback management[cite: 19].

## 🚀 Features
* **Embeddable Widget:** Low-code integration for contextual user feedback[cite: 27, 31].
* **Admin Dashboard:** Centralized interface for reviewing and managing submitted data[cite: 48].
* **Tiered Functionality:** Designed with a Free tier (basic forms, email exports) and a Pro tier (custom branding, Slack/Jira integrations)[cite: 39].
* **High-Performance Delivery:** Hosted on Vercel utilizing Edge network capabilities[cite: 43, 54].

## 🛠️ Tech Stack
**Frontend:** * Next.js (SPA) [cite: 51]
* TypeScript (Strong typing) [cite: 51, 61]
* Tailwind CSS (UI consistency) [cite: 51, 62]

**Backend & Infrastructure:**
* Vercel Functions (Node.js API routes) [cite: 52, 57]
* Supabase / PostgreSQL (Database management & automated backups) [cite: 42, 53, 105]
* GitHub Actions (CI/CD automation) [cite: 80]

## ⚙️ DevOps & Architecture
This project implements modern reliability engineering and DevOps practices:
* **CI/CD Pipeline:** Automated dependency installation, linting, building, and deployment to Vercel via `.github/workflows/deploy.yml`[cite: 81, 86, 88, 89, 90].
* **Version Control:** Adheres to a GitFlow Lite branching strategy (`main`, `feat/*`, `fix/*`) and Conventional Commits format[cite: 71, 72, 76].
* **Deployment Strategy:** Blue-green deployments via Vercel with preview environments generated for each Pull Request[cite: 103, 104, 106].
* **Testing:** Configured for Unit tests (Jest) and Integration tests (Supertest)[cite: 82, 92].

## 💻 Getting Started
First, install the dependencies using `pnpm` (required for monorepo speed):
```bash
pnpm install
