# git push
When you have a [remote](./remote.md) set up you'll need to begin to move [commits](./commit.md) tot he remote. This can be done with the command 'git push'.
You can attach a name and branch name to your command to specify where youre pushing to.
```
git push origin main
```
This command will push the **main** branch to the remote called **origin**. This means any commits that are in your local will be **pushed** to the remote.
### upstream tracking
Instead of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch.This means you can tell the branch to pushto its assigned upstream remote branch by using the command 'git push'.
Before doing so, you'll need to use the '-u' or '--set-upstream' flag. Thiscan be done on any 'git push'.
```
git push -u origin main
```
After this command is used,you can just use 'git push' and it will function the same way.

## Resources
- [git push documentation](https://git-scm.com/docs/git-push)
---
[back to home](../readme.md)
