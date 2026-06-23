# Monorepo Skills

Skills for standing up and maintaining a [Forward Impact](https://forwardimpact.team)-style monorepo — the cross-cutting setup that composes the Co-Aligned and Kata packs.

## Install

With [APM](https://microsoft.github.io/apm/):

```bash
apm install forwardimpact/monorepo-skills
```

With [npx skills](https://github.com/vercel-labs/skills):

```bash
npx skills add forwardimpact/monorepo-skills
```

## Available Skills

| Skill | Description |
| --- | --- |
| **monorepo-setup** | Stand up a new MONOREPO.md-compliant repository end to end — bootstrap the skeleton, install the skill packs, run coaligned-setup then kata-setup, and fill the seams neither owns (root package.json, directory tree, agent profiles, CI, remote creation). Use when creating a Forward Impact-style repo from nothing, or when one exists but the cross-cutting wiring is missing. |
