# Was ist git

git ist ein Versionsverwaltungssystem

# Basis Befehle

git -> Zeigt eine Übersicht der Hilfe

## Änderungen der stage hinzufügen

git add {file}
git add {dir}
git add --all

## Unterschiede zwischen Workspace, Stage und Repository

git diff -> Zeigt die Unterschiede zwischen Workspace und Stage 

git diff --staged -> Zeigt die UNterschiede zwischen Stage und Repository

# Receipes

## push an existing repository from the command line

git remote add origin https://github.com/wbswbs/git_the_right_way.git
git push -u origin master
