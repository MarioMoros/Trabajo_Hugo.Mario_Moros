---
weight: 4
title: "La Communication"
description: "Descriptions and examples of markdown syntaxes used in Hugo."
titleIcon: "fa-solid fa-rocket"
categories: ["Markdown"]
tags: ["Content management"]
---

# Premier Pas
L'adresse saisie dans la barre de recherche du navigateur.

Cette adresse est composée de :

|Protocole|Autorité|Port|Route|Paramètres|Fragment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|https:|//user:password@links.com|:80|/modules/dwes|?id=123&search=php|#objects-111|

# Deuxième Pas
L'adresse que nous avons saisie est évaluée par le serveur DNS, qui est chargé de rechercher une adresse IP correspondant à la page Web recherchée.

# Troisième Étape
Le routeur est chargé de demander les informations trouvées sur Internet, pour les envoyer ultérieurement aux ordinateurs qui les demandent.

# Quatrième Étape
Le protocole HTTP pour obtenir ces informations du Web pour les transférer à l'utilisateur.

# Cinquième Étape
Les informations de la page parviennent au routeur et la page Web s'affiche dans le navigateur.

***

<!-- Contour de sirène -->
``` mermaid
graph TB
    subgraph Étape 2
    b1(Routeur) --> b2(HTTP) --> b3(Navigateur)
    end
    subgraph Étape 1
    a1(URL) --> a2(DNS) --> a3(Routeur)
    end
```