# 🐳 Student List - Déploiement Dockerisé

Projet de preuve de concept (**POC**) pour démontrer les capacités de **Docker** à découpler, automatiser et rendre évolutive une infrastructure existante. Ce projet est réalisé pour le département **innovation** de **PO-OS**, une entreprise française spécialisée dans le développement de logiciels pour les lycées.

---

## 🎯 Objectifs pédagogiques

- Déployer une application existante dans des conteneurs séparés.
- Automatiser le déploiement via `docker-compose`.
- Suivre les bonnes pratiques Docker et sécurité.
- Mettre en place une base d’**Infrastructure as Code**.
- Stocker les images dans un registre privé Docker.

---

## 🧱 Architecture du projet

| Composant | Description |
|----------|-------------|
| **API Flask** | Fournit une liste d'étudiants à partir d’un fichier JSON avec authentification basique |
| **Frontend PHP** | Interface web HTML/PHP interrogeant l’API pour afficher la liste |

---

## 📁 Arborescence

├── api/

│ ├── Dockerfile
│ ├── requirements.txt
│ ├── student_age.py
│ ├── student-age.json
├── website/
│ └── index.php
├── docker-compose.yml
├── README.md
