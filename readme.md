## Good Game

##### To start developing:
1. Open `Git Bash` terminal
2. Go to projects directory
3. Run `yarn start`

##### To build for production (end result):
1. Open `Git Bash` terminal
2. Go to projects directory
3. Run `yarn run build`

##### Git commands:
| Usage | Command |
| --- | --- |
| Create branch | `git checkout -b [BRANCH_NAME]` |
| Go to branch |`git checkout [BRANCH_NAME]` |
| Update branch |`git pull` |
| See status |`git status` |
| Add all changed files before commit |`git add .` |
| Commit changes |`git commit -m "[COMMIT_MESSAGE]"` |
| Push commits to branch |`git push origin [CURRENT_BRANCH_NAME]` |

##### Git workflow:
* Main branch is `master`
* Create working branches from `master`
* When work finished - add, commit and push changes to current branch
* When pushed - go to github and do a `pull request`
* After that go to master, update it with `pull` and create another branch and continue working
