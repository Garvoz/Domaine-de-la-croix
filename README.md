# 🍷 Business Case : Domaine de la croix

**Auteur : Antoine Savournin**  
**Formation : Wild Code School – 2024-2025**  
**Projet de Certification – Data Analyst**

---

## 🎯 Objectif du projet

Ce projet s’inscrit dans le cadre du passage de la **certification Data Analyst – Wild Code School**. Il représente le bloc 4 (Business Case) de l’examen final, à compléter après trois blocs de cas pratiques techniques.

Le **Domaine des Croix** souhaite lancer un **Pinot Noir de Bourgogne** sur le **marché américain**. Pour cela, il est essentiel de fixer un **prix compétitif et justifié**, dans un secteur concurrentiel, tout en vulgarisant l’approche analytique utilisée.

Ce projet a pour but de fournir :
- Une **analyse du marché international et français du vin**
- Une **analyse comparative** des vins similaires
- Une **recommandation de prix claire**, en fonction du positionnement souhaité
- Une **présentation business orientée client non-technique**
- Un **dashboard interactif Power BI** pour l'exploration des résultats

---

## 🧰 Outils & Langages

- **Python (Google Colab)** : extraction, transformation, nettoyage
- **Power BI** : visualisations interactives (cartes, TCD, filtres dynamiques)
- **DAX** : mesures dynamiques pour les indicateurs
- **NLTK, WordCloud** : analyse sémantique de descriptions œnologiques
- **Google Slides** : support de présentation vulgarisé


---

## 🧪 Démarche & Méthodologie

1. **Nettoyage des données** : gestion fine des valeurs manquantes
2. **Création d’une colonne “millésime”** via `regex`
3. **Exploration du dataset** :
   - WordClouds par zones (monde, France, Pinot Noir)
   - Répartition géographique des cépages
   - Corrélations entre prix et notes
4. [**Construction d’un dashboard interactif Power BI**](./livrables_pdf/dashboard_domaine_de_la_croix.pdf), structuré en **4 pages** :
   - Vue mondiale
   - Analyse centrée sur la France
   - Focus Pinot Noir
   - Page dédiée au Domaine des Croix (comparaison ciblée)
5. **Comparaison des vins similaires** (Pinot Noir, Bourgogne, millésime 2016)
6. **Recommandation personnalisée** avec 3 scénarios de pricing
7. [**Présentation synthétique des résultats au client (PowerPoint)**](./livrables_pdf/presentation_domaine_de_la_croix.pdf)

---

## 💡 Recommandation finale

| Gamme         | Fourchette de prix | Justification                                      |
|---------------|--------------------|---------------------------------------------------|
| Entrée        | ~85€               | Basée sur la médiane des Corton                   |
| Moyenne       | 100–110€           | Plafond du cluster principal                      |
| Haut de gamme | 155–160€           | Aligné sur les vins de 2016 les mieux notés       |

---

## 📚 Autres blocs de certification

### 🔹 Bloc 1 – SQL, RGPD, Web Scraping & API
- **SQL** : requêtes complexes, modélisation relationnelle
- **RGPD** : compréhension des grands principes de la réglementation européenne
- **Web Scraping** : analyse de structure HTML
- **API REST** : utilisation de l’API `adresse.gouv.fr` pour du reverse geocoding

### 🔹 Bloc 2 – Pandas, Regex, Agilité
- **Python / Pandas** : manipulation de données immobilières
- **Regex** : extraction de code postal à partir d’adresses textuelles
- **Méthodologie Agile (Scrum)** : identification des rôles clés (PO, Scrum Master, Dev)

### 🔹 Bloc 3 – Machine Learning
- **NLP (traitement de texte)** : préparation de la colonne `description`
- **Régression** : prédiction du prix d’un bien à partir de variables numériques et catégorielles
- **Classification** : prédiction du type de bien
- **Évaluation des modèles** : corrélation, métriques, interprétation métier

---

## 👤 À propos

Antoine Savournin – Data Analyst certifié  
🎓 En reconversion vers la Data Engineering  
📫 afasavournin@gmail.com  
🔗 [Portfolio & GitHub](https://github.com/Garvoz)  
🔗 [LinkedIn](https://www.linkedin.com/in/antoine-savournin-3b9277109/)

---
