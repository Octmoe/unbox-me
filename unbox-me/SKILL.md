---
name: unbox-me
description: Reopen a creative problem, design, plan, architecture, narrative, or solution that has converged too early on its first plausible answer. Use when work feels generic, safe, over-polished, locally optimized, or vaguely wrong; when brainstorming keeps producing variants of one idea; or before implementation when structural alternatives should be explored.
---

# Unbox Me

Reopen the design space from the leaves upward. Do not optimize a branch that may be wrong.

## Rules

- Treat only explicit non-negotiables as fixed.
- Separate known facts and constraints from assumptions introduced by the user or agent.
- Treat inferred problems as hypotheses, never facts.
- Prefer structural change over patches, refinements, renaming, or cosmetic variation.
- Keep each round concise: use at most 5 diagnostic probes or exactly 3 structural breaks.
- Do not implement or reconverge while the user is still diagnosing the direction, unless explicitly asked.
- Do not mistake a longer list for a wider design space. Variants that preserve the same structure belong to one branch.

## Workflow

### 1. Frame the current branch

Summarize the current answer or direction in one sentence.

List:

- **Fixed**: explicit constraints and non-negotiables.
- **Assumed**: beliefs, defaults, and inferred requirements that currently hold the branch in place.

Keep this framing short. If the user's dissatisfaction is vague, prefer concrete probes over asking them to explain an abstract feeling.

### 2. Choose a starting node

If the user identifies the problem, start there.

If the dissatisfaction is vague:

1. Select 3–5 likely problematic leaf nodes from different branches.
2. For each node, state the hypothesis in one line.
3. Apply one small, contrasting change as a diagnostic probe.
4. Ask the user to mark each probe as **closer**, **farther**, or **irrelevant**.
5. Start from the node that produces the strongest useful reaction.

When an artifact exists, show minimal side-by-side changes. When no artifact exists, state a provisional default branch, then probe against it.

### 3. Break the current boundary

At the selected node:

1. Identify the assumption holding the branch in place.
2. Offer three mutually distinct breaks:
   - **Delete** the assumption or element.
   - **Reverse** its role, goal, sequence, or relationship.
   - **Replace** it with a different structure.
3. For each break, state what it opens and its main cost.
4. Recommend one break based on the user's signals, not generic best practice.
5. Ask whether the design boundary has moved enough.

Do not preserve the old branch through extra rules, resources, exceptions, or surface styling.

### 4. Escalate when needed

If the user is still dissatisfied, move up exactly one level:

**detail → component → system → objective → problem frame**

At the new level, repeat the break process. Do not keep generating variants at a level the user has rejected.

### 5. Stop and hand off

Stop divergent exploration when the user selects a meaningfully new direction.

Summarize:

- **Preserved**
- **Broken**
- **Newly opened**
- **Unresolved**

Then hand the selected direction back to normal design, planning, or implementation work.

## Use the examples

Read [references/use-cases.md](references/use-cases.md) when the user asks for examples, the domain is unfamiliar, or contrasting probes are hard to formulate. Adapt the reasoning pattern; do not copy the example outputs as templates.
