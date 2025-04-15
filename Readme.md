# Projet PRO3 - Atelier DevOps

## Description

Ce projet a été réalisé dans le cadre de l'atelier L3 MIAGE DevOps animé par [Nicolas Lebacq](https://github.com/SmashingQuasar)

## Membres du groupe

| Nom               | Prénom            |
|-------------------|-------------------|
| DU                | Alexandre         |
| Ouamer Ali        | Nazim             |
| Leng              | Antoine           |
| Guilavogui        | Henry Pamphil     |
| Lakrouz           | Sarah             |
| Zouane            | Amina             |
| El Hassouni       | Imad              |
| Ait Ahcene        | Amélia            |


### Prérequis 
- Lancer Docker Desktop
- Être sous Linux (WSL / Debian / Ubuntu)

### Étape 0: Accèder au fichier de démarrage
```bash
cd _ops/scripts
```
### Étape 1: Démarrer le service
```bash
./up.sh
```
### Étape 2: Tester l'accès
```bash
curl -k http://localhost:80
```

### Étape 3: Arrêter le service
```bash
./down.sh
```