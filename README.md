# Unbox Me

**A Codex skill for reopening creative work that converged too early.**

AI is good at making the first plausible direction look finished. Unbox Me interrupts that pattern. It helps identify the assumption holding a design in place, test dissatisfaction with concrete contrasts, and open structurally different directions before more polish makes the current branch harder to leave.

它用于对抗 AI 在设计和创意工作中过早收敛的倾向：当方案“没错但平庸”、头脑风暴只是同一想法的变体，或团队正在局部优化一条可能错误的路径时，先重新打开问题空间，再决定往哪里收敛。

## What it does

1. Separates explicit constraints from hidden assumptions.
2. Uses small diagnostic probes when “something feels wrong” is hard to explain.
3. Breaks one assumption in three structural ways: **delete**, **reverse**, and **replace**.
4. Escalates from detail to component, system, objective, and finally the problem frame.
5. Stops once a genuinely new direction is selected, then hands it back to normal implementation work.

Unbox Me is not a prompt for producing a longer list of ideas. It is a process for discovering when many ideas still belong to the same branch.

## Example prompts

| Situation | Prompt |
| --- | --- |
| Generic product UI | `This dashboard is polished but generic. Use $unbox-me before changing the visuals.` |
| Patch-heavy architecture | `Use $unbox-me to check whether our queues and caches are optimizing the wrong architecture.` |
| Forgettable campaign | `The campaign is professional but forgettable. Use $unbox-me on the creative direction.` |
| Predictable story | `This premise keeps becoming a standard thriller. Use $unbox-me without adding random twists.` |
| Category-clone product | `We are building another habit tracker. Use $unbox-me before we write the roadmap.` |
| Obvious article structure | `The argument is coherent but unsurprising. Use $unbox-me before drafting.` |

See [the detailed use cases](unbox-me/references/use-cases.md) for the assumptions and structural breaks behind each example.

## Install

Copy the [`unbox-me`](unbox-me) directory into your Codex skills directory:

```text
~/.codex/skills/unbox-me/
```

Restart Codex if the skill does not appear immediately. Invoke it explicitly with `$unbox-me`, or let Codex select it when a creative or design task shows signs of premature convergence.

## Repository layout

```text
unbox-me/
├── README.md
└── unbox-me/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    └── references/
        └── use-cases.md
```
