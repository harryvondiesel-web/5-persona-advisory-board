# 5 Persona Advisory Board

![5 Persona Advisory Board hero](assets/5-persona-advisory-board-hero.png)

One decision engine. Five strategic lenses. Three rounds of debate. One clear decision contract.

The 5 Persona Advisory Board stress-tests high-leverage decisions through Product Clarity, Risk and Capital, Scale and Systems, Offer Strength, and Future Self. Version 1.0 adds formal debate, score movement, anti-groupthink checks, risk vetoes, validation thresholds, kill criteria, and accountable follow-up.

The lenses are inspired by publicly documented business principles associated with Steve Jobs, Warren Buffett, Jeff Bezos, Alex Hormozi, and long-term future-self thinking. They are analytical frameworks—not celebrity simulations, endorsements, or affiliated advisers.

## What v1.0 Does

1. Interviews for decision-critical context.
2. Normalizes the real options.
3. Runs five independent opening positions.
4. Forces debate around the disagreements that could change the choice.
5. Rescores each option after debate.
6. Prevents credible ruin risk from being averaged away.
7. Produces a decision contract with a validation test, go threshold, kill criterion, owner, deadline, and review date.

## Modes

- **Quick:** concise five-lens review, central disagreement, and next test.
- **Standard:** three rounds, pre/post scoring, risk review, and decision contract.
- **Full:** deeper evidence research plus a reusable session record.

Standard is the default. Use Full only when the stakes or irreversibility justify it.

## The Five Lenses

- **Product Clarity** — focus, simplicity, quality, story, and memorability.
- **Risk and Capital** — downside, durability, incentives, economics, and margin of safety.
- **Scale and Systems** — customer value, mechanisms, repeatability, leverage, and delivery capacity.
- **Offer Strength** — demand, value, pricing, execution, and sales friction.
- **Future Self** — alignment, regret, identity, freedom, and opportunity cost.

## Quick Start

Portable skill key: `5-persona-advisory-board`.

Use:

```text
Use the 5 Persona Advisory Board in standard mode.

Decision: [exact choice]
Options: [real alternatives]
Context: [stage, audience, offer, evidence]
Economics: [price, margin, budget, capacity, conversion]
Constraints: [time, team, legal, technical, operational]
Success: [measurable outcome and deadline]
Current preference: [what you favor and why]
```

If material context is missing, the skill asks up to three focused questions before running the board.

## Install With an Agent

Give OpenClaw, Hermes, Codex, Claude Code, or another coding agent this instruction:

```text
Install the complete 5 Persona Advisory Board skill from:
https://github.com/harryvondiesel-web/5-persona-advisory-board

Use the canonical skill key: 5-persona-advisory-board.
Copy SKILL.md and the references directory.
Validate the YAML frontmatter and relative paths.
Start a fresh session after installation so the skill is re-indexed.
```

## Manual Installation

### Codex

```bash
mkdir -p ~/.codex/skills/5-persona-advisory-board/references
cp SKILL.md ~/.codex/skills/5-persona-advisory-board/SKILL.md
cp -R references/. ~/.codex/skills/5-persona-advisory-board/references/
```

### Hermes

```bash
mkdir -p ~/.hermes/skills/productivity/5-persona-advisory-board/references
cp SKILL.md ~/.hermes/skills/productivity/5-persona-advisory-board/SKILL.md
cp -R references/. ~/.hermes/skills/productivity/5-persona-advisory-board/references/
```

### Claude or ChatGPT

Paste the full contents of `SKILL.md` into a Project or custom instruction area. Start a fresh conversation after adding it.

### OpenClaw

Install the complete directory under the active agent workspace’s `skills/5-persona-advisory-board/` path, then start a fresh session.

## Decision Contract

Standard and Full sessions end with:

- verdict,
- decisive evidence and constraints,
- conditions,
- strongest minority objection,
- cheapest validation test,
- measurable go threshold,
- measurable kill criterion,
- owner and deadline,
- review date,
- next action,
- explicit “do not do.”

## Anti-Groupthink and Safety

Early unanimity triggers a steelman of the strongest rejected alternative. A credible legal, security, cash-flow, reputation, operational, or explicit-boundary risk cannot be averaged away by a popular vote.

The skill never claims to speak as a real person, never fabricates quotations or endorsements, and does not replace customer evidence or qualified professional advice.

## Compatibility

Version 1.0 is designed as one portable skill for:

- OpenClaw
- Hermes
- Codex
- Claude
- ChatGPT

Host behavior can change. Re-run the cases in [references/evals.json](references/evals.json) when validating a new platform version.

## Repository Policy

This repository is the single source of truth for the product. “Marketing Council” and “BVD Decision Room” are not separate products.

## License

MIT. See [LICENSE](LICENSE).

## Non-Affiliation

This project is not affiliated with, endorsed by, or connected to Steve Jobs’ estate, Warren Buffett, Jeff Bezos, Alex Hormozi, or any related company.
