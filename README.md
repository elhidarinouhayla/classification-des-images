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
   - Réseau de neurones séquentiel :  
     - Couche `Flatten`  
     - Couche cachée `Dense(128, relu)`  
     - Couche de sortie `Dense(10, softmax)`

4. **Compilation et entraînement**
   - Optimiseur : **Adam**  
   - Fonction de perte : **sparse_categorical_crossentropy**  
   - Entraînement sur **10 époques**

5. **Évaluation**
   - Précision sur les données de test : **≈ 88%**

---

## 🧩 Technologies utilisées
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib

---

👩‍💻 Auteur

El hidari Nouhayla