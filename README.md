# KeRF

We provide here a repository which is made of works/simulations related to the study of random forests and more precisely of their kernel estimator, KeRF.

Les forêts aléatoires introduites par Leo \textsc{Breiman} au début des années 2000 (voir \cite{breiman2001random}) sont une méthode de classification et de régression par apprentissage supervisé. L'approche repose sur un principe simple mais puissant, "diviser pour mieux régner" : faire plusieurs sous-échantillonnages des données, construire un arbre de décision pour chaque sous-ensemble selon un paramètre aléatoire, agréger les réponses pour obtenir la prédiction finale. Cette stratégie affiche d'excellents résultats dans divers domaines appliqués, pour en nommer quelques-uns : bio-informatique, économétrie ou encore reconnaissance d'objets $3$D. La robustesse des forêts aléatoires dans des problèmes de très grande dimension associée à leur simplicité pratique (peu de paramètres sont à ajuster) en ont fait une méthode populaire. Ce succès contraste avec le peu de résultats théoriques présents dans la littérature (citer quelques approches?\lf{citer des résultats}). Les forêts demeurent mathématiquement mal comprises\pl{plutôt dire toujours à découvrir ?}, ce sont des objets complexes et de ce fait difficiles à analyser. Dans le cadre d'un problème de régression, notre présent objectif est d'établir le lien entre les forêts aléatoires et des estimateurs à noyau obtenus après une légère modification de leur définition. Cette approche permet d'obtenir de nouveaux estimateurs nommés KeRF (Kernel Random Forest), qui satisfont une certaine proximité aux forêts aléatoires (dans certains cas), tout en ouvrant des perspectives d'analyses mathématiques plus profondes.

Contributions : Laure Ferraris, Paul Liautaud


![Model1_d2](https://user-images.githubusercontent.com/90805180/148701826-410d8e85-d42d-44cd-afd8-78bdc4a7f643.jpg)


![Pathos_Exemple7_d2_N=200](https://user-images.githubusercontent.com/90805180/148701851-b73ff73e-f9a6-4506-87fb-c3e3bc601437.jpg)
