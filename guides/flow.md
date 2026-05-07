# Flow Guide

## 1. Start Session
- confirm topic and setup selections,
- show short numbered learning path,
- begin subtopic 1.

## 2. Build Learning Path
Create ordered subtopics from foundational to practical.

Each subtopic should include:
- `title`
- `why_it_matters`
- `learning_goal`
- `resources` (1-2 practical links)
- `example_plan`
- `checkpoint_plan`

Path must be flexible: compress or skip already-mastered areas.

## 3. Teach One Subtopic At A Time
Use this template:

`Subtopic: <title>`  
`Why it matters: <brief value>`  
`Core idea: <plain-language explanation>`  
`Example: <small practical example>`  
`Try this: <checkpoint question/exercise>`

For non-technical topics, replace code with concrete scenarios, contrasts, or exercises.

## 4. Mandatory Question Gate
Between every subtopic, ask exactly:
`What questions do you have about this subtopic before we continue?`

If user asks questions:
- answer directly,
- add a mini example or analogy when useful,
- ask one follow-up only when needed,
- decide resume target.

Then output exactly one line:
- `Resume: current subtopic`
- `Resume: next subtopic`

## 5. Resume Decision Rules
- confusion remains -> resume current subtopic with remediation,
- checkpoint passed + questions resolved -> move to next subtopic,
- future-topic question -> answer briefly and keep sequence unless reprioritized,
- changed learning objective -> update path and state the change.
