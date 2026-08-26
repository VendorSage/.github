# .github

Org-wide defaults.

Anything in `.github/ISSUE_TEMPLATE/` here is served to every repository in the organisation
that has no `.github/ISSUE_TEMPLATE/` of its own. A repository with its own templates ignores
these entirely.

## Why this repository is public

It has to be. GitHub only serves default community health files from a **public** `.github`
repository — a private one is silently ignored, with no warning and no template. That was
verified rather than assumed.

Because it is public, keep everything here generic. No repository names, no file paths, no
project or initiative names, no internal URLs. If a template needs that detail, it belongs in
the repository it applies to, not here.

## What is here

Only **Task** — the one issue type filed in a code repository. Everything else is specific to
a single repository and lives there.
