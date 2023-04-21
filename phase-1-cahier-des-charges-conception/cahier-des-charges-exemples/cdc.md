# Cahier des charges démo

## Contexte 

>Concepts. Description de l'existant

>Composition du projet: les différents composants (rester général). Une application qui gere ceci, un site web qui expose cela, une base de données, etc.


## Objectifs

>définition des objectifs du produit. Pour chaque objectif: énoncé, bénéfices attendus, indicateurs de mesure.

## Acteurs (*rôles*)

>*utilisateurs* du système/rôles (diagramme d'acteurs)

Un acteur est externe au système par définition.

- Le système rend service à qui ? A qui est destiné le système
- Relations entre rôles

## Périmètre du système et cas d'utilisation

>(diagramme de cas d'utilisation), interfaces avec d'autres systèmes

## Règles métiers (ou règles de gestion)

Dérive des lois, règlements, procédures, bonnes pratiques dans un métier donné, règles de calcul (ex: RGPD). 

Exemples: 

- *Si la date du jour est supérieure à la date de consommation, le produit est périmé.* 
- *Le pharmacien doit analyser la prescription médicale avant de délivrer un médicament à un·e patient·e.*

## Description des cas d'utilisation

>Fournir une description textuelle du cas d'utilisation principal de votre projet. On fournira une description textuelle du cas d'utilisation (tous les scenarios possibles: scenario nominal+scenarios alternatifs) et une description textuelle du scenario nominal (un seul scenario, données fixées à l'avance, équivalent à un test)

## Exigences fonctionnelles

>Reprendre les cas d'utilisation et les spécifier sous format texte en une liste priorisée

- Ce que votre système doit faire, comment il se comporte. 
- Elles sont organisées sous forme de liste
- Chaque exigence est priorisée
- Les exigences peuvent être regroupées sous forme d'itérations
- Laisser de côté les spécifications inutiles, optionnelles, etc. 

> Spécification: translation au format texte d'une exigence (besoin exprimé et débattu, clarifié par toutes les parties). Doit être claire et brève. Quelques templates de specifications:
> - Le système doit ...
> - Dans le cas de ..., le système doit ...
> - Dans le cas où <acteur> fait ..., le système doit ...

## Exigences *non fonctionnelles*

Objectifs *secondaires* de votre système (ou qualités du système) : architecture, dépendances, qualité, fiabilité, sécurité, etc. N'apporte pas de valeur *directement* mais indirectement (par exemple un système fiable et sécurisé va gagner en réputation et des utilisateurs)

>Exemple "Le système doit..."

## Contraintes 

- techniques (volume de données à heberger, format des données, bande passante )
- performances
- **Contraintes imposées par l'école** (pré-requis pour valider les compétences, et utilisation d'un langage orienté objet)

## Prestations attendues

- Planning prévisionnel
- Installation (comment déployer votre système => README de votre dépôt)
- Documentation technique (vos diagrammes UML, autre docs)
  
## Annexes

- Liste des abréviations et des conventions
- **Dictionnaire des données** (pour conception de la base de données)
- Lien vers votre dépôt
- Compte rendus de vos réunions (CR). Un CR contient au moins
  - date
  - lieu
  - durée réunion
  - personnes présentes
  - ordre du jour (de quoi on parle)
  - résumé des décisions prises sur chaque point de l'ordre du jour
  - actions à mener (ce que chacun doit faire pour réaliser les décisions)
  - commentaires: ce qu'il s'est bien passé ou non
- Lien vers votre suivi des tâches si vous en utilisez un (Trello, etc.)
- Stack technique: les outils utilisés (avec leurs versions) pour chaque partie de votre système