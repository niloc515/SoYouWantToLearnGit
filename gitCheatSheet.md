# Cheat sheet

Theres a lot of git cheat sheets out there, some are even pretty good (see [otherCheatSheets.md](./otherChearSheets.md)) but I wanted to make my own with the stuff that I find myself using pretty regularly so I know where to go when I need some git help.

| Task                                                | How to                                               | Example                                                                     |
|-----------------------------------------------------|------------------------------------------------------|-----------------------------------------------------------------------------|
|Make a new repository                                | `git init`                                           |`git init`                                                                   |
|Clone a repository                                   | `git clone [URL]`                                    |`git clone https://github.com/Marak/faker.js.git`                            |
|Check on the staging area                            | `git status`                                         | `git status`                                                                |
|Add an item to the staging area                      | `git add [NAME OF FILE]`                             | `git add index.html`                                                        |
|Add all items with changes to the staging area       | `git add .`                                          | `git add .`                                                                 |
|Add all items of a specific type to the staging area | `git add *.[FILE EXTENSION]`                         | `git add *.js`                                                              |
|Remove a file from the staging area                  | `git reset HEAD -- [PATH TO FILE]`                   | `git reset HEAD -- index.html`                                              |
|Create a new commit                                  | `git commit -m "[YOUR COMMIT MESSAGE]"`              | `git commit -m "Fixes bug where logo didn't load properly"`                 |
|Create a and switch to a new Branch                  | `git checkout -b [NAME OF NEW BRANCH]`               | `git checkout -b newFeature`                                                |
|View list of all branches                            |`git branch`                                          |`git branch`                                                                 |
|Change current branch                                |`git checkout [BRANCH YOU WISH TO CHANGE TO]`         |`git checkout main`                                                          |
|Merge a branch into the current branch               |`git merge [BRANCH YOU WISH TO MERGE]`                |`git merge newFeature`                                                       |
|Set a remote for your local repo                     |`git remote add [NAME FOR REMOTE] [ADDRESS OF REMOTE]`|`git remote add my_awesome_new_remote_repo https://github.com/user/repo.git` |
|Keep your local repo in sync with the remote         |`git pull`                                            |`git pull`                                                                   |
|Mirror your commits to the remote                    |`git push [NAME OF REMOTE] [NAME OF BRANCH]`          |`git push origin main`                                                       |
