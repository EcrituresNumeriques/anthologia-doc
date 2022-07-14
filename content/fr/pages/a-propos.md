---
title: À propos
---

# Pour une édition numérique collaborative de l'*Anthologie Grecque*

Le projet "Pour une édition numérique collaborative de l'*Anthologie grecque*" est né en 2014, grâce à la collaboration de Marcello Vitali-Rosati et d'Elsa Bouchard. S'inscrivant dans le champ des *Digital Classics*, le projet AG a pour vocation d'approcher une édition, la plus complète possible, de ce monument de la littérature classique. 

## L'*Anthologie grecque* 

Le mot *anthologie* signifie littéralement "rassemblement, couronne de fleur" et est équivalent au mot d'origine latine "florilège". L'*Anthologie grecque* recueille les "fleurs" (à savoir, des épigrammes) de la littérature grecque. Les épigrammes consistent en de petites pièces versifiées, qui avaient pour vocation initiale d'être gravées afin d'acompagner une statue, un ex-voto, une épitaphe,... Le genre se développe et se diversifie particulièrement à l'époque alexandrine, abordant, entre autres, des sujets amoureux, satiriques ou bachique. 

Ce que nous appelons *Anthologie grecque* correspond à un recueil regroupant la poésie épigrammatique grecque issue de la période classique jusqu’à la période byzantine, soit près de 4 000 pièces, de 325 auteur·e·s différent·e·s, résultat de seize siècles de littérature. Fruit de multiples compilations et reconfigurations, l’*Anthologie* a une histoire complexe. Par définition, un recueil anthologique se caractérise par une reprise de plusieurs sources et l’enrichissement continu d’un corpus. 

La dénomination « Anthologie grecque » fait d’ailleurs référence à la réunion du manuscrit Palatinus 23 et de l'*appendix planudea*. 
Le *Codex palatinus 23* (940 apr. J.-C.) a été retrouvé en 1606 par Claude Saumaise et correspond à l'*Anthologie Palatine*. L'ouvrage voyagea en de nombreuses mains à travers toute l'Europe avant d'arriver à la Bibliothèque Palatine de Heidelberg où il est actuellement conservé. Toutefois, lors -- sans doute -- d'un voyage entre la Bibliothèque Palatine et la Vaticane, il se déchira en deux à la page 614, entre les livres XIII et XIV. Les pages 615 à 709 sont encore aujourd'hui conservées à la Bibliothèque Nationale de France. 
L'*Appendix Planudea* comprend les épigrammes absentes du manuscrit palatin mais présentes dans l’*Anthologie* dite *de Planude* (1301), un érudit byzantin ayant vécu aux XIII^e et XIV^e siècles. 
L'*Anthologie grecque* est articulée en 16 livres, par thème. Le premier livre par exemple comprend les épigrammes chrétiennes, le cinquième rassemble des épigrammes amoureuses et érotiques, le septième des épitaphes ou épigrammes funéraires. Le seizième livre correspond à l'*appendix planudea*. 

Ces anthologies se basent sur une anthologie constituée par Constantin Céphalas vers 900 apr. J.-C., elle-même composée à partir des Couronnes de Méléagre (I^e siècle av. J.-C.) et de Philippe (I^e siècle apr. J.-C.), de Diogénien (II^e siècle apr. J.-C.) ou encore du Cycle d’Agathias (plus tardivement, au VI^e siècle apr. J.-C.). 

Malgré sa fragmentation constitutive, l’*Anthologie* se présente comme un corpus riche d’intertextualité : par la répétition de thématiques iconiques émergent des topoï que l’on retrouve dans notre culture actuelle et qui marquent une intemporalité de l’anthologie. Ces poèmes ont exercé une influence majeure sur la littérature de la Renaissance jusqu’à aujourd’hui.  

## Description et objectifs du projet 

Depuis 2014, une vaste équipe contribue au projet d'édition numérique collaborative de l'*Anthologie grecque*. L'objectif du projet est d'offrir une édition la plus *complète* possible pour chacune des épigrammes de l'*Anthologie* -- même si par sa nature anthologique, le projet refuse toute clôture. 
La [plateforme](https://anthologiagraeca.org/) d’édition dédiée au projet se présente comme une base de données relationnelles, construite sur la notion d'entité (1 entité = 1 épigramme). Le but du projet est que chaque entité soit associée à plusieurs types d'informations éditables dont : 
- l'image du manuscrit *Pal. gr. 23* corespondant à l'épigramme (grâce au protocole iiif) 
- des transcriptions 
- des traductions
- des alignements des traductions
- l'image et la transcription des scholies
- des liens entre les épigrammes 
- des mots-clés (structurés selon les recommandation du Web des données ouvertes et liées)
- des commentaires

Ces données sont récupérables grâce à une [api](https://anthologiagraeca.org/api/). Celle-ci expose la base de données ouverte en lecture et écriture en GraphQL et rendue accessible en JSON. À la ifférence de XML, plus rigide dans la structure et le balisage, JSON permet la réorganisation les données en fonction de multiples interprétations et structures.

L'édition proposée n'a pas pour but de concurrencer les nombreuses éditions critiques existantes mais plutôt de proposer une approche philologique alternative, permettant d'épouser et de continuer le projet anthologique initié par les premiers compilateurs. 
Le propre de l'*Anthologie* est la mise en lien des textes. De fait, rendre compte de l'imaginaire anthologique ne signifie pas faire une édition critique et génétique classique dans laquelle il s’agirait d’établir une vérité du texte, mais souligner les innombrables connexions entre textes et d’autres objets culturels. Notre base de données est organisée autour d’une entité texte, puisqu’un texte peut avoir différentes versions et traductions. L’idée de "vérité" du texte - à la base de l’approche critique ou généalogique - n'est pas notre objectif. Au contraire, nous cherchons à faire émerger les pluralités de perceptions du matériel textuel - car c’est en effet cette pluralité, à l’origine de l’imaginaire collectif tissé autour de l’*Anthologie grecque* qui constitue, pour nous, l’essence du texte. Notre base de données doit permettre de parachever cette philosophie anthologique, en soulignant les connexions intertextuelles et intermédiales qui se sont tissées à travers le temps. Pour rendre compte de cette richesse hétérogène, nous avons fait le choix d’une forme éditoriale ouverte, souple et qui permette l'interaction dynamique de la communauté savante avec la communauté des amateurs.
En renouvelant l’approche philologique classique, nous avons été amenés à déplacer les frontières entre pratiques savantes et amateures, tant au niveau de la production que de la diffusion des contenus éditoriaux.


D'autres projets se sont créés en parallèle de la [plateforme principale](https://anthologiagraeca.org/) : 

- la [POP](http://pop.anthologiegrecque.org/#/) (Plateforme Ouverte des Parcours d'imaginaires). Il s'agit d'une visualisation d'une ancienne version de la plateforme Anthologia. Elle regroupe en parcours de lecture thématiques certaines des épigrammes de l'*Anthologie*. 

- *Anthalgo*. Il s'agit d'un projet pilote dont l'objectif est de préciser la définition du concept de variation en utilisant des algorithmes capables d'en retrouver les exemples au sein de l'*Anthologie*. Les algorithmes ne sont pas utilisés dans un but heuristique (nous savons ce qu'ils doivent trouver) mais plutôt dans une idée de thérie littéraire : en effet, les caractéristiques apprises à l'algorithme nous permettront d'approcher une définition formelle de la variation. 

