# Commonly used Git Commands

| Command                                     | Description                                                                 |
| ------------------------------------------- | --------------------------------------------------------------------------- |
| git add -a                                  | Stage all changes                                                           |
| git add .                                   | Stage new files and modifications, without deletions                        |
| git add -u                                  | Stage modifications and deletions, without new files                        |
| git branch                                  | List all local branches                                                     |
| git branch -a                               | List all local and remote branches                                          |
| git branch `<branch-name>`                  | Create local branch `<branch-name>`                                         |
| git branch -d `<branch-name>`               | Delete local branch `<branch-name>`                                         |
| git branch -m `<old-branch>` `<new-branch>` | Rename `<old-branch>` to `<new-branch>`                                     |
| git checkout `<branch-name>`                | Switch to branch `<branch-name>`                                            |
| git checkout -b `<branch-name>`             | Create local branch `<branch-name>` and switch to it                        |
| git checkout -- `<branch-name>`             | Discard changes to `<branch-name>`                                          |
| git commit -m `<msg>`                       | Move files from staging area to the local repository with the given message |
| git commit -a -m `<msg>`                    | Add modified files and commit them to the local repository                  |
| git log                                     | View information about previous commits                                     |
| git merge `<branch-name>`                   | Merge `<branch-name>` into current branch                                   |
| git remote -v                               | Show URLs of remote repositories                                            |
| git reset `[file-name]`                     | Remove `[file-name]` from staging area                                      |
| git reset --soft HEAD^                      | Undo the last commit in the current branch                                  |
| git status                                  | Displays state of the working directory and the staging area                |
