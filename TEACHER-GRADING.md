# Teacher Grading — Checkpoint 4

Final score: **60 automatic + 40 teacher-reviewed = 100**.

## Manual Rubric — 40 points

| Category | Full-credit evidence | Points |
|---|---|---:|
| Command correctness | Commands are syntactically and contextually correct | 15 |
| Local/remote model | Clearly distinguishes local repository, remote repository, and `origin` | 10 |
| Data-flow understanding | Correctly explains clone, push, and pull directions | 10 |
| Reflection | Gives a sensible diagnostic strategy rather than blindly repeating commands | 5 |
| **Total** |  | **40** |

## Entering the Teacher Grade

Every student Pull Request automatically receives a **Teacher grading** block from the bot. Use the fixed template shown there:

```text
/manual-grade
Commands: 0/15
Local/remote model: 0/10
Data flow: 0/10
Reflection: 0/5

Feedback:
Write concise feedback here.
```

Copy it into a **new PR comment**, replace the scores, and add feedback. The workflow calculates the teacher subtotal automatically and combines it with the automatic 60 points.

Example:

```text
/manual-grade
Commands: 14/15
Local/remote model: 9/10
Data flow: 10/10
Reflection: 5/5

Feedback:
Strong mental model. Be more precise about when `git pull` changes the working tree and when you should inspect state first.
```

The newest valid grading comment by `hbycwyh2008` is used. To revise a grade, post a new completed template.

The older short form remains accepted for compatibility:

```text
/manual-grade 38
```

## Recommended teacher check

Look for reasoning, not command memorization. A strong response should distinguish local state from remote state, explain `origin` as a remote name rather than a special Git keyword, and use diagnostic commands such as `git status`, `git branch`, and `git remote -v` before proposing a fix.
