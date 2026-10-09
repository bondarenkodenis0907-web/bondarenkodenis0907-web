# Denis Bondarenko

I work with Next.js, TypeScript and Supabase: sign-in flows, dashboards, PostgreSQL data and API integrations.

I moved into development from technical systems and troubleshooting. My current projects involve the same kind of work: trace a problem through the interface, API and database, then check the fix against the case that failed.

## Projects

### Client Portal Dashboard

A portal for service requests at buildings and sites. Users manage a profile, submit an issue and view their request history.

Data access is enforced with PostgreSQL ownership policies. The public repository includes SQL tests that check access from two different users, plus CI for code checks, a production build and database tests. The staff workflow for assigning and closing requests is still to be built.

[Source and setup](https://github.com/bondarenkodenis0907-web/client-portal-dashboard) · [Live demo](https://client-portal-dashboard-one.vercel.app)

### TradePilot AI

A private application for reviewing exchange data, keeping a trade journal and testing research ideas. It combines Bybit data, Supabase/PostgreSQL, background research and Telegram notifications. Exchange access is read-only.

The public showcase explains the system boundaries and a few implementation decisions, with screenshots of the Russian-language interface. Source code and account data remain private.

[TradePilot showcase](https://github.com/bondarenkodenis0907-web/tradepilot-ai-showcase)

## Work I take on

- Supabase sign-in, session and row-access problems.
- Next.js dashboards, profile screens and request forms.
- PostgreSQL queries, API integrations and fixes that can be reproduced and checked.

For a scoped task, the useful starting point is the current behavior, the expected result and a way to reproduce the problem.
