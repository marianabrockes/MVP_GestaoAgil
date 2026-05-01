# CodeBrincando — Product Management & Design

This repository documents the product planning, UX design, and agile management work behind CodeBrincando — a platform that teaches programming to children through guided theory, bug-fixing challenges, and an AI tutor.

The work here covers the full product lifecycle: from defining the vision and personas, through wireframing both user flows, to sprint planning and backlog management in Jira.

> **Implementation repositories:**
> [mvp_codebrincando_api](https://github.com/marianabrockes/mvp_codebrincando_api) · [mvp_codebrincando_frontend](https://github.com/marianabrockes/mvp_codebrincando_frontend)

---

## Product Demo

[▶ Watch the product walkthrough on YouTube](https://youtu.be/UPxprn2hPvo)

---

## What's in this repository

- **Lean Inception** — product vision, personas, user journeys, feature prioritization and MVP definition (`LeanInception_CodeBrincando_MarinaBrockes.pdf`)
- **Wireframes** — full UX flow for both user profiles: educator and student (`wireframe_CodeBrincando/`)
- **Sprint Backlog** — 3 sprints planned in Jira with user stories, acceptance criteria, story points, DoR, DoD and non-functional requirements (`sprint_backlog_MarianaBrockes.pdf`)
- **Product Canvas** — available on [Miro](https://miro.com/app/board/uXjVJG1NgBw=/?share_link_id=952864625416)
- **Showcase video** — product walkthrough on [YouTube](https://youtu.be/UPxprn2hPvo)

---

## Product Overview

CodeBrincando targets two distinct user profiles:

**Educator (Manu)** — registers her school, creates classes, generates student logins, and monitors each student's progress through a management dashboard.

**Student (Lua)** — logs in with credentials provided by the teacher, goes through a theory module explaining web concepts (HTML, CSS, JavaScript), then enters the Challenge Map to fix buggy code in an interactive editor with live preview. If something isn't clear, she asks RoboTeca — the AI tutor — for a simpler explanation.

---

## Wireframes

The wireframes cover the complete product, including features planned beyond the MVP:

**Educator flow** — landing page, school registration, class management panel, student registration with auto-generated logins, progress dashboard per class and per student.

**Student flow** — login screen, theory module, challenge map, interactive code editor with live preview, feedback screens (wrong answer hint and success celebration).

---

## Agile Planning

The backlog was managed in Jira across 3 sprints, with 2 items remaining in the backlog for future increments.

| Sprint   | Items                                                            | Period          |
| -------- | ---------------------------------------------------------------- | --------------- |
| Sprint 1 | School registration, Class registration, Interactive code editor | Sep 22 – Sep 29 |
| Sprint 2 | Student registration, Student login, Challenge map               | Sep 29 – Oct 6  |
| Sprint 3 | Product landing page, Theory module, Progress dashboard          | Oct 6 – Oct 13  |
| Backlog  | Live preview, Medal system                                       | Oct 20 – Oct 27 |

**Epics:**

- [EPIC-1] Learning Environment
- [EPIC-2] Educator Panel
- [EPIC-3] Onboarding & Presentation

Each user story was written in the format "As [persona], I want... so that..." with acceptance criteria in GIVEN/WHEN/THEN format, story point estimates, DoR and DoD checklists, and non-functional requirements covering usability, performance, security, and cross-browser compatibility.

---

## MVP Scope

The MVP was defined through feature sequencing, weighing effort and business value. The implemented MVP covers the student-facing side of the platform: login, theory module, challenge map, interactive editor, and AI tutor (RoboTeca).

The educator panel — school registration, class and student management, progress dashboard — was fully designed and planned but scoped to a future increment.

---

## Tools Used

- **Figma** — wireframes
- **Miro** — product canvas and Lean Inception
- **Jira** — sprint planning and backlog management
