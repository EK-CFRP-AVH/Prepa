# Évaluation GIT – élèves non voyants (CLI uniquement)

Durée indicative : 45 à 60 minutes  
Mode : ligne de commande uniquement (cmd ou bash)

---

## Consignes générales

- Utiliser uniquement la ligne de commande (cmd ou bash).
- Répondre directement dans les fichiers du dépôt cloné.
- Pour chaque question pratique :
  - copier/coller la commande exacte tapée ;
  - copier/coller l’extrait de sortie utile (par exemple la ligne contenant le message Git).
- L’aide intégrée de Git est autorisée :  
  `git --help` ou `git <commande> --help`.

---

## Partie 1 – Questions théoriques (sur 15 points)

Répondre en texte brut dans le fichier `reponses_theorie.md` du dépôt.

1. Définir, en une phrase chacun :
   - un dépôt Git (repository) ;
   - un commit.

2. Expliquer la différence entre :
   - fichier **non suivi** (untracked) ;
   - fichier **modifié mais non indexé** (modified / not staged) ;
   - fichier **indexé** (staged).

3. Indiquer le rôle principal des commandes suivantes et donner un exemple très court d’utilisation (juste la forme de la commande, pas besoin de chemin réel) :
   - `git init`
   - `git status`
   - `git add`
   - `git commit -m "message"`
   - `git log`

4. Expliquer à quoi sert le message de commit.  
   Donner au moins une bonne pratique pour rédiger un message de commit.

5. Expliquer la signification du message suivant, affiché par `git status` :
   - `nothing to commit, working tree clean`

---

## Partie 2 – Manipulation d’un dépôt sur GitHub (sur 25 points)

Cloner le  dépôt GitHub public dont l’URL sera fournie (exemple :  
`https://github.com/compte-exemple/eval-git-2026.git`), créer une branche individuelle, puis y déposer les réponses.

Toutes les commandes et sorties demandées doivent être copiées dans le fichier `reponses_pratique.md` du dépôt.

### 2.1 Clonage du dépôt (5 points)

1. Dans un dossier de travail, cloner le dépôt GitHub indiqué.  
   - Copier/coller la commande `git clone ...` utilisée.
   - Indiquer dans `reponses_pratique.md` le nom du dossier créé par le clonage.

2. Entrer dans le dossier cloné.  
   - Copier/coller la commande utilisée.

### 2.2 Création d’une branche individuelle (10 points)

Objectif : une branche par élève pour déposer les réponses.

3. Vérifier la branche active au départ.  
   - Copier/coller la commande utilisée pour afficher la branche courante  
     (par exemple via `git status` ou une autre commande adaptée).

4. Créer une nouvelle branche à son nom (par exemple : `prenom-nom`).  
   - Copier/coller la commande `git branch ...` ou `git switch -c ...` utilisée.

5. Basculer sur cette nouvelle branche.  
   - Copier/coller la commande utilisée (`git checkout ...` ou `git switch ...`).

6. Vérifier que la branche active est bien la branche personnelle.  
   - Copier/coller la commande utilisée.
   - Copier/coller la ligne de sortie montrant le nom de la branche active.

### 2.3 Ajout et commit des réponses (10 points)

7. Compléter les fichiers indiqués (au minimum `reponses_theorie.md` et `reponses_pratique.md`) avec les réponses.

8. Afficher l’état du dépôt.  
   - Copier/coller la commande `git status`.
   - Copier/coller les lignes montrant quels fichiers ont été modifiés.

9. Ajouter les fichiers modifiés à l’index (staging).  
   - Copier/coller la commande `git add ...` utilisée pour préparer le commit.

10. Créer un commit avec un message clair, par exemple :  
    `Réponses évaluation Git - prenom nom`  
    - Copier/coller la commande `git commit -m "..."`.
    - Copier/coller les lignes principales de sortie du commit (fichiers changés, insertions, etc.).

11. Vérifier que l’arborescence de travail est propre.  
    - Copier/coller la commande `git status`.
    - Copier/coller la ligne contenant `working tree clean`.

> Optionnel (à utiliser seulement si le contexte le permet) :  
> 12. Si les droits d’écriture sur le dépôt distant sont disponibles, pousser la branche individuelle vers GitHub avec la commande appropriée (`git push`), puis indiquer dans `reponses_pratique.md` la commande utilisée.

---

## Barème proposé (total /40)

- Partie 1 – Théorie : /15  
- Partie 2 – Manipulation du dépôt GitHub : /25  
  - 2.1 Clonage : /5  
  - 2.2 Branche individuelle : /10  
  - 2.3 Ajout + commit des répo
