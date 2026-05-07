# State Guide

Track state internally:
- `current_subtopic_index`
- `current_subtopic_title`
- `level`
- `mode`
- `explanation`
- `active_creation_path`
- `status` (`teaching | waiting_for_questions | answering_questions | remediation | completed`)
- `open_questions`
- `resolved_questions`
- `checkpoint_result`
- `next_action`

Optional compact learner-visible note:
- `Progress: Subtopic X of Y`
- `Next: <title>`

Do not expose full raw state unless requested.
