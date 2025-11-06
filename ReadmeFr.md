🔥 # Commandes Git (Version Française 🇫🇷) 🔥

---

1️⃣ ## Obtenir & Créer des projets
| Commande | Description |
|----------|-------------|
| `git init` | Initialiser un dépôt Git local |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Créer une copie locale |

---

2️⃣ ## Commandes de base 
| Commande | Description |
|----------|-------------|
| `git status` | Vérifier le statut |
| `git add [nom-du-fichier.txt]` | Ajouter un fichier |
| `git add -A` | Ajouter tous les fichiers nouveaux ou modifiés |
| `git commit -m "[message de commit]"` | Valider les changements |
| `git rm -r [nom-du-fichier.txt]` | Supprimer un fichier (ou un dossier) |
| `git remote -v` | Voir le dépôt distant du fichier ou répertoire courant |

---

3️⃣ ## Branches & Fusion 
| Commande | Description |
|----------|-------------|
| `git branch` | Lister les branches (l’astérisque indique la branche active) |
| `git branch -a` | Lister toutes les branches (locales et distantes) |
| `git branch [nom de la branche]` | Créer une nouvelle branche |
| `git branch -d [nom de la branche]` | Supprimer une branche locale |
| `git push origin --delete [nom de la branche]` | Supprimer une branche distante |
| `git checkout -b [nom de la branche]` | Créer une nouvelle branche et y basculer |
| `git checkout -b [nom de la branche] origin/[nom de la branche]` | Cloner une branche distante et y basculer |
| `git branch -m [ancien nom] [nouveau nom]` | Renommer une branche locale |
| `git checkout [nom de la branche]` | Basculer vers une branche |
| `git checkout -` | Revenir à la branche précédemment utilisée |
| `git checkout -- [nom-du-fichier.txt]` | Annuler les modifications d’un fichier |
| `git merge [nom de la branche]` | Fusionner une branche dans la branche active |
| `git merge [branche source] [branche cible]` | Fusionner une branche dans une branche cible |
| `git stash` | Mettre de côté les modifications en cours |
| `git stash clear` | Supprimer toutes les entrées mises de côté |
| `git stash pop` | Appliquer la dernière mise de côté dans le répertoire de travail |

---

4️⃣ ## Partager & Mettre à jour des projets 
| Commande | Description |
|----------|-------------|
| `git push origin [nom de la branche]` | Envoyer une branche vers le dépôt distant |
| `git push -u origin [nom de la branche]` | Envoyer les changements et mémoriser la branche distante |
| `git push` | Envoyer les changements sur la branche mémorisée |
| `git push origin --delete [nom de la branche]` | Supprimer une branche distante |
| `git pull` | Mettre à jour le dépôt local avec le dernier commit |
| `git pull origin [nom de la branche]` | Récupérer les changements depuis le dépôt distant |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Ajouter un dépôt distant |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Définir l’URL SSH pour le dépôt distant |

---

5️⃣ ## Inspection & Comparaison
| Commande | Description |
|----------|-------------|
| `git log` | Voir l’historique des changements |
| `git log --summary` | Voir les changements en détail |
| `git log --oneline` | Voir les changements de façon concise |
| `git diff [branche source] [branche cible]` | Prévisualiser les changements avant fusion |

