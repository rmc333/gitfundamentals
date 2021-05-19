# git pull
Similar to a [git push](./push.md), a 'git pull' will interact with a remote repository.Only this time it will **pull** the changes it does not have from the remote down to the local repository.
This means any commits made that are on the remote repository will be pulled down and added to the local repository. This can be done by adding the remotename and branch name:
```
git pull origin main
```
If there is any upstream connectionestablished, you can use 'git pull' without specifying a remote or branch.
## Resources
- [git pull documentation](https://git-scm.com/docs/git-pull)

[back to home](../readme.md)