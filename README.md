# TechPortal

A responsive internal IT portal built with React, TypeScript, and Vite.

## Develop

Use Node.js 24 and npm 11. From this directory:

```sh
npm ci
npm run dev -- --host 0.0.0.0 --port 5173 --strictPort
```

## Validate

```sh
npm run lint
npm run build
```

`npm run preview -- --host 0.0.0.0 --port 4173 --strictPort` serves the production build.

## Included

- Dashboard with request totals.
- Create, resolve, and reopen requests, persisted in this browser's local storage.
- Searchable knowledge base and article reader.
- Responsive layouts for mobile and desktop.

This is a local prototype. Requests are not sent to an IT team. Authentication, shared storage, ticket routing, and service monitoring require a backend before production use. Do not enter sensitive information. No environment variables or external services are needed for local development.
