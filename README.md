# 🎬 MovieLens Analysis – Projet Data Analyst

## 🟨 QUOI : Objectif du projet

Ce projet est une **analyse complète du dataset MovieLens 100k**, menée dans le cadre de ma reconversion professionnelle vers les métiers de la data.  
Il s’agit d’un **cas d’étude concret** couvrant tout le pipeline de données : depuis l’exploration en Python jusqu’à la visualisation dans Power BI, en passant par la modélisation relationnelle et analytique avec PostgreSQL.

L'objectif : concevoir un **tableau de bord interactif** permettant d’explorer les préférences utilisateurs, les tendances de notation, et de proposer des recommandations de films basées sur les données.

---

## 🟩 POURQUOI : Intérêt métier

🎯 En tant qu’ancien producteur/réalisateur, j’ai choisi un sujet proche de mon univers (le cinéma) pour démontrer ma capacité à :
- **Structurer et modéliser des données** issues de sources brutes
- **Extraire des insights utiles** pour la prise de décision (produit, marketing, contenu)
- **Concevoir des visualisations interactives** compréhensibles par tous les profils
- **Raconter une histoire à travers les données**, en appliquant mes compétences narratives dans un contexte analytique

💡 J’ai volontairement choisi un **dataset simple mais connu**, pour montrer qu’**il est possible d’en tirer des insights intéressants** à condition de structurer la démarche correctement.  
Ce projet est aussi un **exercice de bonnes pratiques** techniques : utilisation de **CTE**, **requêtes SQL optimisées**, **vues normalisées**, et conception d’un modèle BI clair.  
Enfin, je voulais survoler **plusieurs technologies clés** (Python, PostgreSQL, Power BI) pour me positionner en phase avec les **attentes actuelles en entreprise** pour un poste de data analyst.

---

## 🟦 COMMENT : Démarche technique

### 🔢 Dataset
- **Source** : MovieLens 100k (env. 100 000 notations, 9 000 utilisateurs, 1 600 films)
- **Format** : fichiers CSV

### 🧠 Étapes du projet

| Étape                          | Outils/Techniques utilisés                                |
|-------------------------------|------------------------------------------------------------|
| 📊 Analyse exploratoire (EDA) | Python, pandas, matplotlib, seaborn                       |
| 🧱 Modélisation relationnelle  | PostgreSQL (tables normalisées, contraintes, clés)        |
| 🧮 Vues analytiques SQL        | CTE, agrégats, vues pour la BI (films polarisants, etc.) |
| 📊 Visualisation               | Power BI (relations, KPIs, interactions, storytelling)     |

### 🧾 Vues SQL créées

- `dim_movies`, `dim_genres` (dimensions)
- `vue_notes_par_annee`, `vue_notes_par_decennie_genre`
- `vue_profils_utilisateurs`, `vue_films_polarisants`
- `vue_films_souscotes`, `vue_top_films_notes`
- `vue_recommandations_par_genre`

### 📁 Organisation du projet

```
├── notebooks/
│   ├── [01_EDA_MovieLens.ipynb](notebooks/01_EDA_MovieLens.ipynb)
│   ├── [02_Schema_SQL_MovieLens.ipynb](notebooks/02_Schema_SQL_MovieLens.ipynb)
│   ├── [03_Creation_Vues_Analytique.ipynb](notebooks/03_Creation_Vues_Analytique.ipynb)
│   └── [04_PowerBI_Preparation.ipynb](notebooks/04_PowerBI_Preparation.ipynb)
├── [MovieLens_Report.pbix](MovieLens_Report.pbix)           # Rapport Power BI
├── [views.sql](views.sql)                       # Code SQL des vues
├── [schema.sql](schema.sql)                     # Script de création des tables
```

---

## 📊 Rapport Power BI

Le fichier `.pbix` peut être consulté ici :  
📎 [MovieLens_Report.pbix]https://github.com/HammicheR/MovieLens-Analysis/blob/master/Movielens_Rapport_PBI.pbix

> 🚧 Le lien vers la version en ligne (Power BI Service) sera ajouté dès publication.

Le tableau de bord permet de :
- Explorer l’évolution des notes dans le temps
- Comparer les genres, décennies, profils utilisateurs
- Mettre en avant les films polarisants, sous-cotés ou recommandés

---

## 🧠 Ce que ce projet démontre

✔️ Maîtrise des bases de la data analyse : Python, SQL, modélisation et BI  
✔️ Capacité à construire un projet complet, structuré et réutilisable  
✔️ Sens métier et storytelling appliqué à la donnée  
✔️ Volonté de respecter les bonnes pratiques utilisées en entreprise  
✔️ Adaptabilité à plusieurs outils et capacité à évoluer dans un environnement technique

---

## 📫 Contact

👤 Réalisé par Hammiche Reda – Data Analyst en reconversion (ex-producteur/réalisateur)  
🔗 https://www.linkedin.com/in/hammicheradouan/  
📧 hammiche.radouan@outlook.com

# 🎬 MovieLens Analysis – Projet Data Analyst

## 🟨 QUOI : Objectif du projet

Ce projet est une **analyse complète du dataset MovieLens 100k**, menée dans le cadre de ma reconversion professionnelle vers les métiers de la data.  
Il s’agit d’un **cas d’étude concret** couvrant tout le pipeline de données : depuis l’exploration en Python jusqu’à la visualisation dans Power BI, en passant par la modélisation relationnelle et analytique avec PostgreSQL.

L'objectif : concevoir un **tableau de bord interactif** permettant d’explorer les préférences utilisateurs, les tendances de notation, et de proposer des recommandations de films basées sur les données.

---

## 🟩 POURQUOI : Intérêt métier

🎯 En tant qu’ancien producteur/réalisateur, j’ai choisi un sujet proche de mon univers (le cinéma) pour démontrer ma capacité à :
- **Structurer et modéliser des données** issues de sources brutes
- **Extraire des insights utiles** pour la prise de décision (produit, marketing, contenu)
- **Concevoir des visualisations interactives** compréhensibles par tous les profils
- **Raconter une histoire à travers les données**, en appliquant mes compétences narratives dans un contexte analytique

💡 J’ai volontairement choisi un **dataset simple mais connu**, pour montrer qu’**il est possible d’en tirer des insights intéressants** à condition de structurer la démarche correctement.  
Ce projet est aussi un **exercice de bonnes pratiques** techniques : utilisation de **CTE**, **requêtes SQL optimisées**, **vues normalisées**, et conception d’un modèle BI clair.  
Enfin, je voulais survoler **plusieurs technologies clés** (Python, PostgreSQL, Power BI) pour me positionner en phase avec les **attentes actuelles en entreprise** pour un poste de data analyst.

---

## 🟦 COMMENT : Démarche technique

### 🔢 Dataset
- **Source** : MovieLens 100k (env. 100 000 notations, 9 000 utilisateurs, 1 600 films)
- **Format** : fichiers CSV

### 🧠 Étapes du projet

| Étape                          | Outils/Techniques utilisés                                |
|-------------------------------|------------------------------------------------------------|
| 📊 Analyse exploratoire (EDA) | Python, pandas, matplotlib, seaborn                       |
| 🧱 Modélisation relationnelle  | PostgreSQL (tables normalisées, contraintes, clés)        |
| 🧮 Vues analytiques SQL        | CTE, agrégats, vues pour la BI (films polarisants, etc.) |
| 📊 Visualisation               | Power BI (relations, KPIs, interactions, storytelling)     |

### 🧾 Vues SQL créées

- `dim_movies`, `dim_genres` (dimensions)
- `vue_notes_par_annee`, `vue_notes_par_decennie_genre`
- `vue_profils_utilisateurs`, `vue_films_polarisants`
- `vue_films_souscotes`, `vue_top_films_notes`
- `vue_recommandations_par_genre`

### 📁 Organisation du projet

```
├── notebooks/
│   ├── [01_EDA_MovieLens.ipynb](notebooks/01_EDA_MovieLens.ipynb)
│   ├── [02_Schema_SQL_MovieLens.ipynb](notebooks/02_Schema_SQL_MovieLens.ipynb)
│   ├── [03_Creation_Vues_Analytique.ipynb](notebooks/03_Creation_Vues_Analytique.ipynb)
│   └── [04_PowerBI_Preparation.ipynb](notebooks/04_PowerBI_Preparation.ipynb)
├── [MovieLens_Report.pbix](MovieLens_Report.pbix)           # Rapport Power BI
├── [views.sql](views.sql)                       # Code SQL des vues
├── [schema.sql](schema.sql)                     # Script de création des tables
```

---

## 📊 Rapport Power BI

Le fichier `.pbix` peut être consulté ici :  
📎 [MovieLens_Report.pbix]https://github.com/HammicheR/MovieLens-Analysis/blob/master/Movielens_Rapport_PBI.pbix

> 🚧 Le lien vers la version en ligne (Power BI Service) sera ajouté dès publication.

Le tableau de bord permet de :
- Explorer l’évolution des notes dans le temps
- Comparer les genres, décennies, profils utilisateurs
- Mettre en avant les films polarisants, sous-cotés ou recommandés

---

## 🧠 Ce que ce projet démontre

✔️ Maîtrise des bases de la data analyse : Python, SQL, modélisation et BI  
✔️ Capacité à construire un projet complet, structuré et réutilisable  
✔️ Sens métier et storytelling appliqué à la donnée  
✔️ Volonté de respecter les bonnes pratiques utilisées en entreprise  
✔️ Adaptabilité à plusieurs outils et capacité à évoluer dans un environnement technique

---

## 📫 Contact

👤 Réalisé par Hammiche Reda – Data Analyst en reconversion (ex-producteur/réalisateur)  
🔗 https://www.linkedin.com/in/hammicheradouan/  
📧 hammiche.radouan@outlook.com
