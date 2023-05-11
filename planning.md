# Planning : du 20/04/23 au 11/07/23

Le planning prévisionnel du module. Définit les objectifs de chaque séance et des livrables/travail attendu au début de la séance suivante.

- [Planning : du 20/04/23 au 11/07/23](#planning--du-200423-au-110723)
  - [11/05/23 :](#110523-)
    - [Ordre du jour](#ordre-du-jour)
    - [A faire pour le 12/05/23](#a-faire-pour-le-120523)
  - [20/04/23 : Premier jour](#200423--premier-jour)
    - [Ordre du jour](#ordre-du-jour-1)
    - [A faire (pour le 11/05/23)](#a-faire-pour-le-110523)
    - [Prochaine séance](#prochaine-séance)
  - [Ressources](#ressources)

## 11/05/23 :

### Ordre du jour

- Revoir des outils de conception (diagrammes d'activités, états/transition)
- Finir le cahier des charges
- Démarrer l'implémentation du cas d'utilisation principal. Itération et allers/retours conception/implémentation

### A faire pour le 12/05/23

- Livrer une première version du cahier des charges. Il sera validé ou non
- Proposer un premier planning: définir le contenu d'une première itération (ensemble d'exigences fonctionnelles) à réaliser (implémenter) pour la prochaine fois, le **19/06/23**. 
- Chaque groupe présentera (5min) une démo de l'état de leur projet en début de séance

## 20/04/23 : Premier jour

### Ordre du jour

Démarrer le projet, définir le cahier des charges et le périmètre du projet, commencer la conception. Ce travail permettra notamment de valider le projet pour l'UE (respect des contraintes imposées)

- Présenter le référentiel du projet (consignes, contraintes, types de projet)
- Former les groupes
- Chaque groupe définit un projet
- Création d'un dépôt principal pour chaque projet
- Premiere phase: exigences et début de la conception
  - Version initiale du cahier des charges
  - concepts/objectifs
  - Diagramme cas d'utilisation
  - Acteurs
  - Description textuelle des CU
  - Dictionnaire des données

### A faire (pour le 11/05/23)

- URL du dépot (ou dépôt point d'entrée si plusieurs dépôts) à envoyer à l'adresse paul.schuhmacher@ynov.com
- Le dépôt doit contenir :
  - une première version du cahier des charges
  - description textuelle du cas d'utilisation principal (tous les scenarios: nominal + alternatifs)
  - Pour le cas d'utilisation principal :
    - description textuelle du scenario nominal (toutes les données sont fixées à l'avance) 
    - description textuelle d'un scenario alternatif (cas d'erreur, mauvais input, annulation de la part de l'utilisation, toutes les données sont fixées à l'avance) 
  - dictionnaire des données ([voir un exemple ici](https://www.univ-constantine2.dz/CoursOnLine/Benelhadj-Mohamed/co/grain3_2.html)): un tableau recensant les données atomiques manipulées par votre système. Voici les colonnes de ce tableau: *Code*, *Label/désignation*, *Type (Alphabetique (A), Numerique (N), AlphaNumerique (AN), Date (D), Booleen (B))*, *Taille*, *Remarque*. Étape indispensable pour la conception de la base de données et vérifier que vos modèles de données (côté applicatif) sont cohérents et complets. Sert de base pour échanger. Elimine les redondances et lève les ambiguités sur des concepts métiers

> Tous ces documents vont subir des modifications, être revisités, améliorés. Essayer de garder trace de l'historique des modifications (dans un commit bien défini par exemple)

### Prochaine séance 

- Mise à niveau Git et Git branching models
- Éléments de conception (diagrammes d'activités, états/transition, classes)
- Continuer la conception et démarrer l'implémentation du cas d'utilisation principal. Itération et allers/retours conception/implémentation

## Ressources