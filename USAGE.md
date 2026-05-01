# Usage Guide

Elite Review Bench is intentionally simple: the Markdown files are the product. They can be uploaded, referenced, or copied into AI workspaces that support project files or structured instruction documents.

Use it when a decision deserves a cleaner room: facts separated from assumptions, risks made visible, dissent placed on the table, and the next responsible step stated plainly.

## Best Use Cases

Elite Review Bench is strongest for:

- board-style second opinions;
- go / no-go analysis;
- dissent memos;
- risk registers;
- evidence-tier review;
- expert-review threshold detection;
- pre-mortem analysis;
- execution-risk review.

## Recommended File Order

For most workflows, start here:

1. `README.md` — public overview.
2. `USAGE.md` — practical usage guide.
3. `SKILL.md` — primary review framework.
4. `CLAUDE.md` — Claude Code usage guide.
5. `templates/review_request.md` — structured intake template.
6. `templates/board_minutes.md` — board-style output template.
7. `examples/first_use_request.md` — starter request.

## Claude Code

Place the repository files in the workspace. Use `CLAUDE.md` for Claude Code setup and `SKILL.md` as the primary review framework.

Suggested request:

```text
Use Elite Review Bench. Review the following decision using the repository files. Separate facts from assumptions, apply evidence tiers, include dissent, identify expert-review items, and recommend Go, Conditional Go, No-Go, or Defer.

Decision:
[insert decision]
```

## Claude Projects

For a Claude Project, upload or reference:

- `SKILL.md`
- `CLAUDE.md`
- `USAGE.md`
- the relevant template from `templates/`

Then ask for the format you want: advisory decision review, dissent memo, board-style minutes, or risk register.

## ChatGPT Projects

For a ChatGPT Project or similar workspace, upload or paste:

- `SKILL.md` as the main review framework;
- `USAGE.md` for workflow context;
- `templates/review_request.md` when structured intake is useful;
- `templates/board_minutes.md` when board-style output is needed.

Suggested request:

```text
Use Elite Review Bench. Produce a concise board-level go / no-go review with evidence posture, key risks, dissent, expert-review needs, and the next best reversible step.

Decision:
[insert decision]
```

## Manual Copy-Paste Workflow

For simple use without a project workspace:

1. Open `SKILL.md`.
2. Copy the relevant review format.
3. Paste it into the AI workspace.
4. Add the decision, known facts, assumptions, constraints, and desired outcome.
5. Request an advisory review.

Use `templates/review_request.md` when the decision is complex, evidence-sensitive, or high-consequence.

## Community Courtesy Context

This courtesy edition is adapted from a broader AI-assisted decision-review concept and formatted for Claude Code use by finance professionals, operators, and builders. It is shared for attendees, panelists, hosts, and peers connected with **Welcome: Vibe Coding for Finance — Weekly Workshop**, including Welcome: Contemporary and related participants.

This context is descriptive only. Elite Review Bench is independent and is not affiliated with, sponsored by, endorsed by, or authorized by any event organizer, platform, firm, institution, regulator, professional body, or AI provider.

## Limitations

Elite Review Bench is advisory decision support only. It does not provide legal, investment, tax, accounting, securities, medical, fiduciary, compliance, governance, or other regulated professional advice.

For high-consequence decisions, use the framework to structure the issue map, risk register, evidence checklist, and expert-review items. Final action should be reviewed by qualified professionals where appropriate.
