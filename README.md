# Denis Bondarenko

**Next.js & Supabase Developer**

I build service portals and dashboards with Next.js, TypeScript, Supabase and PostgreSQL. My work covers authentication, database access controls, request workflows and API integrations.

[Telegram](https://t.me/BDenisD) · [LinkedIn](https://www.linkedin.com/in/denis-bondarenko-a94491388)

My technical background includes installation, commissioning and troubleshooting of video surveillance, access control and other building systems. I bring the same approach to software: reproduce a problem, trace it through the interface, API and database, then verify the fix against the original case.

## Selected projects

### Client Portal Dashboard

A portfolio application for reporting and processing issues with building and site systems.

Clients submit requests and follow their progress. Staff assign an engineer, start work and record a resolution. The client can see the completed work and request history.

PostgreSQL enforces client ownership, staff permissions and valid status transitions. Saves detect conflicting updates, and history records are protected from direct editing.

CI runs lint, TypeScript, a production build, SQL access tests and a browser workflow against an isolated local Supabase backend. The browser test follows a request from submission to closure and checks the result in the client's account and the database.

[Source and setup](https://github.com/bondarenkodenis0907-web/client-portal-dashboard) · [Live demo](https://client-portal-dashboard-one.vercel.app) · [CI checks](https://github.com/bondarenkodenis0907-web/client-portal-dashboard/actions)

### TradePilot AI

A private application combining Bybit exchange data, a trade journal, strategy research and Telegram notifications. Exchange access is read-only; background research runs separately from the web interface.

The public showcase contains interface screenshots, architecture notes and implementation decisions. Source code, account data and executable tests remain private.

[Public showcase](https://github.com/bondarenkodenis0907-web/tradepilot-ai-showcase)

## Work I take on

- Next.js dashboards, account screens and request workflows.
- Supabase authentication, session handling and PostgreSQL access controls.
- PostgreSQL queries, API integrations and reproducible bug fixes.

To discuss a task, message me on [Telegram](https://t.me/BDenisD). Include the current behavior, expected result and steps to reproduce the issue. For a new feature, describe its users and the workflow they need.
