+++
title = "Architecture Map"
description = "Quick map of the publishing stack and what each repo is responsible for."
date = 2026-03-11T10:05:00Z
draft = false
+++

The stack is split on purpose.

## REPOS

- **ox** — canonical shared presentation layer
- **site-base** — lightweight module bridge / propagation surface
- **www** — public signal board
- **docs** — manual and reference layer

## RULE OF THUMB

If a change should affect both sites, it probably belongs in `ox`.
If a change is only about public content or docs content, keep it local.
