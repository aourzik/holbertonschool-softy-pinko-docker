# Holbertonschool-softy-pinko-docker

Ce projet retrace l'apprentissage et la mise en œuvre progressive de l'écosystème **Docker** au sein d'une architecture applicative Web (Full-Stack). L'objectif est de comprendre comment conteneuriser une application, gérer la communication inter-conteneurs, orchestrer les services avec **Docker Compose**, implémenter un **Reverse Proxy (Nginx)** et appliquer du **Load Balancing**.

---

## 🚀 Structure du Projet

Le projet est découpé en 7 étapes distinctes (Task 0 à Task 6) illustrant l'évolution de l'infrastructure.

```text
.
├── task0/                # Base Ubuntu - "Hello, World!" via CMD
├── task1/                # API Flask basique sous Ubuntu (Port 5252)
├── task2/                # Séparation Back-end / Front-end (Nginx sur Port 9000)
├── task3/                # Intégration de CORS et requêtes dynamiques AJAX
├── task4/                # Orchestration des deux services via Docker Compose
├── task5/                # Ajout du Reverse Proxy (Nginx sur Port 80)
└── task6/                # Répartition de charge (Horizontal Scaling)
