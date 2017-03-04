---
layout: post
title:  "Jekyllbrücke"
date:   2017-03-04 23:31:00 +0100
categories: blog
tags: jekyll support github
---
Um meiner Vergesslichkeit entgegenzukommen, liefere ich mir hier die wichtigsten Schritte zum erfolgreichen Posten mit jekyll und github.

# 1. Einen Post anlegen

Im Ordner _posts eine Datei mit dem Format YYYY-MM-DD-name-of-post anlegen.
yml-Header nicht vergessen.
Schreiben. Speichern.

# 2. Sprung in die command line

Commandline öffnen und Directory mit `cd` setzen und darauffolgender Ordnerstruktur setzen.
Directory auf Projektebene setzen.
Mit `cd ..` ggf. wieder in übergeordneten Ordner gehen.

# 3. Auf lokalem Server ausprobieren

`jekyll serve` bringt den Server zum laufen.
Die Webseite samt neuen Post kann auf `localhost:4000` angesehen und gesprüft werden.
Mit `ctrl + c` kann der Server wieder beendet werden.

# 4. Git Commit

1. `git add .`
2. `git commit -m "Explain the change"`

# 5. Git Status übperprüfen

Mit `git status` überprüfen, ob es Änderungen gab und alles passt.
Eine ideale sieht zum Beispiel so aus:
>On branch master  
>Your branch is ahead of 'origin/master' by 1 commit.  
>  (use "git push" to publish your local commits)  
>nothing to commit, working tree clean  

# 6. Push und fertig

Mit `git push` wird der commit durchgesetzt.
In einen Browser gehen und <a href="http://dataista.github.io" target="_blank">die Webseite</a> samt Änderungen besuchen.

# 7. Weitere Tipps

####  Gegebenenfalls nach Markdownunterstützung suchen
Zum Beispiel mit diesem <a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet" target="_blank">Cheatsheet</a>

#### Links gleich anders formatieren
Damit sich Links in einem neuen Tab öffnen, dieses Schema nutzen:  
`<a href="http://dataista.github.io" target="_blank">die Webseite</a>`
