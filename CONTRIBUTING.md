# Contributing Guide

This document defines the team workflow for the Project Course repository.

## Team principles

- Keep the main branch clean and releasable.
- Work in small, reviewable pieces.
- Document decisions and changes.
- Communicate blockers early.
- Prefer evidence over assumptions.

## Git workflow

### Branches

Use the following naming conventions:

- `feature/<short-description>` for new work
- `fix/<short-description>` for bug fixes
- `docs/<short-description>` for documentation updates
- `chore/<short-description>` for maintenance tasks

Examples:

- `feature/user-login`
- `fix/api-timeout`
- `docs/project-setup`

### Commit expectations

- Keep commits atomic and meaningful.
- Write clear commit messages in the present tense.
- Prefer one topic per commit.

Examples:

- `Add user login form validation`
- `Fix API timeout handling`
- `Document sprint planning workflow`

### Pull requests

Before merging to `main`:

1. Create a branch from the latest `main`.
2. Implement the work.
3. Run the relevant checks/tests.
4. Ensure the code is readable and documented.
5. Open a pull request.
6. Request review from at least one teammate.
7. Resolve comments before merging.

### Merge policy

- Do not merge directly to `main` without a pull request.
- Do not merge without a review.
- Prefer squash merges for small, focused changes.

## Issue workflow

Every task should be linked to an issue when possible.

Use issues for:

- features,
- bugs,
- technical debt,
- documentation tasks,
- research or investigation work.

## Documentation expectations

Whenever a change affects:

- system behavior,
- architecture,
- setup steps,
- data flow,
- team workflow,

update the relevant documentation in the `docs/` folder or the root README.

## Communication expectations

- Post blockers in the team communication channel as soon as they arise.
- Share updates during the regular meeting cadence.
- Keep comments constructive and specific.

## Definition of done

A task is considered done when:

- the implementation or artifact is complete,
- tests or checks are passing,
- documentation is updated if required,
- the pull request is reviewed and merged,
- the result is visible in the current project state.
