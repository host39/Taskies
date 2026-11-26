# Tasks

This is the current order of work. The step is the order of work, and the issue number is the original GitHub issue number.

| Step | Issue | Title | Notes |
|---|---|---|---|
| 1 | #1 | Initial project scaffolding for cross-platform task manager | Starts from the RustInit template; shared core in Rust |
| 2 | #10 | Work fully offline without any backend (IndexedDB on web, SQLite on mobile and desktop) | Linux is the minimum desktop platform |
| 3 | #11 | Backup and restore as a ZIP (readable JSON + attachments) with optional encryption | |
| 4 | #12 | Robust filtering, sorting, grouping, saved filters and search | |
| 5 | #2 | Polished UI and UX inspired by Todoist (web, desktop) and Todoist / Tasks.org (mobile) | Ongoing focus across all steps |
| 6 | #8 | Configurable defaults for new tasks (like Tasks.org task defaults) | |
| 7 | #6 | Recurring tasks with the same behaviour as Tasks.org | |
| 8 | #7 | Robust notification and reminder system for phone and desktop apps | |
| 9 | #3 | Calendar view for tasks (week, month and year) | |
| 10 | #9 | Android home screen widgets | |
| 11 | #4 | Support multiple sync backends and multiple instances of each (Taskies API, CalDAV, EteSync, DAVx⁵, DecSync CC, WebDAV) | |
| 12 | #5 | Build our own Taskies backend API in Rust with optional E2EE, PostgreSQL/SQLite, attachments and MCP | Blocked by host39/RustAuth |
| 13 | #15 | Optional Authelia sign-in (OIDC, plus forward auth for the web) | After #5 |
| 14 | #13 | MCP support for all backends and features (server MCP + desktop fallback) | After #5 |
| 15 | #14 | In-app AI helper with bring-your-own provider (Anthropic, OpenAI, self-hosted) | Uses the same tools as #13 |
