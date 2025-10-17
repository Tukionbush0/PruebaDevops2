# PruebaDevops2
# Evaluación DevOps - Node.js + Docker


## Qué hace este proyecto


Este repositorio contiene:
- Un workflow de GitHub Actions (`.github/workflows/ci.yml`) que instala dependencias, ejecuta tests, ejecuta ESLint, analiza dependencias con Snyk, hace un scan con SonarCloud, construye una imagen Docker y la sube a Docker Hub.
- Un `docker-compose.yml` que levanta 3 contenedores: `app` (imagen desde Docker Hub), `db` (MySQL) y `phpmyadmin`.


## Requisitos previos
- Tener Docker y Docker Compose instalados en tu máquina.
- Tener una imagen en Docker Hub 


## Cómo ejecutar localmente
1. Clona el repositorio 
