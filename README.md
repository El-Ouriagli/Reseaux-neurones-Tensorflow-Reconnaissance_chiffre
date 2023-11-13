# Réseaux-neurones-Tensorflow-Reconnaissance_chiffre
![tenserflow](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/0cdf6e37-4fa9-4f77-a56f-1a8e8bb0a43f)

# Explication 
Importez les bibliothèques nécessaires, notamment NumPy pour le traitement numérique, Matplotlib pour la visualisation, et les modules de scikit-learn et Keras pour la manipulation des données et le chargement du jeu de données MNIST.

1. Chargez les données d'entraînement et de test du jeu de données MNIST à l'aide de la fonction mnist.load_data() de Keras.

2. Affichez les dimensions des tableaux contenant les données d'entraînement (X_train et y_train) et les données de test (X_test et y_test) à l'aide de la fonction np.shape().

3. Normalisez les valeurs des pixels des images en les divisant par 255 pour les ramener dans la plage [0, 1].

4. Visualisez une grille d'images à partir des données d'entraînement à l'aide de Matplotlib, en affichant une sélection d'images dans une grille de taille définie (k0 lignes par k1 colonnes).
# Résultat 

![Capture22](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/4efd497a-5e58-4a4d-93c0-f9abf5336110)

# Suite :

![Capture333](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/488f0811-1be3-428f-888e-a4a9e41ec2c1)

# Explication 


1. Concaténez les données d'entraînement (X_train, y_train) et de test (X_test, y_test) pour créer des ensembles de données combinés (X et y).

2. Utilisez la fonction shuffle pour mélanger aléatoirement les données d'entraînement et de test.

3. Divisez les ensembles de données mélangés en ensembles d'entraînement (X_train, y_train) et deux ensembles de test distincts (X_test, y_test et X_test2, y_test2) en utilisant la fonction train_test_split.

4. Affichez les dimensions des ensembles d'entraînement et des deux ensembles de test à l'aide de la fonction np.shape().

   Ensuite, définissez une fonction plot_The_images pour afficher visuellement quelques images avec leurs étiquettes à partir d'un index donné. Enfin, utilisez cette fonction pour afficher cinq images avec leurs 
    étiquettes pour cinq indices différents dans l'ensemble d'entraînement (X_train, y_train).

# Résultat 
![Capture44](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/bc6c401e-a187-4a81-b385-6dc16eabc691)

# 2 Construction du modèle

![Capture55](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/e60763c8-190e-4eae-9ab6-80b1a3d3fa9d)

# 3 Compilation du modèle

![Capture66](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/b09e4b3a-55ca-45ec-b7ea-bfedeaa9d055)

# 4 Training du modèle

![Capture77](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/9a15fef9-dbd0-4408-b85c-1e1356428896)

# 5 Evaluation de la précision

![image](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/0d554ba9-939b-4517-88e4-651f7a31af66)

# 6 Faire des prédictions

![image](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/b324f47a-905f-42a6-b6b3-5f4cf21c0025)

![image](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/39a4733a-8acb-4a3e-9e63-41417415e992)

# Explication

1. La fonction plot_images_histogramme prend un indice i, un tableau de prédictions (predict_array), l'étiquette réelle (true_label), et une image (img). Elle affiche l'image, la prédiction, la vérité, et colorie le texte en bleu si la prédiction est correcte, en rouge sinon.

2. La fonction plot_value_array prend un indice i, un tableau de prédictions (predict_array), et l'étiquette réelle (true_label). Elle crée un diagramme à barres montrant la confiance de chaque classe prédite. La barre correspondant à la prédiction correcte est coloriée en bleu, tandis que celle de la prédiction incorrecte est en rouge.

3. Les variables num_rows, num_cols, et num_images sont utilisées pour définir le nombre de lignes, de colonnes et d'images dans la visualisation.

4. La boucle for parcourt un nombre spécifié N d'images à partir de l'indice N, et pour chaque image, elle utilise les fonctions définies pour afficher à la fois l'image avec les prédictions et l'histogramme des valeurs prédites.

5. La visualisation finale est une grille de sous-graphiques avec les images, les prédictions, les étiquettes réelles, et les histogrammes, permettant une analyse détaillée des résultats du modèle sur un ensemble spécifique d'images de test (X_test2).

# Résultat finale 

![image](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/7183851c-8ffe-4d71-8dad-b09eeaa1f0f2)
![image](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/7fa933cf-8151-464f-b2d5-5f1550329c14)
![image](https://github.com/El-Ouriagli/R-seaux-neurones-Tensorflow-Reconnaissance_chiffre/assets/149663821/ec062f2d-1eab-42c8-a2f2-37b8178447c9)



  # Don't forget to leave a Star  ⭐
