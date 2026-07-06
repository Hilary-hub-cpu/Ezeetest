# Ezeetest

Plateforme Ezeetest : bibliothèque numérique de ressources pédagogiques, avec authentification, espace communautaire et assistant IA.

Projet réalisé dans le cadre d'un stage académique (Lot 1, V1).

## Stack technique

- Python 3.12
- Django 5
- Django REST Framework
- PostgreSQL 16
- Celery + Redis (tâches asynchrones)

## Structure du dépôt

- `backend/` : API Django REST Framework, base de données, logique métier
- `frontend/` : interface utilisateur (HTML, Tailwind CSS, JavaScript)

## Installation locale (backend)

\`\`\`bash
cd backend
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
cp .env.example .env
python manage.py migrate
python manage.py runserver
\`\`\`

## État d'avancement

- [x] Structure du dépôt (backend / frontend)
- [ ] Environnement Django et connexion PostgreSQL
- [ ] Authentification
- [ ] Bibliothèque de ressources
- [ ] Recherche
- [ ] Téléchargement
- [ ] Communauté
- [ ] Assistant IA
- [ ] Contact / pages institutionnelles / back-office

## Auteurs

Hilary (backend) et Laurine (frontend) — Stage académique 2026