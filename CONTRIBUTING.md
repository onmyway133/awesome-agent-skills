# Contributing

This repo is a curated list of Claude agent skills. Contributions are welcome, but every entry goes through a quick review to keep the collection tight and non-redundant.

## Before you start

Open an issue or a draft PR naming the skill before writing up the entry. This avoids duplicate submissions — check the table of contents in `README.md` first to see if something similar already exists.

## What qualifies

A skill can be added if it meets at least one of these:

- It's published by Anthropic (e.g. `anthropics/skills`) or ships as a first-party skill in an official Claude product or plugin.
- It comes from a repository with a high star count and visible signs of real usage (issues, forks, recent commits) — not a fresh repo with inflated or vanity stars.

The skill itself must also:

- Have a working `SKILL.md` with valid YAML frontmatter (`name`, `description`).
- Do one thing clearly, not bundle several unrelated instructions together.
- Still work — check it against a recent Claude Code release before submitting.

## One entry per repo, not per skill

Each entry represents a repository or publisher, not an individual skill. If a repo ships one skill or fifty, it still gets a single row — list a few representative skill names inline instead of a separate entry per skill.

## Where an entry goes

Entries are grouped into categories in `README.md` (Anthropic (Official), Databases & Data, Cloud & Infrastructure, AI/ML Platforms & APIs, Frontend/Mobile & Design, Auth & Identity, Testing & Code Quality, Security, Observability, Payments & Web3, Search & Web Data, Productivity & Collaboration, Agent Frameworks & Tooling, Developer Workflow, ...). Add a new category only if an entry doesn't fit any existing one.

Within a category, entries are sorted alphabetically by publisher/repo name.

Add a matching entry to the table of contents at the top of `README.md`, linking to the category's heading anchor.

## Writing an entry

Format:

```
- **[Publisher](link-to-repo-or-official-skills-page)** — one sentence on what the collection covers. Examples: `skill-a`, `skill-b`, `skill-c`. _(Source: org/repo, official or X★)_
```

- Description is factual and third person — no marketing language, and covers the collection as a whole, not one skill in it.
- Link to the publisher's repo root or official skills page, not a single skill's subfolder.
- The `Examples:` list is optional plain text — a few representative skill names, no links. Omit it if the repo only ships one skill (fold that into the description instead).
- Note the source: `official` for Anthropic/first-party skills, or the star count at time of submission for community repos.

## Style

Writing must be simple, concise, and factual — no buzzwords, no unverified claims about what a skill does.

## Submitting

Open a PR adding the entry. Mention where you found it and why it qualifies (official source, or the star count / evidence of adoption) so it can be reviewed.
