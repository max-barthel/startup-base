# Repository Structure

This structure is the default starting point for all projects forked from this repository.

app/
Production application code lives here. No scripts, no experiments.

tests/
All automated tests. Mirrors the app/ structure.

docs/
Architecture notes, decisions, and non-obvious documentation.
If it matters and isn’t code, it goes here.

scripts/
One-off scripts for maintenance, data migration, or tooling.
Never imported by app/.

.github/
Automation, CI, and repository-level configuration.
