---
title: Travail réalisé
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Réalisation

> :bulb: Cette page sert à présenter les travaux réalisés incluant la conception.  
> Elle ne remplace pas le rapport final, mais permet de documenter progressivement les travaux réalisés, les décisions prises et les principaux résultats obtenus.


## Structure suggérée

> La structure suivante est donnée à titre indicatif.  
> Vous pouvez l’adapter selon la nature de votre projet.

### Architecture ou structure générale

> Présentez l’organisation générale du projet :
>
> - architecture logicielle ;
> - composants principaux ;
> - structure des données ;
> - technologies utilisées ;
> - environnement de développement ;
> - outils ou services externes.
Le projet comporte une architecture full-stack, avec une séparation claire entre le backend et le frontend, et utilise une API REST, ainsi que SSE pour des updates en temps réel. L'entièreté du backend a été réalisé par un autre élève au trimestre précédent, donc notre tâche principale était le frontend, mais nous avons quand même travaillé sur le backend. Vignette est divisé en plusieurs parties différentes, dont le volet communauté, qui est le volet sur lequel je me suis concentré, mais il y aussi le volet studio qui permet aux utilisateurs de créer des scénarios (storyboard). Il y aussi le module langues qui contient les données Glottolog. Le module communauté contient tout ce qui est les discussions, likes, bookmarks, notifications, accréditation, copie d'un scénario, collaboration, etc. Pour ce qui est de la structure des données, on utilise PostGreSQL en production et H2 en développement pour être plus rapide. Nous utisons aussi des migrations Flyway pour garantir la compatibilité des deux. JPA/Hibernate est utilisé pour faire le pont entre le code Java et SQL. Les tests sont réalisés à l'aide de Mockito. Au niveau des technologies utilisées, pour le backend nous avons Spring Boot avec Java, et pour le frontend nous avons Vue 3. Un outil trés important de ce projet est un service externe, Glottolog, qui sert de source de donnée linguistique. 

### Fonctionnalités ou composantes réalisées

> Présentez les principales fonctionnalités, modules ou composantes développés.
>
> Vous pouvez inclure :
>
> - captures d’écran ;
> - diagrammes ;
> - démonstrations ;
> - extraits de code ;
> - prototypes.

### Difficultés rencontrées

> Décrivez les principaux défis rencontrés durant le projet :
>
> - techniques ;
> - méthodologiques ;
> - organisationnels ;
> - liés aux outils ou technologies.

### Décisions et ajustements

> Présentez les changements importants effectués durant le trimestre :
>
> - changement d’approche ;
> - ajustement des objectifs ;
> - nouvelles contraintes ;
> - simplifications ;
> - améliorations apportées.
