# ft-transcendence
Projet final du tronc commun 42 : une application web de jeu de Pong en temps réel, multijoueur, avec tournois et matchmaking. ft_transcendence couvre le développement web complet (frontend, backend, base de données, sécurité, websockets) et la conteneurisation avec Docker.

# 🏓 ft_transcendence

Plateforme de jeu Pong en ligne, jouable en temps réel, avec système d'authentification complet.

![Status](https://img.shields.io/badge/status-terminé-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📖 À propos

Transcendence est le projet final du cursus 42. L'objectif : reproduire le jeu Pong sous forme d'application web moderne, jouable en multijoueur en temps réel, avec une authentification sécurisée et un déploiement entièrement conteneurisé via Docker.

## ✨ Fonctionnalités

- 🎮 Jeu de Pong jouable en temps réel (1v1)
- 🔐 Authentification (inscription, connexion, déconnexion)
- 👤 Gestion de profil utilisateur
- 🌐 Communication en temps réel via WebSockets
- 🐳 Déploiement complet via Docker Compose

## 🛠️ Stack technique

- **Backend** : Django (Python)
- **Frontend** : JavaScript, HTML, CSS
- **Base de données** : PostgreSQL
- **Authentification** : JWT
- **Conteneurisation** : Docker, Docker Compose

## 🚀 Installation

### Prérequis

- Docker
- Docker Compose

### Étapes

```bash
git clone https://github.com/votre-user/ft_transcendence.git
cd ft_transcendence
cp .env.example .env
docker compose up --build
```

L'application est accessible sur :

```
http://localhost:8000
```

## ⚙️ Configuration

Le fichier `.env` contient les variables suivantes :

```env
DB_NAME=transcendence
DB_USER=admin
DB_PASSWORD=changeme
JWT_SECRET=changeme
```

## 🎮 Comment jouer

1. Créer un compte ou se connecter
2. Lancer une partie contre un autre joueur
3. Déplacer sa raquette avec `↑` / `↓` ou `W` / `S`
4. Le premier joueur à atteindre le score limite gagne la partie

## 📂 Structure du projet

```
ft_transcendence/
├── backend/
├── frontend/
├── docker-compose.yml
├── .env.example
└── README.md
```

## 👥 Auteur

Projet réalisé dans le cadre du cursus **42**.

## 📜 Licence

Distribué sous licence MIT — voir le fichier `LICENSE`.
