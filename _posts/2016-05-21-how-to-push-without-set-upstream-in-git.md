---
layout: post
---

Tiered of typing `git branch --set-upstream awesome-branch origin/awesome-branch`?

Change your git setting to use the current branch name:

```bash
git config --global push.default current
```

And you can just use

```bash
git push
```

*Thanks to [zamith](http://stackoverflow.com/users/830229/zamith) on [stackoverflow.com](http://stackoverflow.com/a/22933955/747044).*
