# ForgeOS

**Your founder command centre.** A focused workspace for discovering resources, creating, building and launching products.

## Current foundation

- Responsive React + TypeScript + Vite application.
- Dark, restrained interface with a lime accent system, subtle motion and mobile navigation.
- Resource Library seeded with a starter selection from the design, AI, development, film and startup resources collected for this project.
- Resource search and category filtering.
- Resource detail view and bookmark persistence in browser local storage.
- Reduced-motion support and responsive layouts.

## Run locally

```bash
npm install
npm run dev
```

Create a production build:

```bash
npm run build
npm run preview
```

## Product architecture

ForgeOS is being developed in three distinct layers:

1. **Discover** — catalogue resources with verified descriptions, links, licences, pricing and compatibility.
2. **Orchestrate** — turn a goal into an actionable plan or reusable workflow.
3. **Execute** — run supported integrations through authenticated APIs and background jobs.

A resource being listed does not mean ForgeOS can execute it. Execution will only be enabled after a real integration and its permissions are configured.

## Planned product areas

- Resource Library
- AI Studio
- Design Studio
- Film Studio
- Development Lab
- Startup Launchpad
- Projects and Workflows
- Knowledge Base and administration

## Next engineering milestones

1. Connect Supabase for authentication, database-backed resources, bookmarks and projects.
2. Add resource management and verification workflows.
3. Build project and task management with persistent data.
4. Add integration registry and secure server-side credential handling.
5. Implement workflow orchestration and supported AI provider integrations.
6. Add admin controls, audit logs, automated tests, deployment health checks and production monitoring.

## Environment

No API keys or service credentials are committed. Add environment variables through the deployment platform. Never expose provider secrets in browser code.
