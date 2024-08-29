## Exercice 2 : Rebase et fusion de commits

### Objectif
Comprendre comment utiliser `git rebase` pour combiner plusieurs commits en un seul commit.

### Étapes
1. Création du fichier `file1.txt` avec deux commits séparés.
2. Création du fichier `file2.txt` et validation.
3. Utilisation de `git rebase -i` pour fusionner les deux commits de `file1.txt`.

### Commandes Utilisées
- `git rebase -i HEAD~3`

### Résultat
Les commits ont été correctement fusionnés en un seul commit pour `file1.txt`.

---