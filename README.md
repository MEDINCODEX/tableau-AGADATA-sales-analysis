# 📊 Analyse des données commerciales – Tableau

## 🧠 Contexte du projet
Les entreprises disposent de grandes quantités de données commerciales (ventes, retours, clients, produits, satisfaction).
L’objectif de ce projet est d’exploiter ces données afin de mieux comprendre les performances commerciales et d’aider à la prise de décision.

---

## 🎯 Objectifs du projet
- Importer et connecter plusieurs sources de données
- Nettoyer et préparer les données pour l’analyse
- Créer des hiérarchies et regroupements
- Réaliser des visualisations simples et avancées
- Construire un dashboard interactif et lisible
- Utiliser des calculs et paramètres pour enrichir l’analyse

---

## ⚙️ Sources de données
Les données utilisées comprennent :
- Achats (commandes, ventes, quantités, profits)
- Évaluations (satisfaction client)
- Retours
- Personnes (clients)

---

## 🔗 Modélisation des données
- Jointures physiques :
  - LEFT JOIN : Achats ↔ Évaluations
  - LEFT JOIN : Achats ↔ Retours
  - INNER JOIN : Achats ↔ Personnes
- Relation logique entre Achats et Évaluations afin de préserver la granularité au niveau de la commande (ID de Commande).

---

## 🏗️ Hiérarchies & regroupements
- Hiérarchie Produit : Catégorie → Sous-catégorie → Nom du produit
- Hiérarchie Géographie : Pays → Région → Ville
- Regroupement des sous-catégories pour simplifier l’analyse

---

## 📈 Visualisations réalisées
### Visualisations de base :
- Ventes par sous-catégorie
- Ventes par segment
- Quantité par hiérarchie produit
- Satisfaction client par commande
- Ventes par date (jour / mois / année)

## o-o Visualisations avancées :
- Carte : ventes par pays / région
- Graphique à bulles : ventes par segment
- Graphique à double axe : ventes vs quantités
- Graphique miroir
- Lignes de référence (targets / moyennes)

---

## 🧮 Calculs & paramètres
- Champs calculés simples et conditionnels (IF / THEN / ELSE)
- Mesures agrégées (SUM, AVG)
- Paramètre dynamique pour définir un objectif de ventes (Sales Target)
- Comparaison des ventes par rapport à l’objectif

---

## 📊 Dashboard final
- Sélection des visualisations les plus pertinentes
- Filtres globaux (date, pays, segment)
- Paramètres interactifs
- Mise en forme claire et cohérente
- Dashboard conçu pour l’exploration et la prise de décision

---

## 🛠️ Outils utilisés
- Tableau Desktop / Tableau Public
- Données CSV / Excel

---

## 📌 Auteur
Projet réalisé dans un cadre pédagogique pour l’apprentissage de l’analyse de données et de la visualisation avec Tableau.
"# tableau-AGADATA-sales-analysis" 
