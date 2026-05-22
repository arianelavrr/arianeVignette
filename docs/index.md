---
title: Vue d'ensemble du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Vue d'ensemble du projet

!!! info "Informations générales"
    **Session**: Été 2026  
    **Auteur(s)**: Léa Hemidj (), Ariane Laverrière (20248561),     
    **Thème(s)**: <!-- Thèmes principaux abordés dans le projet  -->  
    **Superviseur(s)**: Louis-Edouard Lafontant     
    **Collaborateur(s):** <!-- Nom de(s) collaborateur(s) et partenaire(s)` -->  

## Description du projet

Le projet Vignette est un site web qui, une fois développé, permettra aux linguistes et autres utilisateurs de partager des scénarios et des vignettes pour divers langage, ainsi que des audios.

### Contexte

Ce projet s’inscrit dans un contexte à la fois éducatif, technologique et socioculturel, où la préservation et la transmission des langues, en particulier celles dites à faibles ressources, représentent un enjeu important. Les ressources qui existent sont souvent éparpillées, techniques, et peu accessibles à ceux qui en auraient le plus besoin, comme les membres des communautés elles-mêmes, ou simplement ceux qui sont curieux.

Ce projet part de ce constat. Il cherche à tirer profit des technologies web actuelles, comme les interfaces modernes, API REST et les bases de données comme Glottolog, pour construire quelque chose d'utile autant aux linguistes qu'aux apprenants ordinaires.

### Problématique

Les plateformes existantes ont un problème commun, elles traitent les langues comme des objets à archiver, pas comme des pratiques vivantes à partager. Les contenus sont rarement interactifs, les communautés y ont peu de place, et quand des échanges existent, ils sont déconnectés des ressources elles-mêmes, comme si les discussions et les enregistrements audio vivaient dans deux mondes séparés.

La question qui guide ce projet est donc la suivante :
Comment concevoir une plateforme qui documente les langues, facilite leur apprentissage et implique réellement les communautés, tout cela de façon accessible et engageante?

### Proposition et objectifs

L'idée centrale, c'est d'utiliser des storyboards linguistiques, donc des scénarios qui combinent texte, audio et images pour raconter une langue plutôt que de simplement la lister. Notre approche ressemble à ceci :

- Documenter les langues à travers des scénarios organisés et navigables
- Apprendre de manière interactive, notamment grâce à l'audio
- Permettre aux communautés de contribuer, d'échanger et de prendre part à la vie de la plateforme

Concrètement, cela se traduit par des storyboards clairs, un système de discussions attachées aux contenus, un mécanisme d'accréditation pour encadrer les contributions, et une interface pensée pour être accessible.

### Méthodologie

Le développement suit une approche itérative, avec une séparation nette entre frontend et backend. On commence par comprendre ce qui existe déjà côté serveur, puis on construit les composants visuels progressivement (discussions, profils, badges, gestion des rôles) avant de les connecter à l'API et d'affiner l'expérience au fil des retours.

Voici les grandes étapes principales:

- Compréhension de l’architecture backend existante et des endpoints disponibles
- Conception des composants frontend (ex. discussions, profils, badges)
- Implémentation des fonctionnalités communautaires :
    - fils de discussion
    - demandes d’accréditation
    - gestion des rôles
- Intégration des éléments multimédias (audio, scénarios)
- Amélioration de l’expérience utilisateur (design, navigation, accessibilité)

### Validation et Évaluation

> Indiquez comment vous évaluerez que votre solution répond aux objectifs du projet (ex. scénarios d’usage, tests, retours utilisateurs, indicateurs qualitatifs ou quantitatifs).


## Équipe

> Présentez les membres de l’équipe et le rôle principal de chacun dans le projet.

## Échéancier

!!! info
    Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Activités                      | Début   |   Fin   | Livrable                            | Statut      |
|--------------------------------|---------|---------|-------------------------------------|-------------|
| Ouverture de projet            | 4 mai   | 15 mai  | Proposition de projet               | ✅ Terminé  |
| Études préliminaires           | 4 mai   | 22 mai  | Document d'analyse                  | 🔄 En cours |
| Création du site web           | 4 mai   | 22 mai  | Site web                            | ✅ Terminé  |
| Commencement du code           | 4 mai   | 22 mai  | Document d'analyse                  | 🔄 En cours |
| Présentation + Rapport         | 7 aout  | 14 aout | Présentation + Rapport              | ⏳ À venir  |
