# Projet : Site Web Interactif pour les Jeux Olympiques de Paris 2024

## Contexte
Le Comité d'Organisation des Jeux Olympiques de Paris 2024 souhaite développer un site web dédié à l'événement. Ce site vise à fournir des informations essentielles aux touristes et aux passionnés des Jeux Olympiques, améliorant ainsi leur expérience globale.

## Objectifs
Créer une plateforme web interactive et informative qui englobe divers aspects des Jeux Olympiques de Paris 2024.

## Datasets
Pour ce projet, vous utiliserez principalement les datasets suivants :
- [Dataset principal des Jeux Olympiques de Paris 2024](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games)
- [Parcours de la flamme olympique](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games?select=torch_route.csv)
- [200 meilleurs restaurants parisiens selon TripAdvisor](https://www.kaggle.com/datasets/kanchana1990/200-best-paris-eateries-tripadvisor-24)

## Fonctionnalités Principales

### 1. Dashboard des Médailles
- Créer un tableau de bord récapitulatif des médailles par pays.
- Proposer des visualisations créatives (ex : carte interactive, graphiques dynamiques).

### 2. Recherche d'Athlètes
- Implémenter un formulaire de recherche avancée permettant de filtrer les athlètes selon divers critères :
  - Nom
  - Nationalité
  - Discipline si disponible
- Afficher les médailles obtenues par l'athlète, le cas échéant.

### 3. Carte Interactive des Sites Olympiques
- Développer une carte interactive montrant tous les sites des compétitions.
- Permettre aux utilisateurs de cliquer sur chaque site pour voir :
  - Les épreuves qui s'y déroulent
  - Les horaires des compétitions
  - Les athlètes participants

### 4. Agenda Interactif des Épreuves
- Créer un calendrier dynamique des épreuves.
- Inclure des filtres par sport, date, et lieu.

### 5. Parcours de la Flamme Olympique
- Visualiser le trajet de la flamme olympique sur une carte interactive.

### 6. Guide Gastronomique
- Intégrer une fonctionnalité pour afficher les restaurants les plus proches des sites olympiques à Paris lorsqu'on les séléctionne.
- Utiliser le dataset des 200 meilleurs restaurants parisiens de TripAdvisor.

### 7. Système de FAQ Intelligent
- Développer un outil de recherche intelligent pour les questions fréquemment posées.
- Utiliser le machine learning pour :
  - Détecter les doublons de questions
  - Proposer les 3 questions les plus similaires à une requête donnée
- optionnel: Intégrer un système de feedback pour améliorer continuellement les réponses.

## Spécifications Techniques

### Framework Web
- Utiliser Python avec Flask comme framework web principal.
  - Flask est léger et flexible, idéal pour ce type de projet éducatif.
  - Il permet une intégration facile avec diverses bibliothèques de visualisation.

### Gestion des Données
- Utiliser pandas pour la manipulation et l'analyse des données CSV.
  - Pandas est parfaitement adapté pour travailler avec des fichiers CSV fournis.
  - Il offre des fonctionnalités puissantes pour le filtrage, le tri et l'agrégation des données.

### Visualisation
- Employer Plotly pour créer des graphiques interactifs (ex : dashboard des médailles).
- Utiliser Folium pour les cartes interactives (parcours de la flamme olympique, sites des compétitions).

### Interface Utilisateur
- Intégrer Streamlit pour le développement rapide de l'interface utilisateur.
  - Streamlit est particulièrement adapté pour créer des applications de data science interactives avec peu de code.
  - Il s'intègre bien avec pandas, Plotly et Folium.

### Machine Learning
- Utiliser scikit-learn pour les tâches de base en ML, comme la vectorisation de texte et les mesures de similarité.
- Employer des bibliothèques comme NLTK ou spaCy pour le traitement du langage naturel (NLP) nécessaire à la FAQ intelligente.

### Stockage de Données
- Stocker les données dans des fichiers CSV, conformément au format des datasets fournis.
- optionnel: Si nécessaire, utiliser SQLite pour une base de données légère, facile à mettre en place sans configuration serveur.

### DevOps
- Utiliser Git pour le contrôle de version.
- Mettre en place une pipeline CI/CD avec GitHub Actions pour l'intégration et le déploiement continus.
- Implémenter des tests unitaires avec pytest.
- optionnel: Utiliser Docker pour la containerisation de l'application si nécessaire pour le déploiement.

### Gestion de Projet
- Utiliser Jira pour la gestion des tâches et le suivi de l'avancement.
- Mettre en place des sprints Agile de 2 semaines.
- Organiser des stand-ups quotidiens et des revues de sprint.

### Déploiement
- Utiliser les serveurs INSA pour le déploiement de l'application web.

## Livrables
1. Code source complet sur GitHub
2. Documentation technique et guide utilisateur
3. Rapport de performance du modèle de ML pour la FAQ
4. Présentation finale du projet

