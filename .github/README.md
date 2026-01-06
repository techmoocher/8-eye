# Personal AI Prompt Workflows

Central place for my system prompts and AI workflows across academic tasks, daily life, and software development. The goal is to keep prompts consistent, auditable, and easy to reuse.

## Contents

- Academic: IELTS writing examiner prompt (see [Academic/IELTS-Writing.md](Academic/IELTS-Writing.md)).
- Daily life: everyday helpers (to add).
- Software development: coding/workflow assistants (to add).

## Repository layout

- [Academic](Academic): subject-specific system prompts.
- [README.md](README.md): overview and contribution guide.
- [TODO.md](TODO.md): upcoming improvements and prompt additions.

## How to use these prompts

- Copy the relevant system prompt into your chat tool; keep roles/guardrails intact.
- Replace any placeholders with your context (task, constraints, desired output style).
- For evaluations, paste your draft first, then ask for critique; avoid asking for full answers before you write.
- Save refinements back into the prompt file so improvements are tracked.

## Conventions when adding prompts

- Start with: role, mission, tone, audience, guardrails, and workflow.
- Keep instructions specific and testable; prefer bullets over prose.
- Call out forbidden behaviors explicitly (e.g., no full answers before a draft is given).
- If a prompt targets a scoring rubric, cite the criteria briefly.
- Use ASCII characters unless the task requires otherwise.

## Template for new prompts

Use this scaffold when creating a new prompt file:

```markdown
# <Prompt name>

## Role
- <Who the assistant is>
- Tone and mission

## Audience
- <Who will use this>

## Guardrails
- <Forbidden behaviors>

## Workflow
1) <Step-by-step flow>

## Response skeleton
- <Sections the model should return>

## Extras
- <Checklists, vocab lists, evaluation rubrics, etc.>
```

## Maintenance tips

- Version prompts in small, reviewable edits so changes are easy to diff.
- Test prompts with a short trial conversation before committing.
- Note what worked/failed in the prompt file or commit message for traceability.

## TODO

Learn more at [TODO.md](TODO.md).
