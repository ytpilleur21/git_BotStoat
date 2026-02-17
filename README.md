# Documentation pour le Bot en collaboration sur Stoat

## Initialisation du dépôt
```bash
git init
git remote add origin Https
``` 
## Envoyer un commit sur le dépot distant 

```bash
git status
git add .
git commit -m "Titre du Commit"
git push origin NOM_BRANCHE
```

## Création d'une branche

```bash
git checkout -b NOM_BRANCHE
git checkout NOM_BRANCHE
```

Pour les bonnes pratique, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépot distant, puis créer une pull request pour demander une revue de code. 

## Pour installer le dépot git

1. Installer Python 3.13
2. Cloner le dépot :
    -avec explorateur de fichier : Créer un dossier où vous voulez cloner le git
    -avec bash :
```bash
cd
cd PATH_FOLDER
mkdir NAME_FOLDER
cd NAME_FOLDER
```
-HTTPS :
```bash
git clone https://github.com/ytpilleur21/git_BotStoat.git
```
3. Créer l'environnement virtuel :
```bash
python -m venv .venv
```
4. Activer L'environnement :
    -windows : `.venv\Scripts\activate`
    -macOS/Linux : `source .venv/bin/activate`
5. Installer les dépendances :
```bash
    pip install -r requirements.txt
```

Pour l'API ajout d'un .env pour tout ce qui est perso.
Pour les dépendances utilisé, checker sur requirement.txt.
Ps : les dépendances peuvent ne plus exister après la publication du bot.