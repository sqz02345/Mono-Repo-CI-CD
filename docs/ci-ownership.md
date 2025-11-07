# CI Ownership & Triggers (Phase 1)
- apps/api/** → api
- apps/web/** → web
- libs/common/** → api + web

Events:
- pull_request → validate (lint/tests/scan)
- push to main → build snapshot (no promote)
- workflow_dispatch → manual promote
