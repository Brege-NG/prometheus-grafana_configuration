#  Installation de Prometheus, Grafana, Node Exporter et Blackbox Exporter avec Docker Compose

## Prérequis

Avant de commencer, assurez-vous d'avoir installé :

- **Docker**
- **Docker Compose**

##  Étapes d'Installation

### 1. Créer un Répertoire de Projet

Créez un répertoire pour votre projet et accédez-y :

```bash
mkdir monitoring-stack
cd monitoring-stack

### 2. Créer les différent fichier .yml


```bash
nano prometheus.yml
nano blackbox.yml
nano node_exporter.yml
nano docker-compose.yml

### 3. Exécuter le docker-compose

```bash

docker-compose up -d
