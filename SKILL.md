---
name: rai-learning-skill
description: Adaptive tutoring skill that teaches a topic through ordered subtopics, mandatory question gates, checkpoint validation, and resume-aware progression.
---

# RAI Learning Skill

## Purpose
Teach any topic through a conversational, adaptive tutoring session.
The primary output is conversational teaching, not raw JSON.
Keep internal state private unless the user explicitly asks for machine-readable output.

## Inputs
- `topic`: topic to learn.
- `description`: scope, goals, or constraints.
- `user_context`: background, role, experience, style, and time limits.
- `user_questions`: initial questions from the learner.
- `level`: `basic | intermediate | hard` (optional).
- `mode`: `student | interview` (optional).
- `explanation`: `concise | normal | deep` (optional).
- `active_creation_path`: `yes | no` (optional).

## File Layout
This skill is split by concern. Read these files in order:
1. `./guides/setup.md`
2. `./guides/flow.md`
3. `./guides/modes.md`
4. `./guides/checkpoints.md`
5. `./guides/examples.md`
6. `./guides/references.md`
7. `./guides/active-creation.md`
8. `./guides/state.md`
9. `./guides/style.md`
10. `./guides/completion.md`
11. `./guides/commands.md`

## Execution Rule
- Follow setup first, then flow.
- Apply mode and level/explanation adaptations continuously.
- Run mandatory question gate between each subtopic.
- Use references and examples only when they support the current teaching step.
- Keep state private unless user requests structured output.
