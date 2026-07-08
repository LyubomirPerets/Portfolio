# CLAUDE.md

Guidance for Claude Code when working in this repository.

## Project

Personal portfolio site — the capstone project for a Frontend Engineering AI
internship. The site showcases projects, skills, and experience, and is
itself meant to demonstrate frontend engineering ability.

## Tech Stack

Primary stack for this project:

- **TypeScript** — preferred over plain JavaScript for all new frontend code
- **React** — component framework for the UI
- **HTML / CSS** — markup and styling (semantic HTML, accessible by default)
- **JavaScript** — fallback only; new files should be `.ts`/`.tsx` unless
  there's a specific reason not to

Languages known and potentially referenced/showcased elsewhere in the
portfolio (e.g. project write-ups, embedded demos, code samples), but not
the primary build stack for the site itself:

- **Java**
- **C++**
- **C**
- **Python**

When in doubt about which language a task calls for, default to the
TypeScript/React/HTML/CSS stack unless the user is clearly working on a
showcased project written in one of the other languages.

## Conventions

- Prefer functional React components with hooks over class components.
- Keep components small and colocated with their styles/tests where
  practical.
- Use TypeScript types/interfaces for props and data models — avoid `any`.
- No inline styles unless there's a specific reason; prefer CSS
  modules/stylesheets consistent with whatever styling approach is already
  in use once established.

## Commands

_To be filled in once the project is scaffolded (e.g. `npm run dev`,
`npm run build`, `npm test`, `npm run lint`)._

## Notes

This file should be updated as the project's structure, tooling, and
conventions are established (e.g. once a framework/bundler like Vite or
Next.js is chosen, once a test runner is added, once deployment is set up).
