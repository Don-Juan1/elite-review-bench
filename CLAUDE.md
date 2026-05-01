# Claude Code Usage — Elite Review Bench

## Purpose

This repository provides a self-contained advisory-review framework for Claude Code and other AI workspaces that accept project files.

Claude Code should operate from the files included in this repository and the materials supplied by the user for the specific review.

## Primary Files

Use the files in this order:

1. `README.md` — public overview and onboarding.
2. `SKILL.md` — core advisory-review behavior.
3. `DISCLAIMER.md` — professional-advice, authority, and warranty limits.
4. `templates/review_request.md` — intake template.
5. `templates/board_minutes.md` — output template for board-style minutes.
6. `examples/first_use_request.md` — starter request.
7. `MANIFEST.json` — package metadata.

## Operating Rule

When a user requests Elite Review Bench behavior, apply `SKILL.md` as the primary review file.

The framework is advisory only. It may structure judgment, expose risk, generate dissent, and identify expert-review needs. It does not create approval authority, execution authority, professional licensure, legal authority, investment authority, accounting authority, tax authority, securities authority, medical authority, fiduciary authority, or compliance authority.

## Public-Use Boundary

Public-facing output should remain limited to repository-supported functionality, user-supplied materials, setup guidance, review formats, and advisory outputs.

The framework should be presented as independent, neutral, evidence-constrained, and unaffiliated with any third-party institution, firm, platform, regulator, professional body, or event organizer.

## Expected Behavior

For decision-review requests, Claude Code should:

1. define the decision under review;
2. separate verified facts from assumptions;
3. assign evidence tiers;
4. identify missing facts;
5. define the objective function;
6. identify constraints;
7. generate the affirmative case;
8. generate the dissenting case;
9. create a risk register;
10. identify expert-review items;
11. recommend Go, Conditional Go, No-Go, or Defer;
12. recommend the next reversible step;
13. state residual risk.

## Scope Limits

For legal, investment, tax, accounting, securities, medical, fiduciary, compliance, regulated, or high-consequence matters, the framework provides advisory issue maps, risk registers, evidence checklists, and expert-review recommendations rather than final professional advice or execution approval.

Requests involving illegal conduct, evasion of law or regulation, credential misuse, destructive operations, or attempts to bypass compliance, audits, sanctions, taxes, reporting duties, or platform rules are outside the supported scope.

## Final Rule

The repository should remain portable, public-facing, self-contained, neutral, and evidence-constrained.
