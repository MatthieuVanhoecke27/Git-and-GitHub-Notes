# 🌿 Introduction à Git et GitHub

> Notes personnelles et guide de référence couvrant les fondamentaux du contrôle de version, les commandes Git, les workflows de collaboration GitHub et les bonnes pratiques.

---

## 📚 Contenu

### Partie I — Commandes de terminal
- `diff`, `wdiff`, `patch` pour comparer et appliquer des modifications entre fichiers
- Système de contrôle de versions (VCS) : définition, objectifs et structure

### Partie II — Git
- Configuration initiale : `git config`
- Création et récupération d'un dépôt : `git init`, `git clone`
- États des fichiers dans Git : modifié → staged → commité
- Suivi et ajout des fichiers : `git add`, `git status`
- Visualisation des modifications : `git diff`, `git diff --staged`
- Validation des modifications : `git commit`, `git commit -a -m`
- Historique des commits : `git log`, `git show`
- Renommer et supprimer des fichiers : `git mv`, `git rm`
- Annuler des changements : `git checkout`, `git reset`, `git commit --amend`
- Rollbacks : `git revert`
- Branches : créer, basculer, supprimer (`git branch`, `git checkout -b`)
- Fusion de branches et gestion des conflits
- Algorithme de fusion à trois voies et fast-forward

### Partie III — GitHub
- Interactions de base : `git clone`, `git push`, `git pull`
- Dépôts distants : `origin`, `git remote`, `git fetch`
- Branches locales et distantes après un clone
- Secure Shell (SSH) : génération de clés, authentification, bonnes pratiques
- API Keys : définition, utilisation, sécurité
- Résolution des conflits : workflow Pull-Merge-Push
- Push de branches : `git push -u origin`
- Rebaser ses modifications : `git rebase`

### Partie IV — Collaboration
- Pull Requests : via l'interface web et en local
- Mise à jour et squash de commits (`git rebase -i`, `git push -f`)
- Code Reviews : workflow, bonnes pratiques, commentaires en ligne
- Gestion de projet : GitHub Issues, lien issues et pull requests
- Intégration Continue et Déploiement Continu (CI/CD)
- Glossaire des termes clés


## 💡 Commandes essentielles

| Commande | Description |
|---|---|
| `git init` | Initialiser un nouveau dépôt local |
| `git clone <url>` | Cloner un dépôt distant |
| `git add` / `git commit` | Stager et enregistrer des modifications |
| `git push` / `git pull` | Synchroniser avec le dépôt distant |
| `git branch` / `git checkout` | Créer et basculer entre les branches |
| `git merge` / `git rebase` | Intégrer les modifications d'une branche |
| `git revert` | Annuler un commit en toute sécurité |
| `git log --graph --oneline` | Visualiser l'historique des commits |



## 👤 Auteur

**Matthieu Vanhoecke**
- GitHub : [@your-username](https://github.com/your-username)
- LinkedIn : [your-linkedin](https://linkedin.com/in/your-linkedin)
