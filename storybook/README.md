
# 🐉 GitHub Storybook (Kid-Friendly Workshop)

Welcome to **GitHub Storybook** — a playful way to learn Git & GitHub by writing a shared story together.

## What you'll learn
- Clone (download) a repo
- Add & commit a change (save your page)
- Push (share to GitHub)
- Pull (get friends' updates)
- Fix a merge conflict (when two people edit the same line)

## Quick Start (Kids)
> Ask your instructor for the GitHub repo link (or USB/zip).

1) Open **Terminal** (Mac/Linux) or **PowerShell** (Windows).
2) Type these commands (paste the real repo URL if you have one):

```bash
git clone <REPO_URL>
cd storybook
code .    # optional if VS Code is installed
```

3) Open `story.txt`, add ONE sentence at the bottom.
4) Save and run:

```bash
git add story.txt
git commit -m "Add my sentence to the story"
git pull origin main   # get the latest from friends
git push origin main   # share your change
```

If you see a **merge conflict**, open the file with the `<<<<<<<` and `>>>>>>>` markers, decide how to combine lines, then:

```bash
git add story.txt
git commit -m "Resolve merge conflict by combining ideas"
git push origin main
```

## Folder Guide
- `story.txt` — the shared story (everyone edits this)
- `kids_cheat_sheet.md` — quick reference for commands
- `scripts/merge_conflict_demo.md` — instructor: force a fun conflict
- `instructor_guide.md` — full plan, timing, roles, tips

Have fun! ✨
