# Git & GitHub

## What did I learn by practicing?

As someone who has already used Git and GitHub, diving deeper into the documentation was a great experience. It revealed that there is so much more to the platform than just `git clone`, `git checkout`, `git pull`, and `git push` (the basics we all use). Git is a comprehensive tool that is easy for developers to grasp. Furthermore, I feel we often fail to fully utilize the potential of GitHub, a platform that has steadily grown over the years to become the most popular among developers. Exploring it in depth gave me a new appreciation for just how good it is, from its easy repository management and automation capabilities (CI/CD) to its power to bring communities together and its ability to integrate tools such as Codex for Pull Request reviews.

## Some commands I learned:

* `git init`
* `git status`
* `git branch` / `git branch <name>` (create a new branch)
* `git clone <repository>`
* `git add <file>` / `git add .`
* `git commit -a -m "feature: new filter"`
* `git push` / `git push origin <branch>`
* `git pull` / `git pull origin <branch>`
* `git checkout <branch>` / `git checkout <file>` (restore a file) / `git checkout -b <branch>` (create and switch to a new branch) / `git checkout <tag>`
* `git mv <file1> <directory/file1>` (move a file) / `git mv <file123> <file_123>` (rename a file)
* `git rm <file>`
* `git reset --hard`
* `git log`
* `git stash` / `git stash pop` / `git stash list`
* `git tag`
* `git merge`
* `git branch -d <branch>`
* `git fetch` / `git fetch --all`
* `git remote -v`
* `git submodule` / `git submodule add <repository>`
* `git show` / `git show <tag>`
* `git diff <fileA> <fileB>`
* `git shortlog`
* `git clean`
* `git gc`
* `git fsck`
* `git reflog`
* `git archive --format=zip --output=<files.zip>`

### Bonus

It isn't a command, but it is very important: `.gitignore`.

It defines files and directories that Git should ignore, preventing them from being tracked and committed to the repository.
