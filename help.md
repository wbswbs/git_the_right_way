[Back to start](README.md)

usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

## Allgemeine Git-Befehle, verwendet in verschiedenen Situationen:

## Arbeitsverzeichnis anlegen (siehe auch: git help tutorial)

   clone      ein Repository in einem neuen Verzeichnis klonen  
   init       ein leeres Git-Repository erstellen oder ein bestehendes neuinitialisieren

## an aktuellen Änderungen arbeiten (siehe auch: git help everyday) 

add
Dateiinhalte zum Commit vormerken mv eine Datei, ein Verzeichnis, oder
eine symbolische Verknüpfung verschieben oder umbenennen reset aktuellen
HEAD zu einem spezifizierten Zustand setzen rm Dateien im
Arbeitsverzeichnis und vom Index löschen

## Historie und Status untersuchen (siehe auch: git help revisions)

bisect Binärsuche verwenden, um den Commit zu finden, der einen Fehler
verursacht hat grep Zeilen darstellen, die einem Muster entsprechen log
Commit-Historie anzeigen show verschiedene Arten von Objekten anzeigen
status den Zustand des Arbeitsverzeichnisses anzeigen

## Historie erweitern und bearbeiten 

branch Branches anzeigen, erstellen
oder entfernen checkout Branches wechseln oder Dateien im
Arbeitsverzeichnis wiederherstellen commit Änderungen in das Repository
eintragen diff Änderungen zwischen Commits, Commit und
Arbeitsverzeichnis, etc. anzeigen merge zwei oder mehr
Entwicklungszweige zusammenführen rebase Wiederholtes Anwenden von
Commits auf anderem Basis-Commit tag ein mit GPG signiertes Tag-Objekt
erzeugen, auflisten, löschen oder verifizieren.

## mit anderen zusammenarbeiten (siehe auch: git help workflows) 

fetch

Objekte und Referenzen von einem anderen Repository herunterladen pull
Objekte von einem externen Repository anfordern und sie mit einem
anderen Repository oder einem lokalen Branch zusammenführen push
Remote-Referenzen mitsamt den verbundenen Objekten aktualisieren

'git help -a' und 'git help -g' listet verfügbare Unterbefehle und
einige Anleitungen zu Git-Konzepten auf. Benutzen Sie 'git help <Befehl>'
oder 'git help <Konzept>', um mehr über einen spezifischen Befehl oder
Konzept zu erfahren.
