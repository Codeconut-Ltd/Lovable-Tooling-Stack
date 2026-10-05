# AI Builder Toolkit

![Toolkit](images/teaser.svg)

AI builder toolkit – Designed for Lovable; compatible with most platforms.

TOC

- [About](#about)
- [Why use this?](#why-use-this)
- [Who might benefit?](#who-might-benefit)
- [How does it work?](#how-does-it-work)
- [Supported stacks](#supported-stacks)
- [Packages & Pricing](#packages--pricing)
- [Get in touch](#get-in-touch)
- [Disclaimer](#disclaimer)

---

## About

Enhance the reliability and scalability of any AI application by (re)introducing a deterministic toolchain.

_This repository is a placeholder for a commercial product. Get in touch for details._

### Goals

Even if most code might be built by AI, the stack can help reduce drift and bugs, and thus potentially reduce overall token usage (= lower costs).

Model choice, agentic development, and code lookups (e.g. through tools such as `Context7`) can bring code only to a certain level. However, they all lack the fundamental distinction that they 'guess' the best solution and can still introduce bugs, whereas static code analyzers use deterministic analysis to identify certain classes of issues.

---

## Why use this?

- Save costs/tokens when crafting and shipping features
- Save time and effort by reducing the need for fixes, debugging, and regression handling
- Increase the reliability of AI-generated code in local and cloud-based workflows
- Reduce drift and potential bugs in AI-generated code
- Increase code maintainability → Allow faster scaling and feature implementation
- Help identify certain security issues

---

## Who might benefit?

Most effective when used prior to a new application build, as a foundation.

- AI builders with access to their codebase, wherever it is
- People building locally (e.g. via Claude Code) or via cloud-based builders/LLMs
- People undertaking gradual/incremental refactoring of small to medium-sized applications
- Solo developers who are setting up their first project from scratch or want to improve existing ones
- Teams with limited experience in application development or AI use

---

## How does it work?

> Please reach out to discuss the details and access the code.

1. Install the code in a clean Git repository
2. Set up a secure development environment that supports the toolchain (e.g. via Docker) – AI builders might support most tools, but not all of them, such as external SaaS
3. Configure Git (especially GitHub) workflows and CI/CD pipelines as needed
4. Connect the project to a cloud-based AI builder (e.g. Lovable)
5. Use tools inside the builder or locally, depending on what is supported and considered best practice

---

## Supported stacks

Only the stated technologies are supported.

### Required

- React 19+
- TanStack Start
- Supabase
- Node.js
- Docker
- Git/GitHub

### Optional/Add-ons

#### Code Analyzers, Linters & Formatters

**Linter and formatter toolchains:** Based on open-source stacks. Several compatible options with preconfigured details are provided. The ultimate choice depends on the overall stack and the project's or team's requirements.

**External SaaS – Advanced static code analysis:** These might be recommended for the best results. A functioning, effective default is provided but can be exchanged depending on the requirements.

#### Skills & Prompts

While these might seem like basic needs, a well-defined project is essential for any AI agent to be effective. Open-source tools are available, but it is highly recommended to enhance them with stack- and project-specific configurations.

---

## Packages & Pricing

As the packages are customizable and depend on the project size, please get in touch for a quote. A demo, trial, and support can be provided.

_No subscriptions – Source code is delivered as-is, with versions up to date at the time of delivery._

---

## Get in touch

Interested in a trial, stack customization, or collaboration? Let's connect and chat about your next project:

<br>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/linkedin-Connect-736c66.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/theremotecoder)
[![Email](https://img.shields.io/badge/Email-Say_Hello-736c66.svg?style=for-the-badge)](mailto:contact@codeconutltd.com)
[![Cal.com](https://img.shields.io/badge/Meeting-Learn_More-736c66.svg?style=for-the-badge)](https://cal.com/codeconut/30min?user=codeconut)
[![Website](https://img.shields.io/badge/Web-Codeconut_Ltd.-736c66?style=for-the-badge&logo=astro&logoColor=white)](https://www.codeconutltd.com)

</div>

---

## Disclaimer

Also read:

- [Limitations & Disclaimer](DISCLAIMER.md)
