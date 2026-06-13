# Skills

A collection of agent skills for AI coding agents (Claude Code, OpenCode, Cursor).

## First Principles

A two-phase adversarial interview skill that strips a problem down to bedrock before any code is written.

### What it does

**Phase 1** — Attacks your problem statement. Exposes inherited assumptions, fake constraints, and solutions disguised as problems.

**Phase 2** — Attacks your solution. Drills every branch of the design tree until nothing is ambiguous.

**Output** — Saves `constitution.md` and `spec.md` ready for immediate use with [Spec-Kit](https://github.com/github/spec-kit)'s `/speckit.constitution` and `/speckit.specify` commands.

### Usage
/first-principles

### Install

```bash
npx skills add https://github.com/fusunyu/skills --skill first-principles
```

### Part of a larger workflow
/first-principles → /speckit.constitution → /speckit.specify → /speckit.plan → /speckit.implement

## License

MIT
