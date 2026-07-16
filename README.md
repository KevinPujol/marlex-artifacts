# Marlex — Shared Artifacts

Public, browsable HTML deliverables for the Marlex Salesforce programme, served via GitHub Pages.

**One folder per artifact.** Each folder contains an `index.html` so it gets a clean URL
(`…/<artifact-folder>/`). The repo-root `index.html` is a landing page linking to each artifact.

## Artifacts

| Folder | Artifact |
|---|---|
| `tr-rebuild-decision-record/` | TargetRecruit Rebuild — Decision Record (assembled, client-safe) |

## Publishing

GitHub Pages serves the `main` branch root. Pushing an updated `index.html` into an artifact
folder redeploys it automatically within ~1 minute.

> Only scrubbed, client-safe HTML belongs here — this repo is public. Raw internal pages
> (named people, org IDs, partner accounts, internal governance IDs) stay in the private
> working repo and must never be pushed here.
