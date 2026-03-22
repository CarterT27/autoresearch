# autoresearch

OpenCode reads this file automatically for project-level instructions.

## Project map

- `prepare.py`: fixed data prep, tokenizer, dataloader, and evaluation harness. Read it for context but do not modify it during experiments.
- `train.py`: the only code file that should change during autonomous experiments.
- `program.md`: the human-maintained experiment charter. Read it before starting setup or an experiment loop.
- `results.tsv` and `run.log`: local experiment artifacts. Keep `results.tsv` untracked.

## Working rules

- Read `README.md`, `program.md`, `prepare.py`, and `train.py` before starting a research run.
- During experiments, restrict code edits to `train.py` unless the user explicitly asks for repository or tooling changes.
- Do not modify the evaluation harness in `prepare.py`.
- Do not create random Markdown files unless the user explicitly asks for them.
- Do not mention that you are an agent in commit messages.
