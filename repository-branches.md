## Repository default branches
All repositories rooted here are migrating default branch names of `master` to `main`

All repositories forked from other repositories will retain the naming conventions of those repositories.

### Branch Migration

You can migrate from master to main in a forked repository with
    
```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```
