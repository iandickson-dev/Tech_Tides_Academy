# Tech Tides Academy

> **Learn to build production-ready applications with AI — from your first artifact to your first customer, starting at $0/month.**

<div align="center">

[![YouTube](https://img.shields.io/badge/YouTube-Tech%20Tides%20Academy-red?style=flat&logo=youtube)](https://www.youtube.com/@TechTidesAcademy)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/iadickson)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

</div>

---

## Welcome 👋

Hey — I'm Ian, a Cloud & AI Consultant, AWS certified AI practitioner, and what you might call a "vibe coder." I don't have a traditional computer science background, but I've spent my career in big tech and most recently am building real applications using AI tools like Claude, and I've seen firsthand what's possible — from watching autonomous robots navigate Amazon distribution centers without ever colliding, to helping 'solopreneurs' launch their first SaaS product for less than $6/month.

**Tech Tides Academy exists to share everything I've learned along the way.**

This repo is your open-source companion to the [Tech Tides Academy YouTube channel](https://www.youtube.com/@TechTidesAcademy). It contains the frameworks, templates, interactive artifacts, and real-world examples that back up what we teach on camera. Whether you're building your very first app with Claude or optimizing LLM costs at scale, there's something here for you.

---

## Who This Is For

- **Non-traditional developers** who can prompt AI effectively but want to understand the full journey from concept to production
- **Consultants and freelancers** building client applications who need a proven, cost-efficient framework
- **Solopreneurs** launching SaaS products without a technical co-founder or VC funding
- **Technical professionals** with deep domain expertise who are newer to AI-assisted development
- **Anyone who's built something cool in Claude** and thought *"okay... now what?"*

You don't need a CS degree. You don't need to know how to code from scratch. You need curiosity, a willingness to learn, and the right framework to follow. That's what we're building here — together.

---

## What You'll Learn

### Use the Right AI Model for the Right Job

One of the biggest mistakes people make is throwing the most powerful (and most expensive) model at every task. We teach you to think in tiers:

| Model | Best For | Cost per 1M Output Tokens |
|-------|----------|--------------------------|
| **Claude Haiku** | Routine tasks — emails, summaries, parsing, classification | $1.25 |
| **Claude Sonnet** | Complex reasoning — architecture, code review, multi-step logic | $15.00 |
| **Claude Opus** | High-stakes work — security audits, compliance, system design | $75.00 |

**The takeaway:** A Haiku-first strategy can save you **90%+ on LLM costs** compared to using Sonnet or Opus for everything — with negligible quality difference on routine tasks. We'll show you exactly how.

### Take Applications from PoC to Production

| Stage | Timeline | Monthly Cost | Who It's For | What You'll Build |
|-------|----------|-------------|-------------|-------------------|
| **PoC** | 1–3 days | $0 | Just you | A working concept that proves your idea is feasible |
| **MVP** | 4–6 weeks | $0–50 | 10–100 early users | A deployed product with real users, auth, and a database |
| **Production** | 4–6 months | $500–5,000 | 1,000+ customers | An enterprise-grade application ready to scale |

Every stage has a clear framework, cost breakdown, technology recommendations, and decision criteria for when to advance.

### Build on Open-Source, Start on Free Tiers

Every technology we recommend prioritizes open-source tools with permissive licenses. You should never pay for software until free tiers can't handle your load. The recommended MVP stack costs **$0 in software licensing**:

Next.js • shadcn/ui • Tailwind CSS • NextAuth.js • PostgreSQL (Supabase/Neon) • Vercel • Vitest • Zod • GitHub Actions

---

## 📂 Repo Structure

This repository is organized by purpose, so you can find what you need based on *what you're trying to do*:

```
Tech_Tides_Academy/
│
├── /frameworks          # Written guides and reference documents
│   ├── application-development-framework.md
│   ├── model-tiering-guide.md
│   └── cost-planning-guide.md
│
├── /artifacts           # Interactive .jsx and .html demos
│   ├── email-generator.jsx
│   ├── travel-map.jsx
│   └── ...
│
├── /templates           # Reusable .docx, .pptx, .pdf templates
│   ├── project-brief-template.md
│   ├── cost-estimation-spreadsheet.xlsx
│   └── security-checklist.pdf
│
├── /examples            # Complete project walkthroughs and case studies
│   ├── email-generator-poc-to-mvp/
│   ├── travel-map-app/
│   └── ...
│
├── CONTRIBUTING.md
├── LICENSE
└── README.md            # You are here
```

---

## 🧭 Learning Path

Not sure where to start? Find your experience level below and follow the recommended path.

### 🟢 Beginner — "I can prompt AI but I've never built an app"

You're comfortable using Claude, ChatGPT, or similar tools in conversation. You may have generated some cool outputs, but you've never deployed anything or worked with a codebase.

**Your path:**
1. Read the [Application Development Framework](/frameworks) — focus on **Section 1 (AI Tool Selection)** and **Section 4 (Application Maturity Model)**
2. Explore the `/artifacts` folder — open a `.jsx` file in Claude Chat to see how interactive apps are built
3. Follow a project walkthrough in `/examples` from start to finish
4. Build your own PoC in Claude Chat (1–3 days, $0)

**Skills you'll develop:** Prompt engineering for development, understanding application layers, building your first interactive prototype.

### 🟡 Intermediate — "I've built artifacts and PoCs but don't know how to deploy"

You've built working prototypes in Claude, maybe even multi-component artifacts. But going from "it works in my browser" to "it's live on the internet" feels like a gap.

**Your path:**
1. Read the full [Application Development Framework](/frameworks) — focus on **Section 2 (Component Separation)**, **Section 3 (Modular Architecture)**, and **Section 5 (Cost Planning)**
2. Study the `/templates` for project planning and cost estimation
3. Follow an MVP case study in `/examples` end-to-end
4. Deploy your first MVP on free tiers (4–6 weeks, $0–50/month)

**Skills you'll develop:** Three-layer architecture, database integration, authentication, deployment pipelines, and cost optimization.

### 🔴 Advanced — "I can deploy apps but want to optimize costs and scale"

You're building and shipping applications, but you're either overpaying for LLM usage, unsure about security at scale, or looking to move from MVP to production-grade.

**Your path:**
1. Deep dive into **Section 5 (Cost & Infrastructure Planning)** and **Section 6 (Security Considerations)** in the framework
2. Implement model tiering in your existing applications using the decision matrices
3. Review the open-source security tooling recommendations (Semgrep, Trivy, Wazuh, OWASP ZAP)
4. Use the production cost projections to plan your scaling strategy

**Skills you'll develop:** LLM cost optimization (model tiering + prompt caching), enterprise security, production infrastructure on AWS, and scaling from hundreds to thousands of users.

---

## Core Frameworks

The heart of this repo is the **Application Development Framework** — a comprehensive guide built from real consulting projects. Here's what it covers:

### 1. AI Tool Selection & Model Tiering
How to choose the right Claude model for every task, when to use Claude Chat vs. Claude Code, and the research workflow that replaces the need for separate tools.

### 2. Application Component Separation
The three-layer architecture model (Presentation, Business Logic, Data) — all built on open-source technologies with clear workstream organization for solo developers.

### 3. Modular Architecture & Feature Addition
What modules are, why they matter, and a step-by-step strategy for adding features without breaking what already works. Includes the LLM client module pattern for model tier selection.

### 4. Application Maturity Model ⭐
The most important section. Detailed breakdowns of PoC, MVP, and Production stages — what each looks like, what it costs, and exactly when to advance between them.

### 5. Cost & Infrastructure Planning
Detailed cost projections from $0 (PoC) to $2,500/month (Production). Includes LLM cost comparisons across all three model tiers, prompt caching strategies for 80–90% input cost reduction, and growth projections from 100 to 10,000 users.

### 6. Security Considerations
Security recommendations that scale with your application's maturity. Covers OWASP Top 10 mitigations, open-source security tooling, MVP security checklists (all achievable at $0), and AWS-specific best practices.

> **📖 Read the full framework:** [`/frameworks/application-development-framework.md`](/frameworks/application-development-framework.md)

---

## Real-World Examples

This framework wasn't built in a vacuum — it comes from real projects:

- **Email Generator** — AWS/customer outreach tool built with Claude Haiku. Documented the journey from PoC to MVP, including the switch from Sonnet to Haiku with no quality loss and 92% cost savings.
- **Travel Map Application** — Interactive Leaflet-based mapping app with persistent storage, built entirely on open-source tools.
- **AWS Product Dashboard** — Cloud service announcement tracker with data visualization.

> Case studies with detailed cost breakdowns and model selection decisions are being added to the `/examples` folder. Contributions welcome!

---

## 💼 Need Help Implementing This?

I help consultants and solopreneurs build production-ready AI applications using this framework — optimized for cost efficiency and open-source tooling.

**What I offer:**
- **Framework Implementation** — Apply this methodology to your specific project with the right model tiers
- **Architecture Review** — Validate your technical decisions and LLM cost strategy
- **MVP Development** — Go from PoC to deployed MVP on free tiers
- **Production Consulting** — Scale to enterprise customers with tiered model selection

**[📅 Book a free consultation](https://calendly.com/ian-dickson-regoconsulting/1-1-with-ian-dickson)**

---

## 🤖 AI Disclaimer

### Built With AI, On Purpose

This repository — including its frameworks, code examples, templates, and this README — was developed with the assistance of AI tools, primarily [Claude by Anthropic](https://www.anthropic.com/). This isn't a footnote; it's the point. **Tech Tides Academy teaches AI-assisted development, and we practice what we preach.**

### AI-Assisted Development Is the Methodology

The applications, code samples, and project walkthroughs in this repo were built using the same AI-assisted workflow we teach: prototyping in Claude Chat, developing with Claude Code, and strategically selecting model tiers based on task complexity. When you follow our guides, you're learning a methodology that has been validated through real consulting projects and production deployments.

### Accuracy & Your Responsibility

While we strive for accuracy in everything we publish, please be aware:

- **Pricing, tooling, and free-tier limits change.** LLM pricing, SaaS free tiers, and open-source tool capabilities referenced in this repo reflect information available at the time of writing. Always verify current pricing and limits before making financial decisions.
- **AI-generated code requires review.** All code in this repo has been tested and reviewed, but AI can produce subtle errors. You are responsible for reviewing, testing, and validating any code you use in your own projects — especially anything handling sensitive data, financial transactions, or security-critical operations.
- **This is not professional advice.** The frameworks, cost projections, and recommendations here are educational. They are not substitutes for professional legal, financial, security, or architectural advice tailored to your specific situation.
- **Your results may vary.** Cost savings, development timelines, and outcomes depend on your specific use case, skill level, and application requirements.

---

## 🤝 Contributing

Tech Tides Academy is a community effort, and contributions make it better for everyone. Here's how you can get involved.

### What We're Looking For

**🟢 Case Studies & Examples (Most Welcome!)**

We love hearing how you've applied these frameworks to your own projects. If you've taken an application from PoC to MVP (or beyond), we'd love to feature your journey.

Case study submissions should include:
- The problem you were solving
- Which frameworks/sections from this repo you used
- Your technology stack and model tier selections
- Cost data (even approximate numbers are valuable)
- What you'd do differently next time

To submit a case study, open a Pull Request adding your write-up to the `/examples` folder with a descriptive subfolder name.

**🟡 Bug Fixes & Corrections (Always Appreciated)**

If you find typos, broken links, outdated pricing, incorrect technical details, or inaccurate information — please open a PR or Issue. No contribution is too small.

### What Requires Discussion First

**🔴 New Frameworks, Templates, or Code Contributions**

For anything beyond case studies and corrections — including new framework documents, templates, artifacts, or significant code additions — please **open an Issue or Discussion first** before submitting a Pull Request. This helps us:

- Ensure the contribution aligns with the repo's educational goals and quality standards
- Avoid duplicate efforts
- Provide guidance on structure and format
- Discuss security implications for any code contributions

### Pull Request Guidelines

1. **Fork the repository** and create your branch from `main`
2. **Follow the existing structure** — place files in the appropriate folder (`/frameworks`, `/artifacts`, `/templates`, `/examples`)
3. **Include clear descriptions** — your PR should explain what you're adding or changing and why
4. **Test your content** — if submitting code, ensure it runs. If submitting markdown, check formatting and links
5. **Keep it focused** — one PR per contribution topic. Don't bundle unrelated changes
6. **Respect the license** — all contributions are subject to the [Apache 2.0 License](LICENSE)

### Code of Conduct

- Be respectful, constructive, and encouraging — we're all learning
- No self-promotion or spam in Issues or PRs
- Give credit where it's due — if your work builds on someone else's, acknowledge it
- Keep discussions on-topic and productive

### Reporting Issues

- **Found a bug or error?** [Open an Issue](../../issues) with a clear description
- **Have a question or idea?** [Start a Discussion](../../discussions)
- **Security concern?** Please email directly rather than opening a public issue

---

## 📬 Stay Connected

- **YouTube:** [Tech Tides Academy](https://www.youtube.com/@TechTidesAcademy)
- **GitHub:** [@iandickson-dev](https://github.com/iandickson-dev)
- **LinkedIn:** [Ian Dickson](https://www.linkedin.com/in/iadickson)

---

## License

This project is licensed under the [Apache License 2.0](LICENSE).

You are free to use, modify, and distribute this work — including for commercial purposes — as long as you provide appropriate attribution and indicate any changes made. See the [LICENSE](LICENSE) file for full details.

---

<div align="center">

**⭐ Star this repo if you found it helpful**

**🍴 Fork it to customize for your own journey**

**📢 Share it with other AI builders**

---

*Built with AI. Taught by humans. Powered by community.*

</div># Tech_Tides_Academy
Sharing best practices, prompting frameworks, and examples to guide your Personal AI journey.
