git flow init
    chiamare il master con il nome main

git remote add origin "https://github.com/genos36/ElettronicaPadovana"

git push origin --all
    per pushare tutti i branch sulla repo:

git flow feature start issue1

git add ./inventario.md

git commit -m "close #1 messaggio"

git flow feature finish issue1 -k

git flow release start  prova1

git flow release publish prova1 

git add ./

git commit -m "modifiche dell'ultimo minuto"

git flow release finish prova1 
    fa il merge sul master/main locale

git checkout master/main

git push origin master/main



