# Achievement Sandbox

A safe repo to practice GitHub workflows (PRs, merges, branch protection) without impacting production projects.

## Purpose

This repository serves as a sandbox environment for:
- Practicing pull request workflows
- Testing merge strategies
- Experimenting with branch protection rules
- Learning GitHub collaboration patterns in a safe space

## Workflow Used

- Feature branches for all changes
- Pull requests required for merging to `main`
- Code review process before merge
- Clean commit history

## Branch Protection Rules

The `main` branch is protected with the following rules:
- ✅ Require pull request before merging
- ✅ Require 1 approval before merge
- ✅ Dismiss stale pull request approvals when new commits are pushed
- ⏸️ Status checks: Not configured (can be added when CI is set up)
- ⏸️ Require branches to be up to date: Not enforced (can be enabled with CI)

---

**Note:** This repo was intentionally created with one initial "YOLO merge" to demonstrate the before/after of implementing branch protection rules.