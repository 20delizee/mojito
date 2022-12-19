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
git add dev.md
git commit -m "commande"
git push -u origin dev