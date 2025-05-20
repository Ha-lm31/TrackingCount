<H1 align="center">Simulation et Adaptation des feux de signalisation </H1>


- Depot github : 
[`Github Repo Link`](https://github.com/Ha-lm31/TrackingCount.git)
[`Github Repo Link`](https://github.com/Ha-lm31/PFE-Module1.git)

<H2> Etape de liaison entre PC et github </H2> 
chemin :
C:\Users\ot\Desktop\TrackingCount
C:\Users\ot\Desktop\PFE-Module1

1. 
'''
cd <chemin>
'''
2. 
'''
git init
'''
3. 
'''
git add .
'''
4. 
'''
git status
'''
5. 
'''
git commit -m "First commit"
'''
6. 
'''
git branch -M main
'''
7. 
'''
git remote add origin <Depot github>
'''
8. 
'''
git remote -v
'''
9. 
'''
git push -u origin main
'''
ou 
'''
git push -u origin main --force
'''
- - Si tu veux modifier le contenu du dépot, suivi si étape : 
1. 
'''
git add .
'''
2. 
'''
git status
'''
3. 
'''
git commit -m "... commit"
'''
4. 
'''
git push -u origin main
'''
ou
'''
git push -u origin main --force
'''

<H2>Modification 'requirement.txt'</H2>

1. Ajouter : pipdeptree, roboflow
2. Supprimer : torch
