## Personne contact
Adrien FOUCAL

## Participants
Chaque collaboration est la bienvenue !

## Titre
Full-ChipSeq

## Description du projet et des données utilisées
Un pipeline snakemake pour traiter les données ChIP-seq humaines sur une machine linux.
Ce pipeline vous permettra de faire ce qui suit :

- Alignement et peak-calling
- Contrôle de la qualité de vos échantillons
- Génération d'un hub pour visualiser les échantillons sur le [navigateur de l'UCSC](https://genome.ucsc.edu/)
- Annotation fonctinelle
- Motif finding (TODO)

Ce pipeline est basé sur le [pyflow-ChIP-seq développé par Ming Tang](https://github.com/crazyhottommy/pyflow-ChIPseq). J'ai reconditionné la plupart des étapes, ajouté et supprimé quelques-unes, créé de nouveaux environnements de conda et regroupé tous les résultats de contrôle de qualité dans multiQC.
Ce pipeline devrait être facile à installer avec snakemake et conda présents sur le système. Pour l'instant, il fonctionne sur un cluster de sge.

## Résultats attendus
L'objectif est d'apprehender l'installation du pipeline et à quel point il est nécéssaire de modulariser la prise en compte des différents types de données de Chip-Seq (pairted end, single end, CUT&RUN)

## État d'avancement du projet : 
2 (existence)

## Compétences attendues
Du bioinformaticien expérimenté au biologiste qui s'essaye à la ligne de commande


## Outils - logiciels - méthodes
Snakemake et Conda

## Liens utiles
[https://gitlab.univ-nantes.fr/foucal-a/full-chipseq](https://gitlab.univ-nantes.fr/foucal-a/full-chipseq)

#### Données partagées en libre accès.
