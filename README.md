# S-TRACE

## Repository structure

```text
project/
├── README.md
├── docs/
├── data/
│   └── samples/
└── src/
```

- `docs/` contains project documentation, such as the overview, requirements, architecture notes, and plans.
- `data/samples/` contains sample or test data that is safe to keep in the repository.
- `src/` contains the project source code.

## Naming conventions

- Use lowercase names with hyphens between words: `system-overview.md`, `test-plan.md`, and `aurora-1-telemetry.csv`.
- Use descriptive names that explain the contents. Prefer `requirements.md` over `data2.md` or `final-final.md`.
- Keep stable documents under a consistent name as they evolve. Git preserves their revision history, so a new filename for every edit is usually unnecessary.
- Use the existing folder purpose to show what kind of file something is instead of adding unnecessary prefixes or suffixes.
