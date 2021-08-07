## FreemanSoft on the Internet 
* [FreemanSoft GitHub](https://github.com/freemansoft)
* [FreemanSoft Blog](https://joe.blog.freemansoft.com)
* [FreemSoft YouTube Channel](https://www.youtube.com/channel/UCKHhuCt5LPp8defcKMpf7zwhttps://www.youtube.com/channel/UCKHhuCt5LPp8defcKMpf7zw)
* [FreemanSoft GitHub Pages](https://freemansoft.github.io/)

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
## This site
This site is hosted on [GitHub Pages](https://pages.github.com/")
