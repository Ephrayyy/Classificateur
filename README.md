📊 Projet Data Science – Prédiction et segmentation de clients


🎯 Objectif global

Analyser plusieurs jeux de données provenant de secteurs variés (banque, santé, télécommunications) afin de détecter les profils à risque et de prédire des comportements clés comme le churn, le défaut de paiement ou la réadmission.

🔍 Problématiques abordées
1. Banque : Quels clients risquent de faire défaut sur leurs prêts ?
Nettoyage des données bancaires (transformation des variables, gestion des valeurs manquantes).

Construction d’un modèle de classification supervisée pour prédire les clients susceptibles de faire défaut.

Évaluation du modèle avec les métriques classiques : accuracy, recall, f1-score.

2. Banque : Quels clients présentent un risque de crédit élevé ?
Création d’une variable cible binaire basée sur un seuil dans une variable continue.

Application de techniques de classification pour repérer les clients à risque.

Analyse des variables les plus discriminantes via un modèle explicatif.

3. Santé : Quels patients risquent d’être réadmis à l’hôpital ?
Exploration des données médicales : variables liées aux hospitalisations, diagnostics, etc.

Préparation des données avec encodage des catégories médicales et traitement des outliers.

Entraînement d’un modèle de classification pour prédire les réadmissions, avec validation croisée.

4. Télécommunications : Quels clients risquent de se désabonner (churn) ?
Analyse complète des données clients (services souscrits, paiements, contrat).

Réduction de dimension avec PCA (15 composantes expliquant 90% de la variance).

Clustering non supervisé (KMeans) pour segmenter les clients.

Taux de correspondance avec le churn réel : 73.44%.

🧠 Techniques utilisées
Analyse exploratoire des données (EDA)

Encodage des variables catégorielles

Standardisation avec StandardScaler

Modélisation supervisée (Logistic Regression, etc.)

Réduction de dimension (PCA)

Clustering non supervisé (KMeans)

Évaluation : Accuracy, Silhouette Score, Matrice de confusion

