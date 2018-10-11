# FACTORISATION DE MATRICES AVEC DESCENTE DE GRADIENT DISTRIBUÉE

Avec le développement d'Internet, en particulier l'Internet mobile, l'information devient explosive. Plus de 90% des données dans le monde sont créées ces dernières années. Avec l'inflation de l'information, les gens accèdent à des informations utiles avec plus de difficultés, ce qui est appelé problème de surcharge d'information. Le principal moyen d’attaquer ce problème est par le biais des moteurs de recherche et des systèmes de recommandation.

En fonction des informations de l'utilisateur, comme l'historique des achats ou des films regardés et des informations personnelles de base, le point clé des systèmes de recommandation est de proposer aux utilisateurs les produits les plus susceptibles de répondre à leurs attentes.

Pour ce faire, la factorisation matricielle de rang inferieur a été considérée comme l’un des meilleurs modèles pour les systèmes de recommandation. Plusieurs chercheurs ont créé des algorithmes de factorisation de matrices à grande et petite échelle. Les algorithmes les plus utilisés sont ALS (Alternative Least Square) et SGD (Stochastic Gradiant Descent).

Dans ce projet, nous utiliserons l’algorithme SGD distribué (DSGD) que nous implémenterons sur Spark avec pySpark sur une base de données des préférences des utilisateurs pour des films. Nous présenterons donc dans une première partie les données utilisées puis dans une seconde partie nous expliquerons l’algorithme DSGD et enfin nous présenterons nos résultats et des extensions envisageables.

Dans ce répertoire, vous trouverez le code et le rapport.
