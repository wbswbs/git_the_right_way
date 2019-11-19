# Git Recipes

## Repositories

### Add a remote repository

```
git remote add {repository}
```

### Remove a remote repository

```
git remote remove origin
```

## Explain

### Show all Versions of a file

```
    git log --format="%H" $FILENAME

```
 or

```
        git log --oneline $FILENAME  

```

### Add all unversioned Files


```
git add -u :/
```
