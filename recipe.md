[Back to start](README.md)

# Git Recipes

## Repositories

### Add a remote repository as Default

```
# Remote hinzufügen
# git remote add {name} {repository}
git remote add wbsgithub git@github.com:wbswbs/qs.git

# Hochspieln
git push wbsgithub 

# Remote als Dfeualt -u = update origin
# Set as Default Upstream
# git push --set-upstream origin master
git push -u wbsgithub 

#Remotes anzeigen
git remote -v
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

## How do I make Git ignore file mode chmod changes

http://stackoverflow.com/questions/1580596/ddg#1580644
Try:

```
git config core.fileMode false
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
