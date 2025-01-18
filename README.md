# **Projet 8 : Réalisez un traitement dans un environnement Big Data sur le Cloud**

## **Contexte du projet**
Ce projet fait partie du parcours **Machine Learning Engineer** de **centralesupélec **et d’**OpenClassrooms**. Il s’agit de construire une solution performante et évolutive pour traiter des données massives en combinant **PySpark** pour le traitement distribué et les services cloud d’**AWS**.

---

## **Objectifs**
1. **Valider un pipeline de traitement d’images en local** avec un jeu de données réduit.
2. **Migrer la solution vers le cloud AWS** pour traiter un volume important d'images.
3. **Optimiser les coûts et la scalabilité** en utilisant AWS EMR et S3.

---

## **Outils et technologies**
- **Langages** : Python (PySpark, TensorFlow, Pandas).
- **Cloud** : AWS (EMR, S3, EC2).
- **Modèle utilisé** : MobileNetV2 pour l’extraction des caractéristiques.
- **Autres** : Jupyter Notebook, Docker (local), Spark, Hadoop.

---

## **Résumé des étapes**

### **Phase 1 : Développement local**
1. **Environnement** :
   - Machine virtuelle Ubuntu (local).
   - Installation de Spark pour simuler un calcul distribué.
2. **Pipeline local** :
   - Prétraitement des images.
   - Extraction des caractéristiques avec MobileNetV2.
   - Stockage des résultats au format parquet.
3. **Résultat** :
   - Validation du pipeline avec un jeu de données réduit.

---

### **Phase 2 : Migration vers AWS**
1. **Configuration du cluster AWS EMR** :
   - Création d’un cluster EMR (EC2, S3).
   - Configuration de Spark, Hadoop, TensorFlow et JupyterHub.
2. **Traitement complet** :
   - Transfert des données vers S3.
   - Exécution du pipeline sur un grand volume d’images.
   - Réduction de dimension avec PCA.
3. **Optimisation** :
   - Scalabilité grâce à la configuration dynamique des nœuds.
   - Réduction des coûts en utilisant les instances EC2 Spot.

---

## **Résultats**
- **Efficacité** : Pipeline exécuté avec succès à grande échelle sur EMR.
- **Scalabilité** : Le cluster est ajustable selon les besoins (horizontalement et verticalement).
- **Économie** : Utilisation d'instances Spot pour minimiser les coûts.
- **Flexibilité** : Utilisation de S3 pour le stockage évolutif et persistant.

---

## **Prérequis**
- Un compte AWS actif.
- Accès à S3, EMR et EC2 via la CLI AWS.
- Jupyter Notebook installé localement pour tester le pipeline avant migration.

---





