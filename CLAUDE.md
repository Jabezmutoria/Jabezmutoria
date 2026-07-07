# About this repository

This repo stores my Claude configuration files. It is not an app —
there is nothing to build, run, or test here.

## Layout
- `global/CLAUDE.md` — the master copy of my personal instructions.
  Copy it to `~/.claude/CLAUDE.md` on any machine I work from.
- `CLAUDE.md` (this file) — rules for editing this repo only.

## Rules for this repo
- When my instructions change, edit `global/CLAUDE.md` here AND copy
  it to `~/.claude/CLAUDE.md`, then commit and push. (Reason: the
  home-folder copy is what Claude actually reads; this repo is the
  backup that survives.)
- Keep every file under 200 lines, and never state the same rule in
  two files.
- Project-specific rules (stack, commands, gotchas) don't belong
  here — they go in each project's own CLAUDE.md.
