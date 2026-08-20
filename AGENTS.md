# Project Instructions

## Stack

- Next.js 16.3.1 + App Router
- TypeScript
- Tailwind CSS 4
- ESLint
- Turbopack

## General rules

- Use the App Router, not the Pages Router.
- Prefer Server Components by default.
- Use `"use client"` only when client-side interactivity or browser APIs are required.
- Use TypeScript and Tailwind CSS 4.
- Follow the existing project structure and conventions.
- Do not install new dependencies unless they are actually needed.
- Do not change unrelated files.
- Keep components small and reusable.
- Make the UI responsive and accessible.

## Workflow

- First understand the existing code.
- For larger tasks, explain the plan before editing.
- Make focused changes.
- Do not replace working code unnecessarily.
- Prefer the current Next.js 16 APIs and patterns.
- After making changes, check TypeScript, ESLint, and that the app actually works.
- Use the matching Next.js Agent Skills in `.agents/skills/` when the task calls for them (`next-dev-loop` for runtime verification; Cache Components / Partial Prefetching skills only when those features are in scope).
- Do not enable Cache Components or Partial Prefetching unless the user explicitly asks.
