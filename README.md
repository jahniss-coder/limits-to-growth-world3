# 🌍 Étude et modélisation du système sociétal avec World3

Projet scientifique encadré — INSA Rouen Normandie — 2024-2025

## Présentation

Ce projet porte sur l'étude et la modélisation de notre système sociétal présenté dans le rapport *The Limits to Growth* (Rapport Meadows).

L'objectif était dans un premier temps de comprendre le fonctionnement du modèle **World3** et les interactions entre les différents secteurs du système mondial. Nous avons ensuite reproduit plusieurs scénarios présentés dans les travaux de *The Limits to Growth* afin de mieux comprendre le comportement du modèle.

Dans un second temps, nous avons utilisé le module **Python, pyWorld3** afin de développer et simuler un nouveau scénario basé sur différentes politiques issues des Conférences des Parties (COP).

Le projet combine ainsi une étude bibliographique avec de la **modélisation et de la simulation informatique**.

---

## Objectifs

- Étudier et comprendre *The Limits to Growth* ;
- Comprendre le fonctionnement du modèle systémique World3 ;
- Étudier les interactions entre les différents secteurs du modèle ;
- Reproduire plusieurs scénarios issus des travaux de *The Limits to Growth* ;
- Utiliser Python et pyWorld3 pour modifier et simuler le modèle ;
- Développer un scénario basé sur des politiques issues des différentes COP ;
- Analyser les résultats obtenus et les limites du modèle.

---

## World3

World3 est un modèle permettant une simulation informatique du système social humain mondial, entre différents facteurs.

Ce modèle repose notamment sur cinq secteurs principaux :

- **Population**
- **Capital**
- **Agriculture**
- **Ressources**
- **Pollution**

Ces secteurs sont reliés par de nombreuses **boucles de rétroaction**. Une modification dans un secteur peut donc avoir des conséquences sur les autres composantes du système.

Il est important de prendre en compte que le modèle ne cherche pas à prédire précisément l'avenir, mais qu'il permet plutôt d'explorer différents scénarios en fonction des hypothèses et des politiques appliquées.

---

## Modélisation et simulation

La partie informatique du projet a été réalisée à l'aide de **Python et du module pyWorld3**.

Tout d'abord, nous avons commencé par étudier la structure du code et le rôle des différentes variables utilisées par le modèle. Nous avons ensuite essayé de reproduire plusieurs scénarios issus de *The Limits to Growth* afin de vérifier notre compréhension du fonctionnement de World3.

Certains scénarios modélisés semblaient éloignés du résultat attendu. Nous nous sommes donc appuyés sur un autre ouvrage des mêmes auteurs *Dynamics of Growth in a Finite World*, se focalisant exclusivement sur le code python, et permettant de reproduire les simulations originales

---

## Scénario basé sur les COP

Une partie importante du projet a consisté à construire un nouveau scénario à partir de différentes décisions et objectifs issus des COP.
Cette simulation a pour but de répondre à plusieurs questions:
- Comment le monde évoluerait-il, notamment en termes de consommation d’énergie et de ressources naturelles, si les engagements des COP étaient respectés?;
- Ces engagements sont-ils suffisants pour atteindre un état d’équilibre durable, tant sur le plan économique qu’environnemental?;
- Dans quelles mesures, ces décisions permettent-elles réellement de faire face aux défis environnementaux auxquels nous sommes confrontés?;

Afin de répondre à ces questions nous avons retenues les politiques suivantes: 

- atteindre des émissions nettes nulles à l'horizon 2075 ;
- réduire de 25 % les émissions des systèmes agroalimentaires en 2030 ;
- conserver dans le sol 60 % du pétrole et du gaz et 90 % du charbon avant 2050 ;
- réduire la production de pétrole et de gaz de 3 % par an ;
- augmenter le capital consacré aux services ;
- améliorer la productivité agricole durable ;
- limiter l'expansion agricole afin de préserver les écosystèmes.

la mise en place de ces différentes politiques ont été traduites par la modifications des variables du modèle World3 puis simulées avec pyWorld3.

---

## Ma contribution

Ma contribution principale au projet a porté sur la **modélisation et la simulation des scénarios avec pyWorld3**.

J'ai notamment travaillé sur :

- la compréhension de la structure du modèle World3 ;
- l'identification et la modification des variables nécessaires aux simulations ;
- la modélisation des différents scénarios ;
- l'implémentation des politiques du scénario basé sur les COP ;
- la simulation des scénarios avec Python / pyWorld3 ;
- l'analyse et l'interprétation des courbes obtenues ;
- la comparaison des résultats entre les différents scénarios.

Cette partie m'a permis de développer ma compréhension de la **modélisation de systèmes complexes**, de la simulation informatique et de la programmation Python.

---

## Principaux résultats

### Scénario standard

La simulation du scénario standard, correspondant à une situation où aucune modification n'est apportée au système, conduit progressivement à un **effondrement du système mondial**.

Le scénario apparaît alors viable à court terme mais ne permet pas de maintenir durablement les différents équilibres du système.

### Scénarios avec modifications

Les autres scénarios montrent que des changements sur les ressources, la pollution, la technologie ou les politiques sociales peuvent modifier fortement la dynamique du système.

Certains scénarios permettent notamment d'obtenir une situation plus proche d'un équilibre lorsque les politiques sont mises en œuvre suffisamment tôt.

### Scénario COP

L'application des politiques issues des COP à partir de 2025 produit plusieurs effets positifs :

- ralentissement de la consommation des ressources non renouvelables ;
- diminution de la pollution ;
- progression des rendements agricoles;
- évolution plus stable de la population ;
- production industrielle relativement stable;
- augmentation de la nourriture par personne à moyen terme.

Cependant, les effets obtenus restent **insuffisants à long terme**.

Nous avons également étudié l'effet d'une mise en œuvre des politiques **25 ans plus tôt**. Cette comparaison met en évidence l'importance du moment auquel les décisions sont prises.

---

## Limites du modèle

World3 constitue une représentation simplifiée d'un système mondial extrêmement complexe.

Le modèle ne prend notamment pas en compte de manière détaillée :

- les différences géographiques ;
- les différences politiques et culturelles ;
- les inégalités entre les populations ;
- certains conflits et catastrophes naturelles ;
- la complexité réelle de certains secteurs comme l'agriculture ou la santé.

De plus, pyWorld3 présente une documentation relativement limitée, simplifiant le modèle World3.

Les résultats obtenus doivent donc être interprétés comme **des scénarios permettant d'explorer des tendances**, et non comme des prédictions précises de l'avenir.

---

## Documents

### Rapport

[Consulter le rapport complet](report/Rapport_PSE_2025.pdf)

Le rapport présente l'ensemble de la démarche, de l'étude de *The Limits to Growth* jusqu'à la modélisation des scénarios et l'analyse des limites du modèle.

### Soutenance

[Consulter les slides de soutenance](presentation/Soutenance_PSE_2025_35.pdf)

### Poster

[Consulter le poster du projet](poster/Poster_PSE_2025_35.pdf)

### Document de référence

[Consulter le document de référence sur *The Limits to Growth*](resources/Limits_to_Growth_reference.pdf)

> Ce document est une ressource documentaire et ne constitue pas une production personnelle du groupe. Il a été rédigé par Romain Jarrier et corrigé par le groupe de travail Clim'@ction du laboratoire LCP-MR.

---

## Équipe

Projet réalisé à l'INSA Rouen Normandie dans le cadre du projet STPI/PSE/2025-35.

- Jahnis Schetrit
- Raphaël Thivent
- Clément Lefebure
- Léo Burnel
- Luane Fouilhé

Enseignant-responsable : **Mathieu Laignel**

---

## Références principales

- Dennis Meadows, Donella Meadows, Jørgen Randers — *The Limits to Growth*
- Dennis Meadows, William Behrens, Donella Meadows, Roger Naill, Jørgen Randers, Erich Zahn — *Dynamics of Growth in a Finite World*
- Documentation et implémentation Python de pyWorld3

---

## Mots-clés

`Python` `pyWorld3` `World3` `Simulation` `Modélisation` `Systèmes dynamiques` `The Limits to Growth` `COP` `Environnement`
