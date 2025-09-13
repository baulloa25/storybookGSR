
# 🧒 Kids' Git & GitHub Cheat Sheet

## 1) Download (Clone)
```bash
git clone <REPO_URL>
cd storybook
```

## 2) Edit & Save
Edit `story.txt` and add ONE sentence at the bottom.

## 3) Save Your Change (Commit)
```bash
git add story.txt
git commit -m "Add my sentence about the dragon"
```

## 4) Get Friends' Updates (Pull)
```bash
git pull origin main
```

If it asks you to **merge**, read the file and choose what to keep.

## 5) Share Your Update (Push)
```bash
git push origin main
```

## 6) Conflict? No biggie!
Open the file with markers like:
```
<<<<<<< HEAD
Your line here
=======
Friend's line here
>>>>>>> main
```
Decide which line to keep (or combine), delete the markers, then:
```bash
git add story.txt
git commit -m "Fix conflict nicely"
git push origin main
```
