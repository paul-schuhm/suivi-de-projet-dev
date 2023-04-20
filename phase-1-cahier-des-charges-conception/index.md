## Vers le "cahier des charges"

### Élaboration

**Exigences** => **conception** => réalisation (implémentation) => (tests) => exploitation/mise en production => maintenance

### Concepts

- Besoin : ressenti par une personne, exprimé plus ou moins clairement. Passés sous silence
- Exigence : besoin qui a été discuté, notion de consensus, cible à atteindre. Mesurable, vérifiable
- Specification : écrire l'exigence sous la forme d'un texte court, concis et clair. Traduction d'une exigence en *langage* convenu entre le client et le fournisseur

Un cahier des charges : ensemble de spécifications.

Un *bon* cahier des charges : 

- document *facile à lire*, établi sur la base d'un consensus
- fait office de *contrat* moral entre les parties (en situation réelle on y adjoint un *contrat*)
- facile à maintenir et à modifier

#### Risques

- bien *contrôler* les modifications
- *surspecifier* (donner trop de détails)
- *sous-specifier* (en donner pas assez)

## Template de cahier des charges

1. **Contexte** : Concepts. Description de l'existant
2. **Objectifs** : définition des objectifs du produit. Pour chaque objectif: énoncé, bénéfices attendus, indicateurs de mesure.
3. **Acteurs**: *utilisateurs*/rôles (diagramme d'acteurs)
4. **Périmètre du système**: (diagramme de cas d'utilisation), interfaces avec d'autres systèmes
5. **Règles métiers** (ou règles de gestion): dérive des lois, règlements, procédures, bonnes pratiques dans un métier donné, règles de calcul (ex: RGPD). Exemple: *Si la date du jour est supérieure à la date de consommation, le produit est périmé.* *Le pharmacien doit analyser la prescription médicale avant de délivrer un médicament à un·e patient·e.*
6. **Description textuelle des cas d'utilisation**
7. **Exigences fonctionnelles** : ce que votre système doit faire, comment il se comporte. Organisé sous forme de liste priorisée.
8. **Exigences *non fonctionnelles***: qualité, fiabilité, sécurité 
9. **Contraintes** : techniques, performances
10. **Prestations attendues**
    1.  Planning
    2.  Installation (comment déployer votre système => README de votre dépôt)
    3.  Documentation technique (diagrammes UML)
11. **Annexes**
    1.  Liste des abréviations et des conventions
    2.  **Dictionnaire des données** ,=> conception de la base de données

> Ce document servira à valider votre projet.

## Démo

[Un cahier des charges démo](./cahier-des-charges-exemples/cdc.md), avec instructions

## Outils

- Dessiner, exporter des diagrammes UML facilement: [Umlet](https://www.umlet.com/)

## Références