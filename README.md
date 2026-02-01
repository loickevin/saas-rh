# SaaS RH – Open Source (Tech Hardcore)

## 🚀 Vision
Construire un **SaaS RH open source**, **scalable**, **orienté automatisation**, pensé pour des environnements réels (PME, cabinets RH, Afrique & international).

Objectif : une plateforme RH moderne basée sur **Django + Docker + n8n**, capable de gérer le **recrutement (ATS)**, les **process RH**, et l’**automatisation métier**, avec une vraie architecture SaaS multi-tenant.

⚠️ Ce projet n’est **pas un tutoriel**.  
C’est un **produit réel**, conçu avec des standards professionnels.

---

## 🧠 Principes techniques
- Architecture **SaaS multi-tenant**
- API-first (**Django Rest Framework**)
- Automatisation via **n8n** (webhooks, workflows)
- Conteneurisation complète avec **Docker / Docker Compose**
- Séparation claire des responsabilités (backend, infra, automation)
- Code lisible, structuré, documenté, testable

---

## 🧱 Stack technique

### Backend
- Python 3.11+
- Django 4+
- Django Rest Framework
- PostgreSQL
- Redis
- Celery (async tasks)

### Infra / DevOps
- Docker
- Docker Compose
- Nginx (reverse proxy)
- Gunicorn

### Automatisation
- n8n
- Webhooks Django ↔ n8n
- Email / WhatsApp (prévu)

### Frontend (phase suivante)
- Flutter Web (ou React – discussion ouverte)

---

## 📦 Modules (Roadmap)

### MVP – ATS (en cours)
- Gestion des offres d’emploi
- Candidatures
- Statuts candidats
- Notifications automatiques
- Parsing CV (prévu)

### RH Core
- Dossiers employés
- Documents RH
- Congés & absences

### SaaS
- Multi-entreprises
- Rôles & permissions
- Abonnements & billing

---

## 🗂️ Architecture simplifiée

```text
[ Client (Web / Mobile) ]
          ↓
[ Django API ]  ←→  [ n8n ]
          ↓
[ PostgreSQL ]
