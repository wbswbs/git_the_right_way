# Git Recipes

## Repositories

### Add a remote repository as Default

```
git remote add origin {repository}
# Set as Default Upstream
git push --set-upstream origin master
```

### Remove a remote repository

```
git remote remove origin
```

### Add Username and Passord when cloning

```
git clone https://username:password@github.com/username/repository.git
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
git add --all
```
