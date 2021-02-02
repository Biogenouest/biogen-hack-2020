## Personne contact
Thomas Darde - BioMas

## Participants
- François Moreews
- Alban Besnard
- Camille Juigné

## Titre
GenFlow

[Git du projet](https://github.com/BioMAs/genflow-biogen-hack-2020)

## Description du projet et des données utilisées

À chaque publications les éditeurs imposent de mette à disposition les données brutes dans des dépôts publique pour permettre à tous d’appliquer les méthodes décrites dans le papier et d’en retirer les mêmes résultats. Cependant, dans la majorité des cas le dépôt des données brutes n’est pas suffisant et le il serait bon également de déposer le workflow d’analyse utilisé pour obtenir les résultats présentés dans l’article. S’il existe déjà certaines solutions pour le dépôt des workflows (Workflowhub, nf-core), elles ne règlent pas le problème de la portabilité des environnements ou encore de la version des logiciels, packages, des annotations, du génome ou des ontologies utilisée.

Le projet GenFlow (Genomique Workflow) a pour objectif de réfléchir sur ces problèmes et de proposer des solutions permettant de partager facilement ses stratégies d’analyses et ainsi de pouvoir les relancer plusieurs mois après en obtenant les mêmes résultats.

## Résultats attendus
- Espace de partage des workflows versionnés
- Solution de mise à disposition des ressources externes utilisées dans le workflow

## État d'avancement du projet : 
0_ Concept - Aucun contenu

## Compétences attendues
Génomique; Statistique; Ontologies; Dev web; Workflow

## Outils - logiciels - méthodes
Python; React; R; Docker; SnakeMake; Conda; NextFLow; Galaxy

## Liens outils

- [https://workflowhub.eu/workflows/3](https://workflowhub.eu/workflows/3)
- [https://www.eclipse.org/atl/atlTransformations/](https://www.eclipse.org/atl/atlTransformations/)
- [https://www.atlanmod.org/](https://www.atlanmod.org/)
- [https://naomod.github.io/](https://naomod.github.io/)
- [https://www.eclipse.org/atl/atlTransformations/](https://www.eclipse.org/atl/atlTransformations/)
- [https://pax2graphml.genouest.org/](https://pax2graphml.genouest.org/)
- [https://graphviz.org/doc/info/lang.html](https://graphviz.org/doc/info/lang.html) 
- [https://dreampuf.github.io/GraphvizOnline/](https://dreampuf.github.io/GraphvizOnline/)


## Rapport d'avancement

| | |
|---|---|
|**Objectifs**|Extraire des graphs des pipelines nextflow/snakemake/CWL pour établir des liens entre outils|
|**Premiers résultats**|Choix du format GraphML et étude des possibilités pour obtenir ce format depuis les différents gestionnaires de workflow.|
|**Difficultés techniques**||

#### Données partagées en libre accès
