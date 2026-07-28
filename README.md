# High-Signal Outreach

Write concise outreach that gives a busy recipient a real reason to respond.

This skill researches the recipient, identifies the decision they can make, chooses one ownership loop the sender can credibly support, and drafts one sendable message with one low-friction ask.

It is built for founder emails, research and engineering roles, academic collaboration, referral requests, technical networking, and follow-ups.

## Install

```bash
npx skills add myfeng10/write-high-signal-outreach
```

Then restart your agent.

## Example prompt

```text
Use $write-high-signal-outreach to research this recipient and draft one concise message for the role. Choose the single ownership loop my evidence supports best.
```

## What it protects against

- explaining the recipient's own work back to them
- hiding a job request behind vague technical curiosity
- repeating an entire job description as a contribution claim
- listing credentials without connecting them to one deliverable
- asking for an undefined call instead of an answerable next step
- laundering an inference into a verified fact

## Output

The skill returns one copy-ready message first. It uses one argument:

1. why this recipient
2. what the sender can credibly contribute or achieve
3. why the collaboration fits
4. one direct, low-friction ask

## Actual before / after

The same research-engineer outreach scenario was run in isolated Codex sessions and judged blindly.

- Before: `9/10` — strong evidence and intent, but the contribution claim covered too many ownership surfaces.
- After: `10/10` — selected one retrieval-evaluation loop, tied it to one proof, and made the employment intent explicit.

See the [public evaluation note](https://github.com/myfeng10/myfeng10/blob/main/skills-evaluation.md#full-scorecard) for the frozen-suite method and full scorecard.
