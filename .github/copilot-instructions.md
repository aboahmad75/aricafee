---
description: "Workspace instructions for the AriCafee EAF representative website-delivery pilot."
---

# AriCafee workspace instructions

This repository is a non-production EAF experimental sandbox.

## Current source and stack
- `index.html` is the website source under test.
- Stack: static HTML, Tailwind CDN, Lucide, and browser JavaScript.
- React migration and framework introduction are out of scope unless explicitly authorized.

## Operating boundaries
- Make changes only on the authorized representative-pilot branch.
- Never modify `main` directly.
- Preserve `eaf/aricafee-pilot-01` as frozen historical evidence.
- Do not deploy or modify production infrastructure.
- Do not change DNS, backend, database, authentication, billing, or Paperclip configuration.
- Do not fabricate unknown business information.

## Pilot behavior
- Inspect the current website before changing it.
- Distinguish functional defects, placeholders, UX/design weaknesses, and unknown real-world data.
- Keep changes bounded to the approved Pilot task.
- Preserve bilingual English/Arabic behavior and the language toggle.
- Verification is performed through the approved independent browser-QA path.

