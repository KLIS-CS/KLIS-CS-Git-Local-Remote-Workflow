# Checkpoint 4 — Local ↔ Remote Mental Model

## Goal

Show that you understand what lives locally, what lives on GitHub, and which Git command moves or synchronizes information between them.

CP4 focuses on this model:

```text
working tree
↕
staging area
↕
local commits
↕ push / fetch / pull
remote repository (origin)
```

You will still use the complete branch → PR → review → merge workflow, but the main assessment focus is your **local/remote mental model**.

## Start the exercise

[![Copy Exercise](https://img.shields.io/badge/COPY%20EXERCISE-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=KLIS-CS-Git-Local-Remote-Workflow&owner=%40me&name=cp4-local-remote-workflow&description=Checkpoint+4:+Local+and+Remote+Git+Workflow&visibility=public)

Keep the copied repository **Public**.

After the copy is created:

1. Copy the HTTPS clone URL.
2. Clone the repository locally.
3. Inspect state with `git status`, `git branch -vv`, and `git remote -v`.
4. Create `cp4-YOUR-GITHUB-USERNAME` locally.
5. Complete only `submission.md`, commit, and push the branch.
6. Open a Pull Request to `main`.
7. Request review from another GitHub user.
8. Receive an **APPROVED** review and then merge.
9. Check the original **Exercise Issue** for the score.

Do **not** manually run Actions.

## Required branch

```text
cp4-YOUR-GITHUB-USERNAME
```

## Challenge

Your submission must demonstrate both starting routes:

### Route A — GitHub first

```text
GitHub repository
→ git clone
→ local repository
```

### Route B — Local first

```text
local folder
→ git init
→ git remote add origin ...
→ connected local repository
```

You must also explain:

- `origin`;
- `push`;
- `fetch`;
- `pull`;
- the difference between `fetch` and `pull`;
- how to inspect branch and remote state before acting.

After opening the PR, get a human **APPROVED** review before merge. Deleting the feature branch after merge is allowed because the grader uses the PR's stored head SHA and review history.

## Scoring

- **60 points** — automatic Git/GitHub evidence and command checks
- **40 points** — teacher review of correctness and conceptual understanding

Automatic evidence includes the required branch identity, commit evidence, PR target, command answers, conceptual answers, approval-before-merge, and final merge.

## Submit for teacher grading

Submit only after review and merge:

[![Submit CP4](https://img.shields.io/badge/SUBMIT%20CP4-%E2%86%92-0969da?style=for-the-badge&logo=github)](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow/issues/new?template=cp4-submission.yml)

Repository URL and GitHub username are detected automatically.

Teacher grading:

```text
/manual-grade
Commands: 0/15
Local/remote model: 0/10
Data flow: 0/10
Reflection: 0/5

Feedback:
Write concise feedback here.
```

The teacher score synchronizes back to the original **Exercise Issue**.

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| CP2 | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| **CP4 — You are here** | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
