# Git

## Command to enter to see the commit graph:

```sh
git log --graph --decorate --all --oneline
```

Result:

```log
* 4469626 (HEAD -> master) fix(style): get rid of margin-right for city
* 00d8116 ajustements
| *   6b6b881 (refs/stash) WIP on master: d7b5ba6 no jekyll
| |\
| | * 08a5ae1 index on master: d7b5ba6 no jekyll
| |/
| * d7b5ba6 (origin/master, sauvegarde-minifie) no jekyll
| * 1cbe141 fix assets line
| * f0122db modified assets line
| * 752e362 adding read me
|/
* 7cd0dfe pages added
* 650f5b5 page restaurant 1
* 9feadaa animation coeur et footer
```

## Command to rebase the last commits

```sh
git rebase -i HEAD~3
```

- GitLens opens
- modify
- Click on `Start rebase`
