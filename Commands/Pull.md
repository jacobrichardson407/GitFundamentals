# git pull
Similar to a [git push](./Push.md), a `git pull` will interact with a remote repository.
Only this time it will **pull** the changes it does not have from the remote down to the local repository.

This means any commit made that are onthe remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
```
git pull origin main
```

If there is any upstream connection established, you can use `git pull` without specifying a remote or branch.

## Resources
- [Git Config Documentation](https://git-scm.com/docs/git-config)

---

[Back to Home](../README.md)