# branchMeAufgabe
## Teil 1

1. Erstelle ein neues Repository auf Github branchMe (mit README und public)
2. Clone das Repository auf deinen Rechner
3. Schreib in die README, z.B. den Text dieser Aufgabe
4. Erstelle eine index.html mit folgendem Inhalt:

'<!DOCTYPE html>
<html>
 <head>
  <meta charset="UTF-8">
  <title>Document</title>
 </head>
 <body>
  <header>
   <h1>Ich bin eine Überschrift</h1>
  </header>
  <main>
   <p>Ich bin ein Text</p>
  </main>
  <footer>
   <p>Ich bin ein Footer</p>
  </footer>
 </body>
</html>'

--> Vergiss nicht zu deine Änderungen zu speichern, wenn du unsicher bist checke immer mit git status ob alles aktuell ist
--> Push deine Änderungen zu github

## Teil 2

*Alle Schritte bei euch Lokal, ihr verändert nichts auf github außer ihr pusht!*
1. Erstelle 2 neue Branches (noch nicht dort reinwechseln!!): body & index
2. Checke mit git branch, dass du im main branch bist und ob die beiden neuen Branches existieren
3. Wechsel in den Branch body und ändere in der index :
  <main>
   <p>Ich wurde von BODY bearbeitet</p>
  </main>
4.  Adden, committen
5. Push den Branch zu Github und checke ob das geklappt hat
6. Wechsel in den Branch index
7. Öffne wieder die index.html und füge dort ein:
  <main>
   <p>Ich wurde von INDEX bearbeitet und hey ich hab euch was zu sagen</p>
  </main>
8. Adden und commiten
9. Auch den Branch pushst du zu github

## Teil 3 - Bonus

1. Geh zu Github(! nicht lokal!!) und erstelle für die neuen Branches jeweils einen Pull Request um diesen danach in die Main einzufügen (merge), löse die entstandenen Konflikte auf
2. Wenn die Branches in in die main eingefügt wurden, zieh dir die aktuelle Version mit (git pull) zurück auf deinen Rechner