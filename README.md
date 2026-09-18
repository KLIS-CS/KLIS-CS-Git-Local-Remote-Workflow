# Checkpoint 4 — Local ↔ Remote Mental Model

## Goal

Show that you understand how a local Git repository connects to a GitHub remote repository and can choose the correct command for the direction of data flow.

## Start the exercise

[![Copy Exercise](https://img.shields.io/badge/COPY%20EXERCISE-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=KLIS-CS-Git-Local-Remote-Workflow&owner=%40me&name=cp4-local-remote-workflow&description=Checkpoint+4:+Local+and+Remote+Git+Workflow&visibility=public)

Keep the copied repository **Public** so the KLIS-CS mother repository can read the trusted CP4 automatic grader output.

After the copy is created:

1. In your copied repository, click **Code** and copy the HTTPS clone URL.
2. Clone your copied repository to your computer.
3. Inspect the repository with `git status`, `git branch`, and `git remote -v`.
4. Create the required `cp4-YOUR-GITHUB-USERNAME` branch locally.
5. Complete only `submission.md`, commit your work, and push the branch.
6. Open a Pull Request from your checkpoint branch to `main` and leave it open for grading.
7. Check the automatically created **CP4 — Score** Issue for your score and feedback.

> **Do not go to Actions and do not run a workflow manually.** Your Git push and Pull Request automatically start the grader.

## Required branch

```text
cp4-YOUR-GITHUB-USERNAME
```

## Challenge

Work from a local clone. Before changing anything, inspect the repository with:

```bash
git status
git branch
git remote -v
```

Create the required checkpoint branch locally, edit only `submission.md`, commit, and push the branch.

Your submission must include commands for both starting routes:

### Route A — GitHub first

```text
GitHub repository → local computer
```

### Route B — Local first

```text
local folder → Git repository → connect to GitHub remote
```

You must also explain `clone`, `push`, `pull`, and the meaning of `origin`.

Open a Pull Request from the checkpoint branch to `main` and leave it open for grading.

## Scoring

- **60 points** — automatic Git/GitHub evidence and command checks
- **40 points** — teacher review of correctness and conceptual understanding

Your copied repository runs the automatic grader and maintains a **CP4 — Score** Issue.

## Submit for teacher grading

[![Submit CP4](https://img.shields.io/badge/SUBMIT%20CP4-%E2%86%92-0969da?style=for-the-badge&logo=github)](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow/issues/new?template=cp4-submission.yml)

The teacher grades from the **KLIS-CS mother repository** using:

```text
/manual-grade
Commands: 0/15
Local/remote model: 0/10
Data flow: 0/10
Reflection: 0/5

Feedback:
Write concise feedback here.
```

After the teacher grade is published, the student's own **CP4 — Score** Issue pulls the `/40` teacher score and shows the **Final score /100**.

```text
Student repository
→ automatic /60
→ Submit CP4
→ mother repository /manual-grade /40
→ teacher grade published
→ student's CP4 — Score updates
→ Final score /100
```

The score syncs automatically after local grading and checks again about once per hour for a published teacher grade. **No manual Actions run is required.**

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| CP2 | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| **CP4 — You are here** | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
