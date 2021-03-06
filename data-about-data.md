## Personne contact
Camille Maumet

## Participants
- Audrey Bihouée
- Alban Gaignard
- Arthur Masson
- Christophe Héligon
- Julien Louis
- Michael Kain
- Yao Chi
- Lise Desquilles
- Raluca Teusan
- Isabelle Hue


## Titre
Data about data

## Description du projet et des données utilisées
Ce projét est autour de la découvrabilité des données. L’objectif est de répondre aux questions des chercheurs qui souhaitent faire connaître les informations relatives à leurs jeux de données sans pour autant partager les données elles-mêmes. Comment décrire les échantillons ? Quelles informations partager ? Comment indexer ces données ? De même, des questions similaires peuvent se présenter aux experts en science du numérique au moment de sélectionner ou réutiliser un jeu de données.

## Résultats attendus
- Engager une discussion sur l’importance des métadonnées (quoi inclure et comment)
- Produire une liste de standards “suffisants”
- Recenser les ontologies existantes pour définir la provenance et la nature d’un échantillon

## État d'avancement du projet : 
0_ Concept - Aucun contenu

## Compétences attendues
Biologie; Santé; Ontologies

## Outils - logiciels - méthodes
Registres d’ontologies (BioPortal, ontobee , AberOWL, BioSamples), éventuellement OWL/RDF

## Liens outils
- [BIDS](https://bids.neuroimaging.io/)
- [Biosample](https://www.ebi.ac.uk/biosamples/ )
- [BioSchemas](http://bioschemas.org/)
- [Bioportal](https://bioportal.bioontology.org/)

## Rapport d'avancement

| | |
|---|---|
|**Objectifs**|Division en 3 sous projets : 1. Modélisation des échantillons : revue des modèles existants et de leur utilisation en biologie/santé. 2.Discussion structuration des données d’un projet pour communication interne (plate-forme). 3. Amélioration d’import + export en BIDS dans Shanoir|
|**Premiers résultats**| |
|1.|Discussion sur les pratiques (sémantique dans les noms de fichiers …) et l’existant (Gene Ontology, etc.). / Exploration de l’ontologie BioSamples. Exploration des ontologies légères BioSchemas (BioSample, Study, Phenotypes).|
|2.|Discussion sur les pratiques internes des plate-formes. / Description des formats de données brutes. / Discussion du cycle de vie d’un projet : acquisition / analyse / publication. / Echange sur le partage de données dans les communautés (partage obligatoire des données au moment de la publication dans une base publique). Echange sur l’utilité de /partager connaître la “richesse” des informations disponibles pour une meilleure utilisation des données existantes / la mise en place de collaborations.|
|**Difficultés techniques**|Se mettre d’accord sur les objectifs|

## WrapUp

- 2 standards étudiés : BioSamples (BD EBI) ; BioSchemas (standards)

- Questions pourquoi faire ? 
  - Questions Isabelle 
    - sur des adypocites intra-muscullaire ? 
    - recherche des papiers dans un premier temps
    - RNAseq fait sur les tissus ? données de puces ? → protocoles / analyses

  - Questions Christophe 
    - J’ai généré les données RNAseq pour comparer l’effet de 24h de jeûne chez des souris adultes mâles. Y a-t-il une(des) étude similaire faite chez la femelle? Puis-je récupérer des échantillons biologiques prélevés dans des conditions similaires dans un autre laboratoire?

- Comment utiliser les standards pour établir des connexions entre 
    - Sample ←→ Paper 
    - Sample ←→ Study + protocoles
    - Sample ←→ Tissue 
    - Sample ←→ Expression databases 

- ! Provenance sur protocoles d’analyses et protocoles expérimentaux ou de conservation des échantillons 

**TODO :**
- Ecrire une ou deux requêtes SPARQL pour répondre à ces questions 
- 1 petit graphe RDF “à la main” 
- Trouver un use-case sur la plateforme GenoBiRD pour annoter un projet avec des métadonnées. 
