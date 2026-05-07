# RAI Learning Skill

Adaptive tutoring skill for AI agents.  
It teaches one subtopic at a time, inserts mandatory question gates, and resumes based on learner understanding.

## Install

From this repository:

```bash
npx skills add https://github.com/<your-org-or-user>/<your-repo> --skill rai-learning-skill
```

Install whole repo skill set:

```bash
npx skills add https://github.com/<your-org-or-user>/<your-repo>
```

## What It Includes

- `SKILL.md`: main orchestrator
- `guides/setup.md`: setup collection and normalization
- `guides/flow.md`: step-by-step teaching flow
- `guides/modes.md`: student/interview mode patterns
- `guides/checkpoints.md`: checkpoint rules
- `guides/examples.md`: simple/complex/real-world example contracts
- `guides/references.md`: sourcing and recency policy
- `guides/active-creation.md`: hands-on file/code creation policy
- `guides/state.md`: internal state contract
- `guides/style.md`: response style
- `guides/completion.md`: completion criteria
- `guides/commands.md`: command and slash-alias contract

## Commands

- `/start`
- `/next`
- `/pause`
- `/resume`
- `/skip`
- `/restart`
- `/stop`
- `/quit`
- `/level easy|medium|hard`

Non-slashed equivalents are also supported.

## License

MIT
