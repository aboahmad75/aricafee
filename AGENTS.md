# AriCafee EAF Pilot Instructions

This repository is being used as a non-production EAF experimental sandbox.

## Current source
- `index.html` is the website under test.
- Technology baseline: static HTML + Tailwind CDN + Lucide + browser JavaScript.
- Do not migrate to React or introduce a framework unless explicitly authorized.

## Pilot boundaries
- Work only within the active AriCafee Representative Pilot envelope.
- Do not modify `main` directly.
- Do not modify, reset, merge, or reuse the historical branch `eaf/aricafee-pilot-01`.
- Do not deploy to production.
- Do not change DNS, backend, database, authentication, billing, or Paperclip configuration.
- Do not invent unknown real business data.

## Verification
Website changes must be verified independently through the approved QA path, including 1440 px, 768 px, and 390 px viewports plus LTR/RTL behavior.
