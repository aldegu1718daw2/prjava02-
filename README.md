1.

git branch branca00

git checkout branca00

git status--> estic a la branca branca00

5.

git checkout master

git status

git log

només hi ha un commit, a branca00 hi ha dos

6.
git status--> Estem a branca00

geany Prjava02.java

No, ja que el commit de la modificació, i per tant el fitxer modificat amb la nova línia es troba a la branca00.

7.
git checkout branca00

geany Prjava02.java

Des de branca00 si, ja que el commit de la modificació, i per tant el fitxer modificat amb la nova línia es troba a aquesta branca.

10.
git checkout master

geany Prjava02.java --> Sense línies afegides

git merge branca00

geany Prjava02.java --> Línies afegides dels commits de la branca00

12.

git push

Només s'ha actualitzat la branca master perquè hem fet un merge de la branca00 amb master.

14.
git push -u origin branca01 --> S'ha generat la branca01 a github
