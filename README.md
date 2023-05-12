# Suivi de projet - spé DEV


- [Suivi de projet - spé DEV](#suivi-de-projet---spé-dev)
  - [Compétences à valider](#compétences-à-valider)
  - [Soutenance](#soutenance)
  - [Livrables attendus](#livrables-attendus)
  - [Pré-requis *minimum* du projet du point de vue technique](#pré-requis-minimum-du-projet-du-point-de-vue-technique)
  - [Programme](#programme)
  - [Planning](#planning)
  - [Équipes](#équipes)
  - [Modules d'enseignement envisagés pour couvrir les compétences](#modules-denseignement-envisagés-pour-couvrir-les-compétences)
  - [Modules supplémentaires, suggérés](#modules-supplémentaires-suggérés)
  - [Suggestions](#suggestions)
    - [Applis web](#applis-web)
    - [IA de jeu](#ia-de-jeu)

## Compétences à valider

UF *Spé INGENIERIE LOGICIELLE et Base de données*

- Architecture logicielle
  - effectuer des choix technologiques et respecter leurs conventions
  - maîtriser les Design Patterns
  - maîtriser l’utilisation d’un ORM
- Architecture Micro-services (REST)
  - maîtriser la séparation des responsabilités
  - concevoir une web API RESTful
- Développement aynschrone (Websocket, JS asynchrone)
  -  détecter les situations ayant besoin de l’asynchrone
  -  construire autour d’informations asynchrones
- Bas niveau / Machine learning
  - réaliser un défi technique

## Soutenance

Le projet sera soutenu devant un jury.

## Livrables attendus

- Dépôt GIT de votre logiciel à jour (code source, historique des commits) documenté avec un README;
- Cahier des charges;
- Exécutable de vos logiciels;
- Slides de votre présentation.

## Pré-requis *minimum* du projet du point de vue technique

- Architecture en *services* (IHM, API)
- Utiliser au moins 3 *Design Patterns* de manière *utile*
- Une BDD (relationnel ou pas que)
- Utiliser un ORM ou un ODM (Object Document Mapping), un composant d'interface entre la base de données et le code applicatif
- Utiliser au moins un langage orienté objet (côté front-end ou back-end)
- *Défi* technique : sortir des sentiers batus des concepts abordés en cours (techno, process, sécurité, etc.)

## Programme

[Voir le programme](./programme.md) (grandes étapes du module pour faire avancer le projet)

## Planning

[Voir le planning](./planning.md) (ordres du jour, livrables pour la prochaine fois)

## Équipes

[Voir les équipes](./groupes.md) (composition des équipes, type de projet, URLs des dépôts)

## Modules d'enseignement envisagés pour couvrir les compétences

- *Exigences et conception*: 
  - [Élaboration d'un document cahier des charges](./phase-1-cahier-des-charges-conception/index.md)
  - [Outils de conception UML](./modules/conception/README.md) : rappels, du bon usage de ces outils, diagramme des cas d'utilisation, description textuel des cas d'utilisation/scénarios,diagramme d'états transition, diagramme d'activités
- *Gitflow*: remise à niveau et consolidation Git et Gitflow (git branching models)
- *Architecture logicielle*: Rappels sur le concept d'interface et les principes SOLID, quelques design patterns (POO Avancé), design pattern MVC pour le web, définition et usage d'un ORM, architecture en couches / architecture Hexagonale: théorie et pratique => Évaluation: mini projet à rendre sur un dépôt (à faire seul)
- *Architecture Micro-services*: concevoir et développer une API *RESTful* basé sur les standards du web (avec nodejs) => Évaluation : QCM
- *Développement aynschrone*: Introduction aux protocoles SSE/Websocket/Mercure => mini projet à rendre sur un dépôt (à faire seul)

## Modules supplémentaires, suggérés

- *Standard SQL et conception d'une base de données relationnelle* (du MCD au schéma de la base)
- *Différents aspects de sécurité*: les differents types de sécurité, identification/authentification/autorisation, démo attaques CSRF/XSS, démo JWT et fonctionnement, Same Origin Policy et Cors
- *Algorithmes de pathfinding*: Breadth First Search, Dijkstra’s Algorithm, A*. Présentation et implémentations
- *Introduction à la génération procédurale* (génération de heightmaps, de dongeons, etc.)
- *Veille personnelle*
- *Fondamentaux de l'écriture technique* (tutoriel, documentation, pitch, story)

## Suggestions

### Applis web

- Site d'un cinéma (consulter les films, ajouter les sorties, connexions API avec les sorties de film, reservation et paiement en ligne, horaires)
- Application de reservation de terrains de badminton, tennis etc. (créneaux horaires, planing)
- Application de information/reservation de billets de concerts
- Site éditorial (média) avec une partie blog (participation des utilisateur·ices)
- Plateforme de partage et publication de vidéos
- Site web de documentation/échange/communauté (wiki/réseau social) sur des sujets de niche (instruments électroniques, MAO, etc.)
- Reproduire le site web d'un service : (CPAM, Laposte, SNCF, etc.)
- Système de gestion de stocks, de flux d'un entrepôt
- Système de gestion de transports publics (bus, vélos, trains, avions, etc.)
- Système de gestion de paie, comptabilité
- Application GPS (itinéraires de randos a pied, moto, etc.) avec utilisation de fonds de cartes
- Application de client mail
- Application web d'édition vidéo/audio (banc de montage, filtre audio, filtres vidéo, etc.)

### IA de jeu

- Génération procédurale de terrain/niveaux, histoires et personnages (story telling)
- Algorithmique: marche aléatoire, tirage dans des distributions aléatoires, arbres de décision, automate cellulaire, etc.
- Modélisation mathématique: dynamique de populations, moteur physique (gravité, frottement, écoulements de liquide/grains, contacts et collisions, transfert de chaleur, etc.), système économique, modélisation météo, etc.

