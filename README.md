# TP-flow

git checkout -b develop
git checkout develop
je creer FICHIER D
git add fichier D
git commit -m '[add] Ajout fichier D' > git push origin develop

git checkout -b hotfix 
git add fichier Z 
git commt -m '[add] ajout fichier Z'
git merge main

git checkout develop 
git fetch 
git pull
git merge develop

git checkout -b feature 01 
Une fois sur la branch je créer FICHIER A
git checkout feature 01 > git commit -m '[add] Ajout fichier A' > git push origin feature 01

git checkout -b feature 02
git checkout develop
git fetch 
git pull
git checkout feature 02
git merge develop
git checkout feature 02 > git commit -m '[add] Ajout fichier C' > git push origin feature 02

git checkout develop 
creer modifier fichier D
git add fichier D
git commit -m '[edit] Modif fichier D' > git push 

git checkout main 
git fetch
git pull
git checkout develop 
git merge main

git checkout -b realese
git add fichier D
git commit -m '[edit] fichier d modifier'
git push
git merge main

git checkout develop 
creer FICHIER E
git add FICHIER E
git commit '[add] ajout fichier E' > git push

git checkout feature 02 
creer FICHIER C
git add FICHIER C
git commit '[add] ajout fichier C' > git push
git merge develop

git chekcout feature 01
je creer FICHIER B sur branch feature 01
git checkout develop
git fetch 
git pull
git checkout feature 01
git merge develop