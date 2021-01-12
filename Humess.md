## Personne contact
Philippe Bordron

## Participants
Chaque collaboration est la bienvenue !

## Titre
Humess

## Description du projet et des données utilisées
Humess est un projet de reconstruction à façon de réseaux métaboliques humains fontionnels à partir de données d'expression de 3'SRP ainsi que de leur analyse à l'aide d'une approche de corrélation de flux métabolique.

À partir de réseaux métaboliques fonctionnels, les analyses en corrélation de flux métabolique produises de grandes matrice de corrélation entre réactions (environ 5000x5000 en moyenne sur un réseau humain). Ces matrices donne une sur-approximation de la dynamique métabolique existant dans les réseaux étudiés.
Dans le cadre de ce hackathon, je souhaite travailler sur les représentations et l’accessibilité des obtenus.

## Résultats attendus

Je souhaite tout d'abord comparer des matrices de corrélation obtenues sur plusieurs organes ou conditions:
- **1.a** d'un point de vue global, comparer les organes. C'est à dire calculer une dissimilarité (distance) ou une similarité entre chaque organe. De approches de comparaison de matrices de covariance ont déjà été tentées (procrustes, test de mantel) , mais les résultats sont mitigés.
- **1.b** d'un point de vue plus spécifique; déterminer ce qui change et ne change pas entre les organes, au delà des réactions et des métabolites spécifiques à chaque réseau.

La difficulté de ce point n'est pas vraiment technique, mais méthodologique. Nous manipulons des millions de corrélations entre réactions et les approches statistiques utilisant des matrices 'feature x échantillon'  (e.g. RNASeq, ...) sont difficilement applicable.

Je souhaite également travailler sur les aspects visualisation et enrichissement des résultats:
- **2.a** Projeter les résultats obtenus sur des réseau métaboliques existants. Tout d'abord les réseaux métaboliques reconstruits, mais également une manière re représenter les matrice de corrélation de façon intelligible malgré leur grande dimension.
- **2.b** Projeter/intégrer/enrichir ces résultats avec les analyses transcriptomiques effectuées en parallèle.
- **2.c** Envisager d'autres sources omique à intégrer (proteomique, metabolomique, ...) 

Seule une phase de recherche sur quelques outils possibles a été effectuée pour cette partie.   
**Toute proposition est la bienvenue !**

## État d'avancement du projet :
2_ existence

## Compétences attendues
Statistique, représentation de l'information, web semantique, data sciences, bioinformatique

## Outils - logiciels - méthodes
miniconda/anaconda, R, python 
