# High-Signal Outreach

Write concise outreach that gives a busy recipient a real reason to respond.

**Use it when:** you have a real reason to contact someone and need one evidence-backed message—not a biography, compliment, or disguised ask.

**Returns:** one sendable message built around why this recipient, one contribution surface your evidence supports, why the fit is real, and one answerable ask.

Use it for founder emails, research and engineering roles, academic collaboration, referral requests, technical networking, and follow-ups.

## Actual user case

> Write a 60–110 word email to Dr. Rao about the Research Engineer role on her agent-evaluation team. The team needs dataset construction, evaluation design, and production feedback analysis. My proof: I built a LongMemEval evaluation pipeline and shipped retrieval feedback instrumentation. My actual intention is to apply, not ask for a generic research chat.

## What the skill returns

> **Subject: Research Engineer, Agent Evaluation**
>
> Hi Dr. Rao,
>
> I'm applying for the Research Engineer role on your agent-evaluation team. I can own the evaluation loop from benchmark construction through analysis of production failures. I built a LongMemEval evaluation pipeline and shipped retrieval feedback instrumentation, giving me experience turning system behavior into structured datasets and actionable evaluation signals.
>
> Does this background fit what you need for the role, and would a brief conversation make sense?
>
> Best,<br>
> Michelle

The message chooses one coherent ownership loop instead of repeating the entire job description, connects it to proof, states the real intention, and asks for the actual decision.

## A real project using the workflow

The [EchoMem Group outreach research pack](https://github.com/myfeng10/myfeng10/tree/main/case-studies/echomem-outreach-research) applies the same reasoning beyond one email:

- find a public pain signal
- score whether the workflow is real
- write down why now
- show one private-by-default product moment
- ask for one 3–5 person pilot

## Try it

```text
Use $write-high-signal-outreach to research this recipient, choose the one ownership loop my evidence supports best, and draft one sendable message. Recipient/source: […]. Real intention: […]. My proof: […]. Channel and length: […].
```

Give it the recipient, a verified source or context block, your real intention, one or two proofs, and the channel or length when they matter. If current facts need verification and browsing is available, the skill researches them; otherwise it asks for verified context rather than guessing.

## Install

```bash
npx skills add myfeng10/write-high-signal-outreach
```

Restart your agent, then invoke it with `$write-high-signal-outreach`.
