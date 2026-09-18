# Teacher Grading — Checkpoint 4

Final score: **60 automatic + 40 teacher-reviewed = 100**.

## Manual Rubric — 40 points

| Category | Full-credit evidence | Points |
|---|---|---:|
| Command correctness | Commands are syntactically and contextually correct | 15 |
| Local/remote model | Clearly distinguishes local repository, remote repository, remote-tracking state, and `origin` | 10 |
| Data-flow understanding | Correctly explains clone, push, fetch, and pull, including fetch vs pull | 10 |
| Reflection | Uses state-inspection commands before proposing changes | 5 |
| **Total** |  | **40** |

## Entering the Teacher Grade

Grade in the **mother-repository CP4 submission Issue**:

```text
/manual-grade
Commands: 0/15
Local/remote model: 0/10
Data flow: 0/10
Reflection: 0/5

Feedback:
Write concise feedback here.
```

The newest valid grading comment by `hbycwyh2008` is used. The older short form remains accepted:

```text
/manual-grade 38
```

## Recommended teacher check

Look for a state-first debugging model rather than memorized commands. A strong response should distinguish:

- working tree vs local commit history;
- local branches vs remote-tracking branches;
- `origin` as a configurable remote name;
- `fetch` as updating remote-tracking information;
- `pull` as fetch plus integration;
- review as a step that occurs before merge.
