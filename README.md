# Windows runner smoke check

This repository contains a minimal check that a GitHub-hosted Windows runner can start.

## Scope

- The workflow records basic runner metadata only.
- It does not download, build, execute, or publish an application.
- Do not upload private source packages, credentials, or application binaries here.

A real application build requires a separately authorized and verified source handoff, a reproducible build recipe, and a build receipt.

A successful smoke run proves runner availability only. It is not an application build or release acceptance.
