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

## Begriffe

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
*   Wie commite ich meine Änderungen?
    *   Was macht `commit`?
    *   Was macht `commit -m`?
*   Wie stage und commite ich eine Änderung?
    *   Was macht `commit -am`?
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
    *   Was macht `update-index --chmod=+x`
*   Wie entferne ich nicht erreichbare Commits?
    *   Was macht `gc`?
*   Wie finde ich nicht erreichbare Commits?
    *   Was macht `reflog`?

## Einstellungen

*   Was sind gute Defaults?
    *   user.name=Arlo O'Keeffe
    *   user.email=mailtoarlo@gmail.com
    *   core.excludesfile=~/.gitignore_global
    *   color.ui=true
    *   push.default=simple
    *   rebase.autostash=true
    *   pull.ff=only
    *   pull.rebase=true
*   Was ist autostash?
*   Was ist eine globale .gitignore?
*   Was sind aliase?

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

## Prinzipien / Konventionen

*   Was ist "commit early, commit often"?
*   Was ist "published History"?
*   Warum will man eine Versionskontrolle?
*   Ist git benutzerfreundlich?
*   Ist git die beste Versionskontrolle?
*   Ist git besser als svn?
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
*   Was ist der Unterschied zwischen porcelain und plumbing?
*   Wie oft soll ich commiten?
*   Wie oft soll ich pushen?
*   Kann ich ein Git Repository zippen?

## Repository Management

*   Was will man alles in einem Repository haben?
    *   diff-baren Quellcode. Also keine "erzeugten" Dateien.
*   Was gehört in eine .gitignore?
    *   https://www.gitignore.io/
*   Wie ignoriere ich einen ganzen Ordner?
    *   `/.settings/`
*   Wie de-ignoriere ich bestimmte Dateien in einem ignorierten Ordner?
    *   `!/.settings/user.setup`
*   Wie füge ich trotz .gitignore eine Datei hinzu?
    *   `git add --force`
*   Was gehört in eine gitattributes?
*   Wie sorge ich dafür, dass in jedem Betriebssystem die Datei CRLF Line
    Endings hat?

## Branch Management

*   Wie soll man Branches nennen?

## Tag Management

*   Wie soll man Tags nennen?

## History Management

*   Was ist der Unterschied zwischen Merge und Rebase?
*   Wie funktioniert ein interactive rebase?

## Kollaboration

*   Was ist Social Coding?
*   Wie arbeitet man mit mehreren Leuten zusammen?
*   Welche Fragen muss man beantworten können?
    *   Welcher Workflow wird eingesetzt? Beantwortet vllt. andere Fragen schon
    *   Wer darf ins Haupt-Repository pushen?
    *   Wie sieht der Prozess aus zwischen finalem Commit und Release zum
        End-User (a.k.a. Deploy)?
    *   Sind Notfall-Patches notwendig?
    *   Wie werden Referenzen benannt?
    *   Müssen alte Releases supported werden?
    *   Wie sieht der Lebenszyklus eines Branches aus?
*   Welche Workflows gibt es?
    *   Viele verschiedene. Mal mehr, mal weniger Bürokratie/Flexibilität.
    *   Grundsätzlich: cherry-pick vs. merge
    *   Was ist git-flow?
    *   Was ist GitHub Flow?
*   Wie hoste ich ein Remote Repository?
    *   git daemon
    *   Smart HTTP
    *   GitWeb
    *   GitLab
    *   GitBucket
    *   öffentliches Hosting: https://git.wiki.kernel.org/index.php/GitHosting
*   Wie clone ich ein Remote Repository?
*   Was ist das Line Ending Problem?
*   Wie ist das mit unterschiedlichen OS?
    *   autocrlf
*   Was ist ein protected Branch?
*   Was ist ein force Push?



## Automatisierung und Integration

*   Was muss man beachten?
*   Welche Tools gibt es?
*   Was sind FIX commit messages?
