# Monorepo Skills

Skills that stand up and maintain a [Forward Impact](https://forwardimpact.team)-style monorepo. They are the cross-cutting setup that composes the Jidoka and Kata packs.

## Install

With [APM](https://microsoft.github.io/apm/):

```bash
apm install forwardimpact/monorepo-skills
```

## Available Skills

| Skill | Description |
| --- | --- |
| **monorepo-setup** | Stand up a new Monorepo-standard repository end to end. Bootstrap the skeleton, install the skill packs, run jidoka-setup then kata-setup, and fill the seams neither owns (root package.json, directory tree, agent profiles, CI, remote creation). Use when you create a Forward Impact-style repo from nothing, or when one exists but the cross-cutting wiring is missing. |
