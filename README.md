# We werken samen met git!

### Werkproces + belangrijke commands

1. clone
   - `git clone <url>`
2. binnen gaan
   - `cd <map-naam>`
3. branch maken
   - `git branch featureNaam`
4. switchen van branch
   - `git checkout featureNaam`
   - `git switch featureNaam` (dezelfde)
5. push branch
   - `git push -u origin featureNaam`
6. lekker coderen!!!
7. toevoegen aan commit
   - `git add .` (alles)
   - `git add <fileName>` (specifiek bestand)
8. commit
   - `git commit -m "message about changes"`
9. push naar github
   - `git push`
10. op github.com een pull request doen...
11. terug naar main
    - `git checkout main`
    - `git switch main` (dezelfde)
12. pull!
    - `git pull`

### Any time:

- `git status`

### Begin van een project (1 persoon)

1. Maak een map
2. Maak er een repository van
   - `git init`
3. Maak een repository op github.com
4. Verbinding maken met de github repository
   - `git remote add origin <link>`
5. Maak een main branch
   - `git branch -M main`
6. Voeg collaborators toe op github settings

### Pull Request

1. `git checkout main`
2. `git pull`
3. `git checkout featureName`
4. `git merge main` - combinatie van main + eigen werk
5. `git push`
6. Pull Request op github.com
