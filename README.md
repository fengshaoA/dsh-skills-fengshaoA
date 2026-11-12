# dsh-skills-fengshaoA

Agent skills for [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness), installable via [skills.sh](https://skills.sh).

Author: **风少 (fengshaoA)**

## Skills

| Skill | What it does |
|---|---|
| [`decision-council`](skills/decision-council/SKILL.md) | Structured deliberation for consequential or irreversible decisions. 30 portable mechanisms distilled from Chinese, Western and global staff institutions, a six-step council process, and a three-tier safety gate. |

## Install

```sh
npx skills add fengshaoA/dsh-skills-fengshaoA
```

Or one skill only:

```sh
npx skills add fengshaoA/dsh-skills-fengshaoA -s decision-council
```

## decision-council

Most bad decisions do not fail for lack of information. They fail because nobody in the process was allowed to say no.

This skill reduces real staff institutions — the Tang send-back review, the dual-key draft-and-approve, the tribune's veto, mission-type command, net assessment, scenario planning, red teams — into **30 actions you can run today**, then wraps them in a six-step process: frame → grade the facts → seat a heterogeneous council → independent testimony and cross-examination → premortem and red team → weighted convergence with an eight-point audit.

It refuses to be a celebrity oracle. No "Confucius says". Each seat is an **institutionalised way of doubting**, not a persona.

### Safety gate

Three questions before anything convenes:

- **L1 — immediate crisis.** Self-harm or suicidal thinking: stop the deliberation, ask directly, give the hotline. Explicitly forbidden to run a cost-benefit analysis on staying alive.
- **L2 — hard refusal.** Crimes, evading regulators, harming a specific person, rigging a case to deceive a third party.
- **L3 — restricted mode.** Life-and-death, medical, legal decisions that are not emergencies: **do not refuse.** Refusing pushes the person back into isolation. Instead, restrict the scope — map the options, elicit what the person values, generate the questions for their doctor or lawyer — and never predict survival or cure rates, never decide for them whether to treat, never convert a life into a cost-benefit ratio.

The L3 tier is the least common design. Most safety policies refuse anything touching life and death; the result is that the people who most need help get turned away.

### Provenance

The 30 mechanisms trace back to a full lineage index of 178 entries across Chinese, Western and global advisory institutions. Each entry in `[1]`–`[30]` carries its source URL and confidence level, so a reader can spot-check any claim without leaving the skill file. The selection rationale — what was kept, what was cut, and why — is in [`SELECTION.md`](SELECTION.md).

## License

Apache-2.0
