# Checkpoint 4 — Local ↔ Remote Mental Model

## Goal

Show that you understand how a local Git repository connects to a GitHub remote repository and can choose the correct command for the direction of data flow.

## Start the exercise

Copy this checkpoint into your own GitHub account:

[![Copy Exercise](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=KLIS-CS-Git-Local-Remote-Workflow&owner=%40me&name=cp4-local-remote-workflow&description=Checkpoint+4:+Local+and+Remote+Git+Workflow&visibility=private)

After the copy is created:

1. Open **Actions**.
2. Select **Start Exercise**.
3. Choose **Run workflow**.
4. Read the Exercise Issue that GitHub Actions creates for you.
5. Clone your copied repository to your computer and complete the checkpoint locally.

> The source repository must be enabled as a GitHub **Template repository** for the Copy Exercise button to work.

## Required Branch

```text
cp4-YOUR-GITHUB-USERNAME
```

## Challenge

Work from a local clone of this repository. Before making changes, inspect the repository with:

```bash
git status
git branch
git remote -v
```

Create the required checkpoint branch locally, edit only `submission.md`, commit, and push the branch.

Your submission must include commands for both repository-starting routes:

### Route A — GitHub first

```text
GitHub repository → local computer
```

### Route B — Local first

```text
local folder → Git repository → connect to GitHub remote
```

You must also explain `clone`, `push`, `pull`, and the meaning of `origin`.

Then open a Pull Request from the checkpoint branch to `main` and leave it open for grading.

## Scoring

- **60 points** — automatic Git/GitHub evidence and command checks
- **40 points** — teacher review of correctness and conceptual understanding

When the required Pull Request is open, the grader posts the live score and a fixed **Teacher grading** template directly in that PR.

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| CP2 | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| **CP4 — You are here** | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
