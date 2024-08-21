# Simulation Parc Informatique

## Description
Conception et simulation d'un réseau pour trois bâtiments (A, B, DG) sur Packet Tracer. Le projet inclut la gestion des adresses IPv6, l'optimisation de la bande passante, l'interconnexion des bâtiments, et la mise en œuvre de politiques de sécurité avancées pour une infrastructure efficace et sécurisée.

## Problématique
Le projet vise à résoudre les limitations en termes de débit de connexion dans un environnement avec plusieurs postes clients. La solution proposée consiste à fournir un accès aux différents services web externes tout en respectant les spécifications fonctionnelles.

## Spécifications fonctionnelles
- **Nombre de postes clients :** 10 par salle
- **Nombre de salles :** 3 par bâtiment
- **Nombre de bâtiments :** 3
- **Types de connexions :** Filaire/Wi-Fi
- **Nombre de lignes entrantes :** 3 (ADSL 40 Mo, Fibre 2 Mo, Fibre 100 Mo)

### Conditions supplémentaires :
- Les lignes entrantes convergent vers la salle serveur.
- Chaque bâtiment a son propre réseau LAN.
- Chaque poste connecté au bâtiment A doit avoir une connexion limitée à 5 Mo.
- Chaque poste connecté au bâtiment B doit avoir une connexion limitée à 10 Mo.
- Chaque poste connecté au bâtiment B en Wi-Fi doit avoir une connexion limitée à 5 Mo.
- Chaque poste connecté au bâtiment A ne peut pas se connecter aux réseaux sociaux.
- Chaque poste connecté au bâtiment B ne peut pas effectuer des téléchargements volumineux dépassant 1Go.

Un troisième bâtiment en construction ayant la même structure que le bâtiment B interconnecte les deux bâtiments A et B et dispose d’une salle serveur.

- Un routeur au niveau de cette salle serveur permet la communication inter-bâtiment et limite l’accès aux serveurs pédagogiques, comptabilité et stockage qu’aux directeurs du bâtiment DG.





## Langages et technologies
- **Outils de simulation :** Cisco Packet Tracer

## Installation
```bash
git clone https://github.com/HAMZA25032005/simulation_parc_informatique.git
