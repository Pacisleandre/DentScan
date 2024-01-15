# DentScan - Read Me

## Introduction
La dentisterie moderne est confrontée à des défis complexes, et l'analyse précise des angles dentaires représente une problématique cruciale. Les étudiants en médecine dentaire doivent souvent déterminer avec précision les angles sur une dent pour des diagnostics et des traitements efficaces. Notre projet, DentScan, s'attaque à cette problématique en utilisant des techniques avancées de Data Mining appliquées à un ensemble de données composé d'images dentaires et de fichiers XML contenant des labels spécifiques.

## Dataset
Le dataset que nous utilisons comprend des images de dents accompagnées de fichiers XML détaillant les labels associés. Ces labels incluent les coordonnées x et y minimales et maximales, délimitant ainsi les contours des dents. Ces informations sont cruciales pour la détermination des quatre points clés nécessaires à la trajectoire des tangentes.

## Augmentation de données
Afin d'améliorer la robustesse et la généralisation de notre modèle, nous avons pris la décision stratégique d'effectuer une augmentation de données. Cette étape consiste à créer des variations artificielles dans notre ensemble d'images en appliquant des transformations telles que la rotation, le changement d'échelle et la translation. La diversité résultante dans les conditions d'éclairage, d'angle et de qualité d'image contribue à renforcer la capacité de notre modèle à traiter des situations variées et à produire des résultats fiables.

## Modèle
Suite à cette augmentation de données, notre modèle utilise des techniques avancées de Data Mining pour extraire des caractéristiques pertinentes des images dentaires. Cela nous permet de déterminer avec précision les quatre points clés sur chaque dent, formant ainsi la base pour la trajectoire des tangentes et la détermination des angles dentaires.

## Objectif
Notre approche, alliant données enrichies et techniques de Data Mining, vise à fournir aux étudiants en médecine dentaire un outil puissant pour une analyse précise des angles dentaires. DentScan représente une avancée significative dans le domaine, ouvrant la voie à des applications pratiques pour l'amélioration des soins dentaires et de la formation des professionnels de la santé bucco-dentaire.
