# Formation d'initiation à la télédétection sur logiciel libre

## Présentation de la ressource pédagogique

Ce document est un support pédagogique d’initiation à la manipulation d’images satellites d’observation de la Terre. L’objectif est de fournir quelques clés pour appréhender ce type de données sur des logiciels informatiques dédiés libres et à code source ouverts (free and open source software), via un cas d’utilisation classique en télédétéction spatiale : la cartographie l’occupation/utilisation du sol.

Nous proposons d’utiliser le logiciel QGIS comme interface principale de visualisation des données et de paramétrisation des algorithmes, tout en “augmentant” ses fonctionnalités de base grâce à sa capacité à intégrer de nombreuses librairies spatiales externes.

Plus spécifiquement, nous utilisons les logiciels et librairies suivantes :

* QGIS v3.10
* SAGA v7.4.0
* La chaine de traitements Sen2cor v2.5.5 et l’extension QGIS Sen2Cor Adapter

Les images satellites manipulées sont des produits Sentinel-2 au niveau 1C ainsi que le modèle numérique de terrain Shuttle Radar Topography Mission (SRTM). Ces produits sont en libre accès et disponibles sur l’ensemble de la surface terrestre.

Prérequis pour aborder sereinement le document: concepts de bases en SIG et télédétéction, utilisation basique de QGIS (ouvrir et manipuler des données vectorielles et rasterisées sur QGIS)

Mots clés : télédétéction spatiale, Sentinel 2, occupation du sol, classification supervisée orientée pixel

**Note importante n°1** : Avant de commencer le tutoriel, veillez à installer et configurer l’ensemble des logiciels utiles ! Rendez-vous à l’annexe n°1 pour un guide d’installation et de configuration des logiciels.

**Note importante n°2** : Les jeux de données mentionnées dans ce tutoriel sont fournies aux personnes formées. Afin de contrôler si les données générées aux différentes étapes du tutoriel sont conformes à ce qui est attendu, l’ensemble des données intermédiaires est également fourni.

## Liens vers la ressource pédagogique

La ressource pédagogique (incluant les données nécessaires pour l'exercice) est disponible à l'adresse suivante : https://doi.org/10.5281/zenodo.7224864

Site internet : https://ptaconet.github.io/formation_initiation_teledetection/

## Citation

Paul Taconet. (2022, octobre 19). Support pédagogique : initiation à la télédétection spatiale sur logiciel libre. Zenodo. https://doi.org/10.5281/zenodo.7224864

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
