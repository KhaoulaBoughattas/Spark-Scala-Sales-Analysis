# Spark Scala Sales Analysis

Ce projet est un TP d'analyse de données avec **Apache Spark en Scala**.  
Il couvre le traitement de fichiers CSV pour les ventes, les produits et les vendeurs, l'utilisation des **DataFrames**, **Datasets typés**, et **Spark SQL**, ainsi que des fonctions avancées pour la comparaison des performances.


---

## 📝 Description du TP

### 1️⃣ Chargement des données
- Chargement des CSV `Products.csv`, `Sales.csv`, `Sellers.csv` avec des **schémas explicites**.
- Affichage des 5 premières lignes et des schémas.

### 2️⃣ Spark SQL & Manipulation
- Création de **vues temporaires** pour SQL.
- Jointures pour obtenir des informations complètes sur les ventes.
- Vue des produits avec prix et quantité vendue.
- Calcul du revenu moyen des commandes.
- Comparaison des performances des vendeurs par rapport à leur **objectif quotidien**.
- Jointure left join pour obtenir une vue globale.

### 3️⃣ Fonctions Window Avancées
- Classement des vendeurs par chiffre d’affaires.
- Montant cumulé des ventes par vendeur au fil du temps.
- Comparaison de chaque vente à la moyenne des ventes du même produit.
- Rang des produits par catégorie selon le volume de ventes.

### 4️⃣ Datasets Typés (API Typée)
- Création des `case classes` pour Product, Sale, Seller.
- Conversion des DataFrames en Datasets typés.
- Détermination des produits les plus vendus.
- Analyse détaillée des performances des vendeurs.
- Analyse des ventes par catégorie avec détection des catégories sous-performantes (objectif fixe et dynamique).

### 5️⃣ Comparaison DF vs DS
- Comparaison des **performances** entre DataFrame et Dataset :
  - Temps d’exécution
  - Count des résultats
- Optimisation : cache, partitionnement, projection.

---

## 📌 Instructions pour exécuter le notebook

1. Cloner le dépôt :
```bash
git clone https://github.com/<votre-username>/Spark-Scala-Sales-Analysis.git
```
