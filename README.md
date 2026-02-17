# Documentation pour le Bot en collaboration sur Stoat

## Initialisation du dépôt
```bash
git init
git remote add origin Https
``` 
## Envoyer un commit sur le dépot distant 

```bash
git add .
git commit -m "Titre du Commit"
git push origin master
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépot distant, puis créer une pull request pour demander une revue de code. 