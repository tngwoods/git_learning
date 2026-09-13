# Repository Guidelines

## Project Structure & Module Organization

This is a small, documentation-focused repository. The root currently contains:

- `github-learning-plan.md` — the primary Chinese-language learning record, organized by learning stages and practice tasks.
- `AGENTS.md` — contributor and automation guidance.

There are no source-code modules, test directories, generated assets, or build-output directories at present. Keep new learning notes and related documentation at the repository root unless the collection grows enough to justify a `docs/` hierarchy.

## Build, Test, and Development Commands

No build or runtime command is configured. Before contributing, inspect the working tree with:

```bash
git status
```

For documentation-only changes, review the rendered Markdown in your editor or on GitHub. If a Markdown linter is added later, run the project-defined lint command and document it here; do not commit generated output.

## Coding Style & Naming Conventions

Write clear Markdown with one title (`#`) per document and logically nested headings. Use fenced code blocks for commands, backticks for inline commands and paths, and short bullet points for enumerated guidance. Preserve the existing Chinese language and instructional tone when extending `github-learning-plan.md`. Use lowercase kebab-case for new Markdown filenames (for example, `branching-exercises.md`), and keep heading text concise and descriptive.

## Testing Guidelines

There is no automated test framework or coverage requirement. Validate documentation changes by checking heading order, list rendering, code-span formatting, and command spelling. Confirm that referenced paths and links are valid, and read the rendered page once for clarity before opening a pull request.

## Commit & Pull Request Guidelines

No local commit history is available to establish an existing convention. Use concise, imperative Conventional Commit-style subjects where practical, such as `docs: add branching exercises` or `docs: clarify pull request workflow`. Keep each commit focused.

Pull requests should explain the learning or documentation change, identify affected files, and link any related issue or exercise. Include screenshots only when a rendered-layout change is important. Request review after checking the rendered Markdown and resolving all spelling or link issues.

## Security & Configuration Tips

Do not commit GitHub tokens, SSH private keys, personal access tokens, or other secrets. Use placeholders in examples and store real credentials only in local credential helpers or GitHub-managed secrets.
