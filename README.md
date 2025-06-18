# devops : student_list

Ce projet est une preuve de concept (POC) pour démontrer l'utilisation de Docker dans le déploiement d'une application composée d'une API Flask et d'une interface web PHP.

## 🧱 Structure du projet

- `Dockerfile` – Construction de l'image pour l'API Flask.
- `docker-compose.yml` – Orchestration des services (API + site web).
- `requirements.txt` – Dépendances Python pour l'API.
- `student_age.py` – API Flask qui renvoie une liste d'étudiants.
- `student-age.json` – Fichier JSON des données étudiantes.
- `index.php` – Interface web PHP consommant l'API.

## 🚀 Déploiement

Lancement de l'infrastructure :
```bash
docker-compose up --build
