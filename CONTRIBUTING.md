# Contributing

Thanks for helping improve this roadmap.

## Ground rules

1. **Evidence over opinion.** Claims about latency, cost, or quality should cite a
   benchmark, experiment (`experiments/`), or a linked source.
2. **Opinionated is fine; dogmatic is not.** Decision records state a recommendation
   *and* the conditions that would flip it.
3. **One concept per file.** Keep modules focused; move depth into `notes/`.
4. **Templates are contracts.** If you change a template, update every doc that uses it
   and note it in the PR.

## Repository conventions

### Naming

- Courses: `courses/NN-kebab-title/` (zero-padded two digits)
- Labs: `labs/NN-kebab-title/`
- Experiments: `experiments/EXP-NNN-kebab-title/`
- Notes: `notes/<topic>/<kebab-title>.md`
- Decision records: `decisions/<topic-vs-topic>.md`

### Course structure

Each course directory contains:

```
README.md          — overview, objectives, prerequisites, module index
NN-<topic>.md      — numbered modules (01..06 pattern)
exercises/         — practice tasks with increasing difficulty
examples/          — worked examples / reference snippets
checkpoint.md      — assessment questions and pass criteria
```

### Lab structure

Each lab directory contains:

```
README.md          — scenario, objectives, deliverables, rubric
<supporting files> — data samples, diagrams, starter code as needed
```

Use `templates/lab-template.md` when creating a new lab.

### Writing style

- Use GitHub-flavored markdown; headings start at `#`.
- Prefer tables for comparisons and checklists.
- Show concrete examples (requests, configs, metrics) over abstract prose.
- Define an acronym on first use.
- No trailing whitespace; one blank line between sections.

### Diagrams

Put source files (`.mmd`, `.drawio`, `.svg`) in `assets/diagrams/` and reference them
relative to the doc that uses them.

## Adding content

1. Fork and create a branch: `git checkout -b add-course-17-xyz`.
2. Follow the structure conventions above.
3. Link new content from `ROADMAP.md`, `KNOWLEDGE-MAP.md`, and `PROGRESS.md`.
4. Open a PR using the checklist below.

### PR checklist

- [ ] Files follow naming conventions
- [ ] Links validated (no dead relative links)
- [ ] Templates used where applicable
- [ ] Roadmap / knowledge map / progress updated
- [ ] Spelling and markdown lint clean

## Corrections

For factual corrections, open an issue with:

- The file and section
- The incorrect statement
- The correct statement with a source
