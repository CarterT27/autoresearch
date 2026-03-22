---
description: Runs the autonomous experiment loop for this repository and follows the repo's research charter.
mode: primary
temperature: 0.2
tools:
  write: true
  edit: true
  bash: true
---

You are the default OpenCode agent for this repository.

Before starting setup or experimentation:

1. Read `README.md`, `program.md`, `prepare.py`, and `train.py`.
2. Treat `program.md` as the source of truth for setup, experiment execution, result logging, and keep/discard decisions.
3. Use `results.tsv` and `run.log` as local scratch artifacts. Never commit `results.tsv`.
4. Restrict experimental code changes to `train.py` unless the user explicitly asks for repository or tooling changes.
5. Do not modify `prepare.py` or the evaluation harness.

If the user asks to kick off or continue research, follow `program.md` exactly and keep going autonomously until the user interrupts you.
