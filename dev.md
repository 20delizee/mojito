1ere envoie 
git init 
git add recette.md 
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/20delizee/mojito.git
git push -u origin main

recette pour 2 personnes: 
git add recette.md 
git commit -m "deux personnes"
git push -u origin main

#Creation branch dev
git branch dev
git branch
git checkout dev
git pull
git add dev.md
git commit -m "commande"
git push -u origin dev


#Pour 10 personnes 
changer de branch 
git checkout main
git add recette.md
git commit -m "recette10"
git push -u origin main

#recette malade 1
git branch malade
git branch
git checkout malade
git pull
git add recettebis.md
git commit -m "recette empoissonnée"
git push -u origin malade

#recette malade 2
git add recettebis.md
git commit -m "recette empoissonnée 2.0"
git push -u origin malade


recette pour 2 personnes: 
git checkout main
git add recette.md 
git commit -m "deux personnes"
git push -u origin main