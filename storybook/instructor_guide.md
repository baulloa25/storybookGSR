
# 👩‍🏫 Instructor Guide: GitHub Storybook

**Audience:** Middle/High school beginners  
**Duration:** ~60 minutes  
**Group Size:** 5–8 per team (scale as needed)

## Learning Goals
- Understand clone / commit / push / pull
- Experience a friendly merge conflict & resolution
- Practice teamwork & communication

## Setup Options
1) **Central GitHub Repo:** Create a private/public repo named `storybook` and upload these files.  
   - Default branch: `main`
   - Add all students as collaborators, or share a classroom GitHub link.
2) **Offline Zip:** Hand out this folder. Have each team `git init` locally, then optionally connect to GitHub later.

## Timing (Suggested)
- 00:00–00:08 — Intro + Story theme
- 00:08–00:18 — Everyone clones the repo
- 00:18–00:35 — Add one sentence → commit → pull → push
- 00:35–00:50 — **Merge Conflict Game** (see script below)
- 00:50–01:00 — Read the story aloud + debrief

## Roles
- **Narrator:** Reads the current story to the team.
- **Scribe:** Types the team sentence.
- **Librarian:** Runs git commands with help.
- **Peacekeeper:** Helps resolve conflicts kindly.

## Conflict Script (Simple)
- Ask **two** students to edit the **same line** in `story.txt` at the same time.
- Student A: add "...found a golden key."
- Student B: add "...found a silver sword."
- Both commit and push. One push will succeed, one will fail.
- The second student runs `git pull origin main` to fetch, then opens `story.txt` and resolves.
- Encourage combining ideas into one awesome line.

## Safety & Kindness Rules
- PG content only.
- No deleting others' work—if it happens, use `git log` to show history and revert.

## Useful Commands (Instructor)
```bash
# Show history
git log --oneline

# See who changed what
git blame story.txt

# Undo last commit (keep changes staged)
git reset --soft HEAD~1

# Revert a bad commit by hash
git revert <hash>
```

## Wrap-Up Questions
- What is a commit message and why is it helpful?
- How did we decide conflicts fairly?
- What would be hard about writing a story with 100 people?
