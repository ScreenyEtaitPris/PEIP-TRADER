# PEIP - Trader

Bienvenu sur le projet trader, dont l'objectif est de répondre à la problématique
suivante : est il possible de s'enrichir avec quelques jeux de données et de l'intelligence artificielle
obtenue sur le web clé en main ?

**Attention, ce projet n'a pas pour objectif de vous pousser à faire du trading, mais plutôt de vous montrer que le trading est généralement est une activité très risquée, entrainant plus de pertes que de gains**. La lecture du livre `The Intelligent Investor, Benjamin Graham, Jason Zweig, Harper Business, février 2006` est conseillée pour compléter vos connaissances liées à ce projet.

Du point de vue compétences, ce projet vous apportera :
- la maitrise du langage Python
- la maitrise de la bibliothèque Pandas
- des connaissances théoriques sur les séries temporelles
- des connaissances sur l'investissement et la spéculation, et leurs risques associés

## Getting started

Les Notebooks vont vous permettre de vous former avant de vous lancer dans votre carrière de trader.

Les données sont stockées dans le dossier `data`.

Pour commencer, il vous suffit de tout importer dans le cocalc de Polytech et de prendre les Notebooks un par un en suivant la numérotation.

## Stratégies spéculatives

Quelques stratégies de base testées pour ce projet :
- effet janvier
- Kinjun
- aléatoire
- Oracle

## Rendu pour évaluation

Dans votre projet Cocalc :
1. partager votre projet avec `antoine.pigeau@univ-nantes.fr`
2. créer un dossier `Projet` dans votre projet Cocalc
3. dans le dossier `Projet`:
  - un notebook `Loader.ipynb` (classe(s) pour charger les données)
  - un notebook `Testeur.ipynb` (classe(s) pour les stratégies)
  - un notebook `Strategy.ipynb` (vos stratégies, implémentant la classe `IStrategy`)
  - un notebook `RunTest.ipynb` (code lançant les tests et sauvegardant les résultats des tests dans des fichiers `.csv`)
  - un notebook `DisplayResult.ipynb` (code pour visualiser les résultats)
  - un dossier `Data` contenant vos données de valeurs mobilières
  et un dossier `Result` contenant vos fichiers de résultats des tests
4. dans chaque Notebook, indiquez les étudiants ayant participé(e)s à l'implémentation de ce Notebook
5. dans le Notebook `Strategy.ipynb`, expliquez les stratégies implémentées (en donnant un exemple de quand on vend ou quand on achète)
6. dans le Notebook `DisplayResult.ipynb`, ajoutez des commentaires sur les stratégies (si on gagne ou perd de l'argent, dans quelle condition, nombre de vente/achat à réaliser, prise en compte ou non des frais de trading, ...), des commentaires/explications sur les figures

## Présentation aux départements

Le groupe 2 présentera ses résultats.

Durée de la présentation : 15 minutes de présentation + 10 minutes de questions.

Plan pour la présentation:
1. introduction
    - objectif du projet
    - contexte du projet
    - le trading permet de s'enrichir à tous les coups ?
2. les données utilisées
3. le jeu
    - exemple de trading
    - stratégie oracle/random et évaluation de ces stratégies
    (exemples pour bien comprendre comment sont évalués les stratégies - test sur chaque jour, coût du broker, ...)
4. les stratégies implémentées
5. résultats / démonstration via Notebook
6. conclusion
    - répondre à la question de l'introduction

Merci de m'envoyer les slides de présentation une semaine avant la soutenance.

## **If you want to look at the final/explanation readme, look at Rendu_Clément_PASQUET.ipynb ! ( be careful, it's a jupyter notebook )**
