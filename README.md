0)$ git config user.name "Mazzola"
0bis)$ git config user.email "mailFreeTax@protonmail.com"
importante: prima di iniziare ogni progetto github è necessario cmbiare username e email per effettuare commit a proprio nome 

1)$ git init //creazione del progetto 
2)$ touch .gitignore //il file .gitignore serve a 
3)$ git add *;
4)$ git commit -m "Inizializazione del progetto";
5)$ git add *;
6)$ git commit -m "busines core implementato";
7)$ git checkout -b "FIX_BUG";
8)$ git add *;
9)$ git commit -m "corretto errore nelle condizioni del for: prima contava solo fino a 9, adesso conta fino a dieci";
10)$ git checkout "master"
10bis)$ git add *;
11)$ git commit -m "system("PAUSE") inserito";
12)$ git checkout "FIX_BUG"
13)$ git add *;
14)$ git commit -m "inclusione namespace";
15)$ git checkout "master"
16)$ git add *;
17)$ git commit -m "aggiunta commenti al codice"
18)$ git merge "FIX_BUG"
19)$ git remote add "link1" https://github.com/Francescomazzola/printer-1-to-10.git
20)$ git add *;
21)$ git commit -m "merge fatto ma con errori"
22)$ git push link1 master
23)$ git push link1 FIX_BUG
