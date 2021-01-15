## Personne contact
Aline FOURY

## Participants
Chaque collaboration est la bienvenue !

## Titre
Bien-être du cheval de sport : recherche d'une signature transcriptomique du niveau d'agressivité 

## Description du projet et des données utilisées
L'étude concerne 18 chevaux de sport, 9 chevaux non agressifs et 9 chevaux agressifs. Chaque cheval est caractérisé par un score d'agressivité. L'ARN a été extrait à partir du sang total afin de réaliser une analyse transcriptomique. Le but du projet est d'identifier les gènes marqueurs de l'agressivité chez le cheval ainsi que les voies métaboliques dans lesquelles ils sont impliqués.

#### Données accessibles via le portail DataINRAe : [https://doi.org/10.15454/IO9XF2](https://doi.org/10.15454/IO9XF2)
  ### Données non publiées => merci de ne pas utiliser ces données en dehors du hackathon

**Données phénotypiques** => [pData_MA2025_Agress.csv](https://doi.org/10.15454/IO9XF2)
- get = échantillon
- agress_scans = niveau d'agressivité
- agress_gp = groupe expérimental (Ag.High vs Ag.Low)
- sexe
- age
- pos = position des échantillons sur les lames Agilent (biais expérimental entre les échantillons déposés en position 1 et 2 et ceux déposés en position 3 et 4)

**Données transcriptomiques** => [WorkingSet_MA2025_Agress.csv](https://doi.org/10.15454/IO9XF2)
Working Set = suppression des arrays et des valeurs de mauvaise qualité, suppression des gènes non exprimés, correction pour les biais entre les arrays.

**Analyses réalisées:** 
- 1. Analyse différentielle Ag.High vs Ag.Low
Analyse réalisée avec R (package limma, fonction lmFit) => 0 sondes DE

- 2. Analyse de corrélation entre données phénotypiques et transcriptomiques
Analyse sPLS-DA réalisée avec R (package mixOmics, fonction splsda) => 326 sondes discriminantes (critères de sélection : VIP>1, Freq >0.50) => 272 gènes discriminants

- 3. Recherche des voies de signalisation
Analyse réalisée avec :
  - a. IPA 
=> 1er canonical pathway : NF-kB / Regulator Effects : IL12, Interferon alpha, TNF / Network autour de NF-kB
=> Voie métabolique majeure : l'inflammation
  - b. Enrichr
L'inflammation est retrouvée dans les bases de données BioCarta 2016 et NCI-Nature 2016

## Résultats attendus
- 1.a Peut-on sélectionner des gènes DE en se basant sur la pval non ajustée? 
- 1.b Si oui, sur quels critères pour pouvoir confirmer ces gènes par qPCR (demande fréquente des reviewers).

Quelles autres analyses peuvent être réalisées afin d’identifier les gènes marqueurs de l'agressivité et les voies métaboliques dons lesquelles ils sont impliqués?

## État d'avancement du projet :
2_ existence

## Compétences attendues
- Identification de gènes différentiellement exprimés entre 2 groupes expérimentaux
- Corrélation entre données transcriptomiques et phénotypiques
- Identification de voies métaboliques activées à partir d'une liste de gènes

## Outils - logiciels - méthodes
logiciel R

## Liens outils


#### Ce données ne peuvent pas être partagées
