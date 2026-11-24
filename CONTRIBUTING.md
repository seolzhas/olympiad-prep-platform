# Contributing Guide

Thank you for helping students prepare for olympiads! You can contribute code, new problems, translations, bug reports or ideas.

By taking part you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to help

| You can… | How |
| --- | --- |
| Report a bug | Open an issue with steps to reproduce, device and browser |
| Suggest a feature | Open an issue with the label `idea` |
| Add a problem or lesson | Add a Markdown file to `content/` (see format below) |
| Translate | Add Russian or Kazakh versions in `content/ru/` or `content/kk/` |
| Write code | Pick an issue labelled `good first issue` |

## Workflow

1. **Fork** this repository and clone your fork.
2. **Create a branch**: `git checkout -b fix/short-description`.
3. **Make your change** and test it locally.
4. **Commit** with a clear message: `git commit -m "Add geometry problem set 1"`.
5. **Push** to your fork and open a **pull request** to `main`.
6. Link the issue in the PR description, for example `Closes #12`.
7. A maintainer reviews the PR. Please answer comments; we merge after approval and passing checks.

## Content format

Each problem is a Markdown file:

```markdown
---
topic: number-theory
level: 1        # 1 = beginner, 3 = advanced
language: en
---
## Problem
...
## Hint
...
## Solution
Step-by-step solution.
```

Only add problems you wrote yourself or that are free to reuse. Always credit the source. New content is published under CC BY-SA 4.0.

## Code style

- Keep pages light: they must work on slow internet and old phones.
- No ads, trackers or third-party analytics.
- Do not collect any new personal data without discussing it in an issue first (see [PRIVACY.md](PRIVACY.md)).

## Questions

Open an issue with the label `question`. We are happy to help first-time contributors.
