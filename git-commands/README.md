# Git-commands

### Username und email am besten immer konfigurieren. Am besten die Selbe email wie github oder ander git webs verwenden.

    git config --global user.name "username"

    git config --global user.email "email@example.at"

### Listet die config auf, gut wenn man sehen will auf welche email man grade ist.

    git config -l

### Erschafft im gewählten Ordner die git file

    git init

### Added die files
### Hinweis: Vor dem adden am besten schon eine .gitignore file erstllen damit man auch nichts unnötiges commited

    git add .

### Commit speicher die changes

    git commit -m "text"

### Zeigt commits an

    git log

### Zeigt den aktuellen Status des Git repos. immer am Anfang benutzen um zu sehen auf welchen branch man ist.

    git status

### Sendet den Branch ins remote.

    git push [remote-name] [branch-name]

### erstellt ein Branch und wechselt zu den.

    git checkout -b [branch-name]

### wechselt Branch.

    git checkout [branch-name]

### Listet die Branches auf.

    git branch

### Macht eine Kopie vom aktuellsten Projekt im Git repo

    git clone [repo-url]

### Merge ist eigentlich nicht nötig wenn man auf einem Git Web Repo alles managed.

### Aber nur für den Fall:

### in den dev oder default branch wechseln

    git checkout dev

### branch aktualisieren:

    git fetch

### mergen:

    git merge [branch-name]
