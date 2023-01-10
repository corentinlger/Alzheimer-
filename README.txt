Auteurs : 

Walid Kini
Yassine Mougou
Corentin Leger
Jacques Kafak 

Chaque jupyter notebook contient un modèle et les résultats de prédictions obtenus avec ce dernier, voici une brève 
description de ces derniers :

2D-epsilon_simple : un seul hippocampe utilisé pour faire la prédiction
2D-epsilon : utiliser les deux hippocampes et générer plusieurs coupes 2D  à des indices proches
2D-epsilon_esp=4 : même code mais on teste la performance avec une valeur de epsilon différente 

Conv3D_whole_brain : Convolutions 3D sur le cerveau entier 

Conv3D_hippocampus : Premier réseau de convolutions 3D sur la partie spécifique de l'hippocampe 
# tentatives d'amélioration du modèle (mais le code reste presque le même)
Conv3D_hippo_reduced_nn : On a juste retiré un bloc de convolutions à l'architecture du réseau de neurones
Conv3D_hippo_data_augmentation : On double le nombre de données en ajoutant des images 3D d'hippocampes avec un 'flip'

Conv3D_random_region : Même code que pour le Conv3D pour l'hippocampe mais avec une région du cerveau qui ades coordonnées différentes