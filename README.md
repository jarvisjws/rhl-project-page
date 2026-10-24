# RHL project homepage — private release preparation

Static HTML/CSS/JavaScript intended for GitHub Pages. This directory is a **local review build**, not a published project or a claim that all desired historical camera recordings exist.

## Preview

Open `index.html` directly in a browser, or use the companion local preview launcher. The bundled content projection supports offline file viewing; the same directory can be served over HTTP for GitHub Pages. No external font, analytics, framework, login or backend is required.

## Content ownership

The canonical manuscript, paper-design owner, experiment notes and selected-asset projection remain in the AgentSys project. `assets/cases.json`, `assets/learning.json`, `assets/media-sources.json` and the compressed media are website derivatives. Do not edit success totals here independently of the experiment owners. No original archive is replaced.

## Media interpretation

- Original recording: captured during the original run; remuxing/re-encoding is logged.
- Recorded-state reconstruction: measured positions, orientations and joints restored without new task-solving actions. These are not independent physical replays.
- State snapshots / event samples: explicitly discrete states; missing temporal state is not interpolated into an invented continuous execution.
- A Twin restored recovery start can differ from the selected policy failure. The page displays the distinction.
- Media and simulation timing exclude model inference, diagnosis and planning latency unless explicitly documented otherwise.

## Publication

Use a separate approved public repository. Copy only the reviewed static publish package, not the internal project, source archives, remote paths or credentials. Public author/citation details and any Paper/Code links must be agreed and available before adding them. The companion deployment example is manual-only and is not activated by this local build.

The current site does not directly fetch the private experiment dataset. Review `DELIVERY.md` and `assets/media-sources.json` for the actual prepared scope and unresolved media gaps before publication.

## Repository status — 24 October 2026

This is the private preparation repository `jarvisjws/rhl-project-page`.
GitHub Pages is enabled at https://jarvisjws.github.io/rhl-project-page/.
The repository remains private, but the review website is publicly accessible.
Author details are pending; no Paper link is supplied.
The owner requested this hosted version for review; this is not a final research release.
`github-pages.workflow.example.yml` is an inactive deployment example, outside
`.github/workflows`; Pages currently deploys from the main branch root using GitHub’s branch publishing.

The initial website is derived from the reviewed r2 package. No private research
Git history, experiment archives, credentials or runtime paths are included.
Changes to scientific facts must be reconciled with the original research owners.
