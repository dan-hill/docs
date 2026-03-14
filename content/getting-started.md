+++
title = "Getting Started"
description = "Cold-start checklist for the shared Hugo module chain."
date = 2026-03-10T08:20:00Z
draft = false
+++

If you are stepping into the stack cold, start here.

## MODULE CHAIN

```text
www/docs -> site-base -> ox
```

## FIRST CHECKS

1. confirm the current module version in each consumer
2. confirm there are no stale local replace directives
3. build both consumers locally before pushing
4. only then push the Pages-triggering branches

## WHY THIS ORDER EXISTS

The shared theme is the source of truth. If consumers drift, the sites start lying about what the system actually is.
