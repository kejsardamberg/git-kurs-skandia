# git-kurs-skandia
Grundkurs i Git för Skandia

## Lathund för git-kommandon

|Kommando	|Beskrivning	|Exempel|
|-----------|---------------|-------|
|git init	|Initierar aktuell katalog till att vara ett nytt Git-repository.	|git init|
|git clone <url>	|Klonar ett existerande repository från en URL till lokal dator.	|git clone https://github.com/...|
|git status	|Visar status för ändringar i lokala repositoryt.	|git status|
|git add <fil>	|Lägger till en fil i staging-området (förbereder för commit).	|git add fil.txt|
|git add .	|Lägger till alla ändrade filer i staging-området. (notera punkten)	|git add .|
|git commit -m "<meddelande>"	|Skapar en commit med ett meddelande som beskriver ändringarna.	|git commit -m "Fixed purchase date format"|
|git log	|Visar en logg av tidigare commits.	|git log|
|git pull	|Hämtar och slår ihop (merge) ändringar från en fjärrbranch.	|git pull origin main|
|git push	|Skickar dina commits till en fjärrserver.	|git push origin main|
|git branch	|Listar alla brancher i repositoryt.	|git branch|
|git branch <namn>	|Skapar en ny branch.	|git branch feature-branch|
|git checkout <branch>	|Byter till en annan branch.	|git checkout feature-branch|
|git merge <branch>	|Slår ihop en annan branch med den nuvarande branchen.	|git merge feature-branch|
|git diff	|Visar skillnader mellan ändringar som ännu inte är staged eller committade.	|git diff|
|git reset <fil>	|Tar bort en fil från staging-området.	|git reset fil.txt|
|git reset --hard	|Återställer alla ändringar till senaste commit. OBS! Kan inte ångras.	|git reset --hard|
|git restore <fil>	|Återställer en specifik fil till senaste commiten.	|git restore fil.txt|
|git fetch	|Hämtar uppdateringar från en fjärrserver utan att slå ihop dem.	|git fetch origin|
|git rebase <branch>	|Applicerar commits från en annan branch på den nuvarande branchen.	|git rebase main|
|git stash	|Sparar ändringar som ännu inte är committade till en tillfällig lagringsyta.	|git stash|
|git stash pop	|Återställer ändringar från stash och tar bort dem från lagringsytan.	|git stash pop|
|git rm <fil>	|Tar bort en fil från repositoryt (både lokalt och i nästa commit).	|git rm fil.txt|
|git remote -v	|Visar vilka fjärr-repositoryn som är kopplade till ditt lokala repository.	|git remote -v|
|git tag <tag>	|Skapar en tagg för en commit, ofta använd för versionshantering.	|git tag v1.0.1|

