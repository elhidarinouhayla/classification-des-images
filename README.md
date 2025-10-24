# classification-des-images



# 👗 Classification d’images - Fashion MNIST

## 🧠 Description
Ce projet utilise **TensorFlow et Keras** pour créer un modèle capable de reconnaître différents types de vêtements à partir d’images en niveaux de gris du dataset **Fashion MNIST**.

---

## ⚙️ Étapes principales

1. **Chargement des données**
   - Importation du dataset Fashion MNIST intégré à TensorFlow.  
   - Division en données d’entraînement et de test.

2. **Prétraitement**
   - Visualisation des images.  
   - Normalisation des valeurs de pixels entre 0 et 1.

   
3. **Création du modèle**
   Le modèle utilisé est un réseau de neurones convolutionnel (CNN).
Il combine des couches de convolution pour extraire les caractéristiques des images et des couches denses pour la classification finale.

  - Conv2D(32, (3,3), relu) : extrait les caractéristiques principales de l’image.

  - MaxPooling2D(2,2) : réduit la taille des images pour diminuer la complexité.

  - Conv2D(64, (3,3), relu) : détecte des caractéristiques plus complexes.

  - MaxPooling2D(2,2) : deuxième réduction de taille.

  - Flatten : transforme les données 2D en vecteur.

  - Dense(128, relu) : couche cachée entièrement connectée.

  - Dense(10, softmax) : couche de sortie avec 10 classes correspondant aux catégories à prédire.

4. **Compilation et entraînement**
   - Optimiseur : **Adam**  
   - Fonction de perte : **sparse_categorical_crossentropy**  
   - Entraînement sur **10 époques**

5. **Évaluation**
   - Précision sur les données de test : **≈ 91%**

---

## 🧩 Technologies utilisées
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib

---

👩‍💻 Auteur

El Hidari Nouhayla
