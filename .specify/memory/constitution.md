<!--
Sync Impact Report
- Version change: unresolved scaffold -> 1.0.0
- Modified principles: none; all five principles are established from project
  documentation.
- Added sections: Project Constraints; Development Workflow.
- Removed sections: none.
- Follow-up TODOs: Confirm the original ratification date and replace
  TODO(RATIFICATION_DATE).
-->

# projext-x Constitution

## Core Principles

### I. Clear Purpose and Scope
Every piece of work MUST identify the user or project problem it addresses, its
acceptance criteria, and its scope before implementation begins. Work that
cannot be connected to the approved project objectives MUST be deferred or
explicitly approved as a scope change. This keeps a course project focused and
prevents effort from drifting into undocumented features.

### II. Small, Reviewable Changes
Changes MUST be made in short-lived branches and organized into small,
single-purpose commits or pull requests. Each pull request MUST explain the
problem, summarize the changes, identify documentation impact, and record
validation evidence. Small changes make review, rollback, and shared ownership
practical.

### III. Evidence-Based Quality
Implementation work MUST include the relevant tests, checks, or documented
manual validation for the behavior changed. A task is not complete while known
blocking quality issues remain unresolved. When the project stack introduces
automated checks, they MUST run before merge and their results MUST be
reviewable. Quality claims must be supported by evidence rather than
assumptions.

### IV. Documentation and Decision Traceability
Changes affecting behavior, architecture, setup, data flow, scope, or team
workflow MUST update the relevant documentation in `docs/` or the root
README. Significant decisions and their rationale MUST be recorded in the
decision log or an equivalent project record. Documentation is part of the
deliverable, not optional cleanup.

### V. Shared Ownership and Constructive Collaboration
The team MUST maintain a respectful, inclusive, and transparent working
environment. Ownership, dependencies, blockers, and remaining work MUST be
visible to the team. Every change merged to `main` MUST receive review from at
least one teammate, and contributors MUST address review feedback before
merging. Responsibilities may be distributed, but quality and delivery remain
shared obligations.

## Project Constraints

The project is developed as a course deliverable and MUST preserve a usable
main branch. The selected technology stack, architecture, and measurable
success criteria MUST be documented before they become governing assumptions.
GitHub issues SHOULD track features, bugs, technical debt, documentation work,
and research; each issue SHOULD state an objective, acceptance criteria,
dependencies, and ownership. No direct merge to `main` is permitted without a
pull request and review.

## Development Workflow

Work MUST progress through planning, execution, review, and delivery:

- Planning MUST define the iteration goal, tasks, priority, ownership, and
  acceptance criteria.
- Execution MUST begin from the latest `main` branch and use a short-lived
  feature, fix, documentation, or maintenance branch.
- Review MUST verify acceptance criteria, relevant validation, readability,
  documentation impact, and resolution of comments.
- Delivery MUST leave `main` in a usable state and record follow-up work as
  issues or documented TODOs.

Blockers MUST be communicated as soon as they are known. Major scope or design
changes MUST be discussed by the team and documented before implementation
continues.

## Governance

This constitution is the governing standard for project process and quality.
When another practice conflicts with it, the conflict MUST be resolved in
favor of this document or explicitly amended before the conflicting practice is
adopted.

Amendments MUST be proposed in a pull request that explains the motivation,
scope, affected principles, compatibility impact, and any migration or
follow-up work. At least one teammate MUST review the amendment, and the
constitution MUST pass the same documentation and validation expectations as
other changes. The amendment becomes effective only after the pull request is
approved and merged.

The version follows semantic versioning. MAJOR increments represent
backward-incompatible removals or redefinitions of governance. MINOR
increments represent new principles or materially expanded requirements.
PATCH increments represent clarifications, wording, or other non-semantic
refinements. The version and last-amended date MUST be updated whenever an
amendment is merged.

Every pull request review MUST consider compliance with this constitution.
Iteration reviews and retrospectives SHOULD identify recurring compliance
gaps, unresolved TODOs, and proposed amendments. The team MUST resolve
governance violations before delivery or document an approved exception and
its expiration or follow-up owner.

**Version**: 1.0.0 | **Ratified**: TODO(RATIFICATION_DATE): confirm original
adoption date | **Last Amended**: 2026-09-03
