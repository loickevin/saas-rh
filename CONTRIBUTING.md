# Contribuer au projet

Merci de ton intérêt pour contribuer à ce projet 🎉
Toute aide est la bienvenue : code, documentation, tests, idées, ou retours.

---

## 🧭 Objectif du projet

Ce projet vise à construire une plateforme SaaS moderne, basée sur :

* **Backend** : Django / Django REST Framework
* **Orchestration** : Docker & Docker Compose
* **Automatisation** : n8n

L’objectif est d’avoir une base propre, maintenable et collaborative.

---

## 🛠️ Prérequis techniques

Avant de contribuer, assure‑toi d’avoir installé :

* Git
* Docker & Docker Compose
* Python 3.10+
* (Optionnel) Node.js si nécessaire pour certains outils

---

## 🚀 Installation en local

1. Fork le dépôt
2. Clone ton fork :

```bash
git clone https://github.com/ton-username/nom-du-repo.git
cd nom-du-repo
```

3. Crée ton fichier `.env` à partir de l’exemple :

```bash
cp .env.example .env
```

4. Lance le projet :

```bash
docker compose up --build
```

---

## 🌱 Bonnes pratiques de contribution

### Branches

* `main` : stable (ne pas push directement)
* `develop` : intégration
* `feature/nom-feature`
* `fix/nom-bug`

### Commits

Merci d’utiliser des messages clairs :

```
feat: ajout du module de gestion des utilisateurs
fix: correction de l’erreur de migration
refactor: nettoyage de la logique d’authentification
```

---

## 🧪 Tests

* Ajoute des tests quand c’est pertinent
* Vérifie que le projet démarre sans erreur avant de proposer une PR

---

## 📦 Docker & n8n

* Les fichiers Docker **doivent être versionnés**
* Ne jamais committer de secrets (`.env`, mots de passe, clés API)
* Les workflows n8n peuvent être :

  * exportés en JSON
  * documentés dans le dossier `n8n/`

---

## 🔁 Pull Requests

Avant d’ouvrir une PR :

* Le code est fonctionnel
* Les migrations sont incluses si nécessaire
* La PR est liée à une issue (si possible)

Format recommandé :

```
### Description

### Type de changement
- [ ] Bug fix
- [ ] Nouvelle fonctionnalité
- [ ] Refactor
- [ ] Documentation

### Checklist
- [ ] Le projet démarre
- [ ] Aucun secret n’est exposé
```

---

## 🐛 Signaler un bug

Merci d’ouvrir une issue avec :

* Description claire
* Étapes pour reproduire
* Logs ou captures si possible

---

## 💬 Communication

* Discussions GitHub
* Issues
* (À venir) Discord / WhatsApp

---

Merci encore pour ta contribution 🙌
Ensemble, on construit quelque chose de solide 🚀
