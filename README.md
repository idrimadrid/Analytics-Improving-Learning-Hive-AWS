## Hadoop - Hive - Sqoop - AWS

# Analytics-Improving-Learning-Hive-AWS

## Introduction :
Le développement phénoménal des systèmes d’informations a conduit à une augmentation des cours en ligne d'apprentissage pour les étudiants (MOOCs). Dans ces cours, les étudiants utilisent un environnement d'apprentissage virtuel (VLE), pour simuler l'expérience d'une salle de classe réelle, un des avantages les plus intéressants est la capacité d'évaluation en temps réel, la collecte du comportement étudiant et l’interaction avec les ressources des cours, toutes ces informations engendre ce qu’on appelle le “Big Data”, représentant une mine d’or pour les établissement d’enseignement, elles peuvent être utilisées pour détecter les étudiants en danger d'échec et intervenir à temps  et même afin d’améliorer la qualité d’apprentissage.

## Contexte :

Aujourd'hui, l'analyse de l'apprentissage est utilisée pour améliorer les performances des enseignants ainsi que la qualité du contenu pédagogique fourni aux apprenants, ainsi elle offre un aperçu global et elle aide les enseignants et les écoles ainsi que les formateur et les entreprises à prendre des décisions sur la manière de rendre l'apprentissage plus efficace pour leurs élèves et apprenants. L'analyse d'apprentissage permet un enseignement basé sur les données.

## Objectifs : 

Dans notre travail, nous cherchons à collecter et analyser les données recueillies dans les environnements d’apprentissage sur les apprenants, durant la période d’enseignements. 
Nous explorons comment utiliser ces informations issues de l'analyse de l'apprentissage pour fournir des informations sur l'enseignement et l'apprentissage et ainsi comprendre comment rendre l'apprentissage plus efficace et quels sont les critères impactant la réussite.

L'acquisition de données et l'analyse de l'apprentissage offrent la possibilité de prendre des mesures au besoin pour aider les apprenants à atteindre des objectifs d'apprentissage définis. Les données de la classe peuvent être utilisées pour faire progresser les apprenants et les motiver à atteindre leurs objectifs. Il permet ainsi aux éducateurs d'être plus réactifs aux besoins des apprenants.

## Données :

Nous avons opté pour une base de données très connue intitulée Open University Learning Analytics Dataset d'une université au UK, qui offre la possibilité de se former en ligne.
La base de données contient les informations sur 22 cours, 32 593 étudiants, leurs résultats d'évaluation et leurs interactions avec le VLE (Virtual Learning Environment) représentés par des résumés quotidiens des clics des étudiants (10 655 280 entrées).

L'OULAD est une collection de données tabulaires sur les étudiants des années 2013 et 2014. L'ensemble de données est disponible sous la forme d'un ensemble de fichiers CSV séparés (valeurs séparées par des virgules, chaque valeur est entre guillemets et la première ligne représente les noms de colonnes).Chaque table contient des informations différentes, qui sont liées aux données d'autres tableaux à l'aide d'identificateurs uniques (colonnes). Les données contenues dans le jeu de données sont structurées comme dans la figure 2. Le jeu de données est orienté étudiant, donc l'étudiant est le point central. Les données des étudiants comprennent des informations sur leurs données démographiques et leurs inscriptions aux modules. Pour chaque triplet étudiant-module-présentation, l'ensemble de données contient les résultats des évaluations des étudiants. Les interactions des étudiants avec le VLE sont consignées sous forme de résumé de leurs activités quotidiennes. 

Démographique : représente les informations de base sur les étudiants, y compris leur âge, sexe, région, études antérieures, etc.
Performance :  reflète les résultats et les réalisations des étudiants pendant leurs études à l’Open University.
Comportement d'apprentissage : est le journal des activités des étudiants dans le VLE.
