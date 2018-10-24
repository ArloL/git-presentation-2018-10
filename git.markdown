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

*   [Think Like (a) Git](http://think-like-a-git.net/)
*   [Git Best Practices](http://sethrobertson.github.io/GitBestPractices/)
*   [12 advanced Git commands I wish my co-workers would know
    ](http://www.askaswiss.com/2016/01/12-useful-advanced-git-commands.html)
*   [How to Write a Git Commit Message
    ](https://chris.beams.io/posts/git-commit/)
*   [git-flow](https://nvie.com/posts/a-successful-git-branching-model/)
*   [GitHub Flow](https://guides.github.com/introduction/flow/)

## Definitionen

*   Was ist ein Graph?
*   Was ist ein gerichteter Graph?
*   Was ist ein azyklischer Graph?
*   Was ist Erreichbarkeit?
*   Was ist ein Baum?
*   Was ist eine untracked Datei?
*   Was ist eine Änderung?
*   Was ist die "Stage"?
*   Was ist ein Commit?
*   Was ist ein Hash?
*   Was ist ein Branch?
*   Was ist ein Tag?
*   Was ist der HEAD?
*   Was ist ein detached HEAD?
*   Was ist HEAD^?
*   Was ist HEAD^^?
*   Was ist HEAD~3?
*   Was ist eine Referenz?
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
*   Wie commite ich auf der Kommandozeile?
    *   Was macht `commit`?
    *   Was macht `commit -m`?
    *   Was macht `commit -am`?
*   Wie erstelle ich einen Branch?
    *   Was macht `branch`?
*   Wie lösche ich einen Branch?
    *   Was macht `branch -d`?
*   Wie wechsle ich den aktuellen Branch?
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
*   Was macht `stash`?
*   Was macht `stash apply`?
*   Was macht `cherry-pick`?
*   Wie ändere ich eine Commit Message?
    *   Was macht `commit --amend`?
    *   Was macht `rebase`?
*   Wie entferne ich alle Änderungen und unnötige Dateien (inkl. ignorierten)?
    *   Was macht `clean`?
*   Wie finde ich raus wer das commitet hat?
    *   Was macht `blame`?
*   Wie finde ich raus wann der Fehler eingeführt wurde?
    *   Was macht `bisect`?
*   Wie füge ich unter Windows ein Executable Flag hinzu?
*   Was macht `gc`?

## Repository Management

*   Was will man alles in einem Repository haben?
*   Was gehört in eine .gitignore?
*   Wie ignoriere ich einen ganzen Ordner?
*   Wie de-ignoriere ich bestimmte Dateien in einem ignorierten Ordner?
*   Wie füge ich trotz .gitignore eine Datei hinzu?
*   Was gehört in eine gitattributes?
*   Wie sorge ich dafür, dass in jedem Betriebssystem die Datei CRLF Line
    Endings hat?

## Graph Management

*   Was ist der Unterschied zwischen Merge und Rebase?
*   Wie funktioniert ein interactive rebase?

## Einstellungen

*   Was sind gute Defaults?
*   Was ist autostash?
*   Was ist eine globale .gitignore?
*   Was sind aliase?

## Kollaboration

*   Was ist Social Coding?
*   Wie arbeitet man mit mehreren Leuten zusammen?
*   Welche Workflows gibt es?
    *   Was ist git-flow?
*   Wie hoste ich ein Remote Repository?
    *   GitLab
    *   GitBucket
    *   GitHub
    *   BitBucket
*   Wie clone ich ein Remote Repository?
*   Was ist das Line Ending Problem?
*   Wie ist das mit unterschiedlichen OS?
    *   autocrlf
*   Was ist ein protected Branch?
*   Was ist ein force Push?

## Automatisierung

*   Was muss man beachten?
*   Welche Tools gibt es?

## Integration

*   Was sind FIX commit messages?

## Prinzipien / Konventionen

*   Warum will man eine Versionskontrolle?
*   Ist git benutzerfreundlich?
*   Ist git die beste Versionskontrolle?
*   Was sind übliche Konventionen?
    *   Commit Messages
    *   lowercase Branch-Namen
    *   master, develop, feature-* Branches
    *   origin und upstream Remote
*   Was bedeutet es, dass git verteilt ist?
    *   Im ersten Moment alle Änderungen lokal
    *   Unter unserer Kontrolle wann remote
    *   Schnell+Unabhängig (weil kein Netzwerk notwendig)
*   Was ist ein Event-Sourced-System?
*   Warum ist git besser als svn?
*   Was ist der Unterschied zwischen porcelain und plumbing?
*   Wie oft soll ich commiten?
*   Wie oft soll ich pushen?
*   Kann ich ein Git Repository zippen?

## Alltag

*   Welche Clients gibt es?
    *   git (git bash unter Windows)
    *   Eclipse
    *   SourceTree
    *   Tower
    *   Visual Studio Code
    *   IntelliJ
    *   TortoiseGit
