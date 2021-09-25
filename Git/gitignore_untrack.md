## Gitignore Tracked Files

I wanted to untrack some files in a repository. I added the necessary lines in gitignore and did the following to untrack already tracked files:

```
git rm -r --cached
git add .
git commit -m "untrack files"
```

Source:
[1](https://www.git-tower.com/learn/git/faq/ignore-tracked-files-in-git/) 