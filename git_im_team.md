
# Git im Team

Folgende Notizen entstanden nach dem sehr guten Vortrag "Git im Team"
von Thomas Weinert auf der Unkonf 2019 in Mannheim.

## Workflow

- Working on Master Branch 
- Feature Branches with Tickets
- Versionsnummer durch Semantic Versioning: Major.Minor.Fixes
- Semantic Versioning with Tags

Bei längeren Tickets

    $ git rebase master
    
um den eigenen Stand mit Master zu synchronisieren

## Feature Branch

- Feature Branch an das Ticket koppeln
- Möglichst klein (1-2 Tage)
- Bei Wechsel -> Stash: Ablegen der Änderungen

## Commit Messages

Titel: Ticket-ID [BUG][FEATURE][!!!] Description

Leerzeile

Description: Wenn diese Änderung angewendet wird, dann ..

Referenz Ticket ID:

Links zum Wiki, etc.

 
## Git Circle

Maintainer: Master (Main Repository)

Developer:  -> checkout

 Master -> Feature Branch -> Master
 
Push to Fork Repository

Merge Request to Main Repository

Maintainer: Merge

## Konsole

    $ git --tags

## Dateien 

- README.md 
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md
- LICENCE.md

## Globale Einstellungen

- GPG Key
- Ignore .idea






 