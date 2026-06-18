# 🧠 Dashboard Power BI — Santé Mentale des Jeunes Adultes

Quels facteurs comportementaux et environnementaux (sommeil, stress, alimentation) constituent les principaux déterminants des troubles de santé mentale chez les jeunes adultes ?

## 📌 Contexte
Projet réalisé en mars 2026 dans le cadre de la formation BUT2 passerelle Technologie de l'information — Parcours Sciences des Données (IUT Villetaneuse, Université Sorbonne Paris Nord), en binôme avec Bajiry DIAKITE.

* **Source des données :** Kaggle — Student Depression Dataset
* **Volume :** 3 000 individus, répartis sur 7 pays (USA, Inde, Japon, Australie, Canada, Brésil, Allemagne)
* **Outil utilisé :** Power BI Desktop

---

## 📊 Structure du Rapport (2 pages)

### Page 1 — Vue d'ensemble géographique
L'objectif de cette page est de situer globalement la population étudiée et de fournir des filtres globaux pour l'exploration du rapport.
* **KPIs principaux :** Nombre total de personnes étudiées (3 000), Âge Moyen (~41 ans), Âge minimum (18) et Âge maximum (64).
* **Treemap :** Répartition et volume des individus selon leur pays d'origine.
* **Carte géographique (Bing Maps) :** Localisation visuelle des répondants à l'échelle mondiale.
* **Filtres (Slicers) :** Filtrage interactif par tranche d'âge, genre et pays.

### Page 2 — Analyse comportementale & Facteurs de risque
Cette page creuse les corrélations entre le mode de vie des individus et leur indicateur de bien-être.
* **Scatter Plot (Nuage de points) :** Analyse de la corrélation entre le volume d'heures de sommeil et le score de bonheur.
* **Tableau croisé :** Analyse croisée du score de bonheur moyen selon la condition de santé mentale (Anxiety, Depression, PTSD, Bipolar, None) et le niveau de stress ressenti (Low / Moderate / High).
* **Donut Charts :** Répartition de la population par genre et par niveau de stress global.
* **Pie Chart :** Proportion des différents types de régimes alimentaires (Junk Food, Balanced, Vegetarian, Keto, Vegan).

---

## ⚙️ Compétences Power BI mobilisées

| Compétence | Détail |
| :--- | :--- |
| **Importation & Nettoyage** | Connexion au fichier CSV de Kaggle, traitement des types de données et nettoyage des colonnes clés. |
| **Préparation des données** | Modélisation basée sur une table unique optimisée pour le filtrage croisé (Cross-filtering). |
| **Calculs DAX** | Création de mesures pour le calcul des moyennes (Score de bonheur moyen) et des volumes globaux. |
| **Visualisation** | Choix et configuration des visuels (KPI cards, scatter plot, treemap, donuts) adaptés aux types de variables. |
| **Interactivité** | Mise en place de segments de filtrage synchronisés pour une exploration fluide. |

---

## 🔍 Principaux résultats de l'analyse

* **Sommeil & Bien-être :** Le graphique met en évidence une corrélation positive claire : un volume de sommeil plus élevé est globalement associé à un meilleur score de bonheur.
* **Impact majeur du stress :** Un niveau de stress qualifié de "Low" est systématiquement lié aux scores de bonheur moyens les plus élevés, et ce, peu importe la condition de santé mentale de l'individu.
* **Uniformité des régimes :** La répartition des habitudes alimentaires est presque parfaitement équitable (~20% pour chaque profil), montrant que ce facteur est homogène au sein de l'échantillon.

---

## 📁 Contenu du dépôt
📦 dashboard-sante-mentale-powerbi
 - 📄 rapport.pbix   ← Fichier source Power BI Desktop
 - 📄 rapport.pdf    ← Export du dashboard pour lecture rapide
 - 📄 README.md     ← Présentation du projet

## 👤 Auteurs
* **Nassim BERRABAH**
* **Bajiry DIAKITE**
*  BUT2 passerelle Technologie de l'information (Informatique, Sciences des Données) 
* *IUT de Villetaneuse, Université Sorbonne Paris Nord*
