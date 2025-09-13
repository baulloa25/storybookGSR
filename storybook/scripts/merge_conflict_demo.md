
# 🧪 Merge Conflict Demo (Instructor Script)

1) Choose two volunteers. Have both edit the SAME line in `story.txt`.
2) Both run:
```bash
git add story.txt
git commit -m "My version of the key/sword line"
git push origin main
```
3) The second pusher will get a rejection. Have them run:
```bash
git pull origin main
```
4) Open the conflicted file, discuss the `<<<<<<<` and `>>>>>>>` markers.
5) Combine ideas into one line, delete markers, then:
```bash
git add story.txt
git commit -m "Resolve conflict by combining ideas"
git push origin main
```
