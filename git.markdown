# git im Kontext industrieller Softwareentwicklung

*   Stand: 2018-10-25
*   Autor: Arlo O'Keeffe
*   Kontakt: mailtoarlo@gmail.com

## Ressourcen

*   [Pro Git](https://git-scm.com/book/en/v2)

### Tutorials

*   https://try.github.io
*   https://www.atlassian.com/git/tutorials
*   https://backlog.com/git-tutorial/
*   https://learngitbranching.js.org/

### Videos

*   [Einführung in verteilte Versionskontrolle mit Git
    ](https://www.youtube.com/watch?v=mPWMtyKYFUI)
*   [Learn Git in 20 Minutes](https://www.youtube.com/watch?v=Y9XZQO1n_7c)

### Weiterführende Themen

*   [The Git Parable
    ](http://tom.preston-werner.com/2009/05/19/the-git-parable.html)
*   [Think Like (a) Git](http://think-like-a-git.net/)
*   [Git Best Practices](http://sethrobertson.github.io/GitBestPractices/)
*   [12 advanced Git commands I wish my co-workers would know
    ](http://www.askaswiss.com/2016/01/12-useful-advanced-git-commands.html)
*   [How to Write a Git Commit Message
    ](https://chris.beams.io/posts/git-commit/)
*   [gitworkflows](https://gitirc.eu/gitworkflows.html)
*   [git-flow](https://nvie.com/posts/a-successful-git-branching-model/)
*   [GitHub Flow](https://guides.github.com/introduction/flow/)

## Begriffe

*   Was ist eine untracked Datei?
*   Was ist eine Änderung?
*   Was ist Staging?
*   Was ist der Index?
*   Was ist ein Commit?
*   Was ist ein Hash?
*   Was ist ein Branch?
*   Was ist ein Tag?
*   Was ist der HEAD?
*   Was ist ein detached HEAD?
*   Was ist HEAD^?
*   Was ist HEAD^^?
*   Was ist HEAD~3?
*   Was ist ein Checkout?
*   Was ist ein Clone?
*   Was ist ein Repository?
*   Was ist ein bare Repository?
*   Was ist ein Remote?
*   Was ist ein Stash?
*   Was ist eine Hook?
*   Was ist ein Submodule?
*   Was ist ein Pull Request?

## Aktionen

*   Wie erstelle ich ein neues Repository?
    *   Was macht `init`?
*   Wie sehe ich lokale Änderungen?
    *   Was macht `status`?
*   Wie stage ich eine Änderung?
    *   Was macht `add`?
    *   Was macht `add --all`?
    *   Was macht `add .`?
*   Wie stage ich nur einen Teil meiner Änderungen?
    *   Was macht `add --interactive`?
*   Wie commite ich meine Änderungen?
    *   Was macht `commit`?
    *   Was macht `commit -m`?
*   Wie stage und commite ich eine Änderung?
    *   Was macht `commit -am`?
*   Wie ignoriere ich bestimmte Dateien?
    *   `*.log`
*   Wie ignoriere ich einen ganzen Ordner?
    *   `/.settings/`
*   Wie de-ignoriere ich bestimmte Dateien in einem ignorierten Ordner?
    *   `!/.settings/user.setup`
*   Wie füge ich trotz .gitignore eine Datei hinzu?
    *   Was macht `add --force`?
*   Wie erstelle ich einen Branch?
    *   Was macht `branch`?
*   Wie lösche ich einen Branch?
    *   Was macht `branch -d`?
*   Wie wechsel ich den aktuellen Branch?
    *   Was macht `checkout`?
*   Wie sehe ich den Unterschied zwischen zwei Branches?
    *   Was macht `diff`?
*   Wie merge ich zwei Branches?
    *   Was macht `merge`?
    *   Was macht `merge --ff`?
*   Wie löse ich einen Merge-Konflikt?
*   Wie erstelle ich einen Tag?
    *   Was macht `tag`?
*   Wie mache ich eine Änderung rückgängig?
    *   Was macht `reset --soft`?
    *   Was macht `reset --hard`?
*   Wie ändere ich eine Commit Message?
    *   Was macht `commit --amend`?
    *   Was macht `rebase`?
*   Wie hole ich mir ein externes Repository?
    *   Was macht `clone`?
*   Wie schiebe ich meine Änderungen in ein externes Repository?
    *   Was macht `push`?
    *   Was macht `push --force`?
*   Wie aktualisiere ich den Zustand vom externen Repository?
    *   Was macht `fetch`?
*   Wie hole ich mir die neusten externen Änderungen in mein Projekt?
    *   Was macht `pull`?
    *   Was macht `pull --rebase`?
*   Wie kann ich Änderungen zwischenspeichern?
    *   Was macht `stash push|save`?
    *   Was macht `stash pop|apply`?
*   Wie kann ich Änderungen zwischenspeichern und den Index behalten?
    *   Was macht `stash push --keep-index`?
*   Wie kann ich einen einzelnen Commit eines anderen Branches übernehmen?
    *   Was macht `cherry-pick`?
*   Wie entferne ich alle Änderungen und unnötige Dateien (inkl. ignorierten)?
    *   Was macht `clean`?
*   Wie finde ich raus wer das commitet hat?
    *   Was macht `blame`?
*   Wie finde ich raus wann der Fehler eingeführt wurde?
    *   Was macht `bisect`?
*   Wie füge ich unter Windows ein Executable Flag hinzu?
    *   Was macht `update-index --chmod=+x`
*   Wie entferne ich nicht erreichbare Commits?
    *   Was macht `gc`?
*   Wie finde ich nicht erreichbare Commits?
    *   Was macht `reflog`?

## Prinzipien

*   Was ist ein Graph?
*   Was ist ein gerichteter Graph?
*   Was ist ein azyklischer Graph?
*   Was ist Erreichbarkeit?
*   Was ist ein Baum?
*   Was ist ein Object?
*   Was ist eine Referenz?
*   Was ist ein Event-Sourced-System?
*   Was bedeutet es, dass git verteilt ist?
    *   Im ersten Moment alle Änderungen lokal
    *   Unter unserer Kontrolle wann remote
    *   Schnell+Unabhängig (weil kein Netzwerk notwendig)
*   Kann ich ein Git Repository zippen?
*   Was ist porcelain?
*   Was ist plumbing?

## Philosophie

*   Warum will man eine Versionskontrolle?
*   Ist git die beste Versionskontrolle?
*   Ist git besser als svn?
*   Ist git benutzerfreundlich?
*   Was ist Social Coding?

## Kollaboration

*   Wie arbeitet man mit mehreren Leuten zusammen?
*   So wenig Prozess wie möglich. So viel wie nötig.
    *   http://widgetsandshit.com/teddziuba/2011/12/process.html
*   Welche Fragen muss man beantworten können?
    *   Welcher Workflow wird eingesetzt? Beantwortet vllt. andere Fragen schon
    *   Wie sieht der Prozess aus zwischen finalem Commit und Release zum
        End-User (a.k.a. Deploy)?
    *   Gibt es Reviews?
    *   Was sind die Konventionen?
    *   Commit Messages
    *   lowercase Branch-Namen
    *   master, develop, feature-* Branches
    *   origin und upstream Remote
*   Wie hoste ich ein Remote Repository?
    *   git daemon
    *   Smart HTTP
    *   GitWeb
    *   GitLab
    *   GitBucket
    *   öffentliches Hosting: https://git.wiki.kernel.org/index.php/GitHosting

### Repository Management

*   Was will man alles in einem Repository haben?
    *   diff-baren Quellcode. Also keine "erzeugten" Dateien.
*   Was gehört in eine .gitignore?
    *   https://www.gitignore.io/
*   Was gehört in eine gitattributes?
*   Wie sorge ich dafür, dass in jedem Betriebssystem die Datei CRLF Line
    Endings hat?

### Branch Management

*   Wie werden Branches benannt?
*   Wofür werden Branches erstellt?
*   Wie sieht der Lebenszyklus eines Branches aus?
*   Wer macht was? Wer arbeitet wo?
*   Sind Notfall-Patches notwendig?
*   Müssen alte Releases supported werden?
*   Was ist ein protected Branch?

### Tag Management

*   Wie werden Tags benannt?
*   Wofür werden Tags erstellt?
*   Wer erstellt Tags?

### Log / History Management

*   Wie sehen Commit Message aus?
*   Was ist der Unterschied zwischen Merge und Rebase?
*   Wie funktioniert ein interactive rebase?
*   Mit oder ohne ff commit?

### Workflows

*   Welche Workflows gibt es?
    *   Gibt mehrere. Mal mehr, mal weniger Bürokratie/Flexibilität.
    *   Grundsätzlich: cherry-pick vs. merge
    *   Was ist git-flow?
    *   Was ist GitHub Flow?

## Alltag

*   Welche Clients gibt es?
    *   git (git bash unter Windows)
    *   SourceTree
    *   Visual Studio Code
    *   Eclipse
    *   Tower
    *   IntelliJ
    *   SublimeMerge
    *   TortoiseGit
    *   uvm.
*   Was sind gute Einstellungen?
    *   user.name=Arlo O'Keeffe
    *   user.email=mailtoarlo@gmail.com
    *   core.autocrlf=true
    *   core.excludesfile=~/.gitignore_global
    *   color.ui=true
    *   push.default=simple
    *   rebase.autostash=true
    *   pull.ff=only
    *   pull.rebase=true
    *   alias.adog=log --all --decorate --oneline --graph
*   Was ist autostash?
*   Was ist eine globale .gitignore?
*   Was sind aliase?

## Automatisierung und Integration

*   Was muss man beachten?
*   Welche Tools gibt es?
*   Was sind FIX commit messages?
