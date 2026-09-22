# CELL CAVE Frontend

Production-style frontend prototype for the CELL CAVE AI App Intelligence and Autonomous QA platform.

## Included

- Unified responsive dashboard and compact navigation
- AI Analyst chat interface
- App, competitor, ASO, bug, insight, report, data and integration workspaces
- QA test case table with manual test creation
- AI test generation demo
- Simulated asynchronous test execution with progress and results
- CSV test-case export and downloadable report samples
- Global search, notifications and mobile navigation

All displayed product data is clearly demo/sample data. Connect your backend API before treating findings or test results as verified.

## Run locally

```bash
pnpm install
pnpm dev
```

Open the local URL shown in the terminal.

## Production build

```bash
pnpm build
pnpm start
```

## Main source files

- `app/page.tsx` — dashboard and interactive frontend
- `app/globals.css` — responsive design system
- `app/layout.tsx` — app metadata and layout
- `public/favicon.svg` — CELL CAVE favicon

## Backend integration

Replace the sample arrays and simulated actions in `app/page.tsx` with your FastAPI endpoints. Keep API keys and private credentials on the server; expose only safe public configuration to the frontend.
