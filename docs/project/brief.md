# Mission brief

## Repository creation decisions

Repository: devlootxyz-bounties/sondfree

Purpose: I want to make a sound cloud variant

Audience: Independent artists wanting to create and publish msuci, but without having technical knowledge

Description: sOUNDFREE IS FOR ALL GOOD ARTIST FREE

License: MIT

Copyright: 2026 devlootxyz-bounties

Contact: Not specified

Reviewed files already created: README.md, CONTRIBUTING.md, LICENSE

## Repository setup conversation (chronological)

Use assistant proposals to understand the user replies. A proposal is a decision only when the user accepted it; the reviewed settings above are the final repository choices.

### Assistant

Let's get your new GitHub repository off to a great start! To begin, what should this repository help people do? Think of the main purpose or goal your project aims to achieve.

### User

Purpose and goals: I want to make a sound cloud variant

### User

Purpose and goals: I want to make a sound cloud variant

### User

Purpose and goals: I want to make a sound cloud variant

### User

Purpose and goals: I want to make a sound cloud variant

### User

Purpose and goals: I want to make a sound cloud variant

### User

Purpose and goals: I want to make a sound cloud variant

### User

Purpose and goals: I want to make a sound cloud variant

### Assistant

Great! Now, who do you envision as the main audience for your SoundCloud variant? For example, independent musicians, podcasters, music fans, or developers? Knowing your audience helps tailor the project to their needs.

### User

Intended audience: Independent artists wanting to create and publish msuci, but without having technical knowledge

### Assistant

Nice! Now let's pick a repository name. It should be concise, memorable, and reflect your project's focus. Something like `soundcloud-variant`, `music-publish`, or `artist-hub` could work. What would you like to name it?

### User

Repository name: sondfree

### Assistant

Now, could you provide a short description for your repository? This should be a brief summary that appears on GitHub, helping visitors quickly understand what your project is about. You can keep it simple, like "A platform for independent artists to easily publish and share their music."

### User

Short description (optional): sOUNDFREE IS FOR ALL GOOD ARTIST FREE

### Assistant

Next, let's choose a license for your repository. The license defines how others can use, modify, and share your code. The dropdown includes popular options like MIT, Apache-2.0, BSD-3-Clause, GPL-3.0, and AGPL-3.0. If you'd like, I can explain the differences to help you decide.

### User

I confirm MIT as the license for this repository.

### Assistant

Thanks for confirming the MIT license — a great choice for broad reuse and simplicity. Now, who should be listed as the copyright holder, and what year should we use? You previously mentioned “devlootxyz-bounties” and 2026; do you want to keep those?

### User

Use devlootxyz-bounties as the copyright holder and 2026 as the copyright year.

### Assistant

Let's decide which documentation files to include. A README.md is essential to explain your project's purpose, audience, usage, and status. You might also consider CONTRIBUTING.md to guide contributors, CODE_OF_CONDUCT.md to set community standards, and SECURITY.md for private vulnerability reporting (which requires a contact email). What set of these documents would you like to include?

### User

Include these documentation files: README.md, CONTRIBUTING.md.

### Assistant

All key decisions are set: your repository named `sondfree` aims to help independent artists publish music easily, with an MIT license and essential docs README.md and CONTRIBUTING.md.

You can now use the Draft repository documents to generate and review these files before publishing. If you want to revisit or add anything like a Code of Conduct or Security policy later, just let me know!

### User

Draft the repository documents using my confirmed decisions.

### Assistant

Here's the initial README.md and CONTRIBUTING.md for your sondfree repository. They reflect your project goals and invite contributions in a friendly, clear way.

## Planning continuation

Continue building this new project from the decisions above. The repository and reviewed documents already exist. Plan the implementation and first usable release; do not restart repository onboarding or propose creating the same documents again. Later user corrections supersede earlier choices. Unstated scope, stack, deadlines, budgets, and contributor commitments remain open. Ask only about missing implementation decisions.

## User update

Quick plan · edit later

## Planned parent issue

# Plan and start building the sONDFREE music publishing platform

## Overview

sONDFREE is a simple, accessible platform for independent artists to create and publish music without technical barriers. This plan focuses on laying the groundwork for a minimal viable product (MVP) that enables basic music upload, storage, and playback.

## Scope

- Design and implement a basic web app interface for artists to upload and share music.
- Develop backend services to handle file storage and metadata management.
- Ensure ease of use for non-technical users.

## Out of scope

- Advanced social features (likes, comments, followers).
- Monetization or licensing management.
- Mobile apps or offline support at this stage.

## Acceptance criteria

- Users can register and log in.
- Users can upload audio files with basic metadata (title, artist name).
- Uploaded tracks are stored securely and playable via a web interface.
- Documentation updated with setup and usage instructions.

## Context

- Repository: devlootxyz-bounties/sondfree
- License: MIT
- Audience: Independent artists without technical knowledge
- Current status: scaffold with README and CONTRIBUTING.md

## Assumptions & open decisions

- Technology stack is open; recommend using popular web frameworks (React, Node.js) and cloud storage.
- Authentication method to be decided (email/password or OAuth).
- Audio formats supported to be clarified.

---

### Tasks

1. **Design basic user interface for music upload and playback**

   Design wireframes and UI components for user registration, login, music upload form, and playback page.

   **Acceptance:** Wireframes approved; UI components scaffolded.

   **Dependencies:** None

   **Handoff:** Design files and React component skeletons.

2. **Implement backend API for user management and music storage**

   Develop REST API endpoints for user registration/login, track upload, and retrieval.

   **Acceptance:** API endpoints functional and tested locally.

   **Dependencies:** Task 1 (for aligning API with UI needs)

   **Handoff:** API codebase with README for setup.

3. **Integrate frontend with backend to enable music publishing flow**

   Connect UI components to backend API for full upload and playback functionality.

   **Acceptance:** Users can register, upload tracks, and play them in the web app.

   **Dependencies:** Tasks 1 and 2

   **Handoff:** Full working MVP frontend and backend integration.

4. **Write setup and usage documentation for contributors and users**

   Document installation, configuration, and usage instructions.

   **Acceptance:** Clear README updates and usage guide added.

   **Dependencies:** Task 3

   **Handoff:** Updated README.md and CONTRIBUTING.md

## AGENTS.md

Project: Plan and start building the sONDFREE music publishing platform
Issue: Plan and start building the sONDFREE music publishing platform

### Context provenance
Mission brief revision: 2. Review affected task context if this brief changes.
The issue scope, acceptance criteria, dependencies, and handoff below are this task's contract. Verify referenced source files before assuming they exist.

### Shared mission
Use this issue's scope and acceptance criteria as the contract. Read the repository's AGENTS.md and linked parent context. Load only the prerequisite issue contracts and source references needed for this task. This issue-local guide supplements repository instructions.

### Collaborate
- A coordinating agent tracks dependencies, assigns bounded tasks, and keeps the shared plan current.
- Implementation agents own clearly named files or interfaces. Work in parallel only when tasks are independent; agree on shared interfaces first.
- A reviewing agent checks the diff, acceptance criteria, and relevant tests before handoff.
- Share blockers, decisions, changed files, and test results in the issue. Preserve other contributors' work and coordinate overlapping edits.

### Handoff
Keep changes focused on this issue. Report what changed, verification results, remaining risks, and the next dependency to unblock. Ask the maintainer before expanding scope. Publishing issues does not authorize agents to merge, deploy, spend funds, or contact contributors.
