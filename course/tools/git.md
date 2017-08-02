---
permalink: /course/tools/git/
title: Tools | Git
---
# Git

[GitHub](https://github.com/) is a popular code repository hosting site that uses the [Git](https://git-scm.com/) version control system. [Git How To](https://githowto.com/) offers a simple guided tour that walks through the fundamentals of Git.

## Links

* Documentation: [Reference](https://git-scm.com/docs).

## Examples

* "Undo" the action of commit while leaving everything eles unchanged: `git reset --soft HEAD^`
* Skip the staging step to commit all changes: `git commit -a -m "Update files"`
* Show changes in `README.md` since the tip of `HEAD`: `git diff HEAD README.md`
