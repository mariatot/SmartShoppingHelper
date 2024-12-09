# SmartShoppingHelper
Application d’aide aux courses utilisant l’intelligence artificielle pour afficher le Nutri-Score des produits, évaluer l’équilibre nutritionnel d’un panier, et proposer des recommandations pour des choix alimentaires plus sains et responsables.

![Aperçu](Smart_shopping_helper_img.jpg)

# **Aide aux courses intelligente**  
Une application innovante pour améliorer les choix alimentaires grâce au Nutri-Score et à des recommandations personnalisées.  

## **Description**  
Ce projet propose une application d’aide aux courses qui aide les utilisateurs à :  
- Visualiser le Nutri-Grade des produits, même lorsqu’il n’est pas affiché sur l’étiquette.  
- Évaluer l’équilibre nutritionnel de leur panier grâce à une répartition par Nutri-Grades.  
- Recevoir des recommandations pour améliorer leurs achats, comme des produits bio, locaux ou sans conservateurs.  

## **Étapes du projet**  
1. **Nettoyage des données** :  
   - Suppression des colonnes et lignes inutiles ou incomplètes.  
   - Traitement des valeurs aberrantes et création de nouvelles variables pertinentes.  

2. **Analyse exploratoire** :  
   - Étude univariée, bivariée et multivariée pour identifier les tendances et corrélations dans les données.  

3. **Modélisation** :  
   - Test de plusieurs modèles pour prédire le Nutri-Grade et le Nutri-Score manquants :  
      - KNN : Accuracy = 72 %.  
      - Random Forest Regressor : Modèle retenu avec R² = 95 %.  

4. **Faisabilité** :  
   - Prédiction du Nutri-Grade manquant avec des algorithmes robustes.  
   - Recommandation de produits similaires, meilleurs en Nutri-Score ou bio.  

## **Technologies utilisées**  
- Python (pandas, NumPy, scikit-learn, matplotlib, seaborn).  
- Algorithmes de Machine Learning : KNN, Régression linéaire, Random Forest.  

## **À explorer**  
- Validation du modèle sur d'autres jeux de données.  
- Amélioration des informations sur les catégories et labels des produits.  
- Anticipation des futures mises à jour du calcul du Nutri-Score.  

## **Données**  
Les données utilisées proviennent de [Open Food Facts](https://world.openfoodfacts.org/), une base de données citoyenne et ouverte sur les produits alimentaires.  
