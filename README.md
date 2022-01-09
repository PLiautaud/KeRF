# KeRF

Les forêts aléatoires introduites par Leo \textsc{Breiman} au début des années 2000 sont une méthode de classification et de régression par apprentissage supervisé. L'approche repose sur un principe simple mais puissant, "diviser pour mieux régner" : faire plusieurs sous-échantillonnages des données, construire un arbre de décision pour chaque sous-ensemble selon un paramètre aléatoire, agréger les réponses pour obtenir la prédiction finale. Cette stratégie affiche d'excellents résultats dans divers domaines appliqués, pour en nommer quelques-uns : bio-informatique, économétrie ou encore reconnaissance d'objets $3$D. La robustesse des forêts aléatoires dans des problèmes de très grande dimension associée à leur simplicité pratique (peu de paramètres sont à ajuster) en ont fait une méthode populaire. Ce succès contraste avec le peu de résultats théoriques présents dans la littérature. Les forêts demeurent mathématiquement mal comprises, ce sont des objets complexes et de ce fait difficiles à analyser. Dans le cadre d'un problème de régression, notre présent objectif est d'établir le lien entre les forêts aléatoires et des estimateurs à noyau obtenus après une légère modification de leur définition. Cette approche permet d'obtenir de nouveaux estimateurs nommés KeRF (Kernel Random Forest), qui satisfont une certaine proximité aux forêts aléatoires (dans certains cas), tout en ouvrant des perspectives d'analyses mathématiques plus profondes.

# XP

 - Par exemple, on peut représenter 4 arbres centrés opérant sur un jeu de données de taille $n=200$ dans $\mathcal{X}=[0;1]^2$, telles que $(\mathbf{X}_i)_i \sim \mathcal{U}([0;1]^2)$ :
![Pathos_Exemple7_d2_N=200](https://user-images.githubusercontent.com/90805180/148701851-b73ff73e-f9a6-4506-87fb-c3e3bc601437.jpg)

- Une comparaison entre KeRF centré, RF centré et RF Breiman évalués sur le modèle suivant AJOUTER :
![Model1_d2](https://user-images.githubusercontent.com/90805180/148701826-410d8e85-d42d-44cd-afd8-78bdc4a7f643.jpg)



*Contributions :* Laure Ferraris, Paul Liautaud
