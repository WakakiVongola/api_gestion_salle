# API de Gestion Intelligente des Salles de Réunion

Ce projet est une API REST qui permet la gestion intelligente des salles de réunion pour l’entreprise WorkEase.  
Elle gère les réservations, applique des contraintes dynamiques et sécurise l’accès selon les rôles utilisateur.

## Stack technique

- Node.js / Express
- Prisma (ORM) + PostgreSQL
- Docker / Docker Compose
- Zod (validation)
- JWT (authentification)
- BcryptJS (hashing mots de passe)

---

## 1. Lancer le projet

### Prérequis

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) installé sur votre machine.

### Initialisation

```bash
# Clonez ce repo
git clone https://github.com/WakakiVongola/api_gestion_salle.git

# Lancez les services (API + BDD)
docker-compose up --build
    