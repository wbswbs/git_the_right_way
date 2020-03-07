[Back to start](README.md)

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

## User Credentials

### Add Username and Passord when cloning

```
git clone https://username:password@github.com/username/repository.git
```
## Store the User Credentials a certain time

```
git config --global credential.helper "cache --timeout=3600"
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

[Back to start](README.md)

## GitHub

### Add a Licence to the Repository

- Go to your repository's **Insights** tab
- Click **Community** on the left side
- On the right side, click **Add** on the line wich says **License**
