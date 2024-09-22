![](img/logo-insa.jpg)
# INSA 4A Outils et méthodes de développement informatique
## Projet :
## Site Web Interactif pour les Jeux Olympiques de Paris 2024

![](img/paris2024.png)
Le Comité d'Organisation des Jeux Olympiques de Paris 2024 souhaite développer une plateforme web interactive pour les Jeux Olympiques de Paris 2024.  
Vous avez été mandatés pour développer cette plateforme fournissant des informations essentielles aux touristes et aux passionnés des Jeux Olympiques, améliorant ainsi leur expérience globale.





## Cahier des charges

### 1. Dashboard des Médailles
- Créer un tableau de bord récapitulatif des médailles par pays.
- Proposer des visualisations créatives (ex : carte interactive, graphiques dynamiques).
![](img/medailles.png)

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
![](img/carte.jpg)

### 4. Agenda Interactif des Épreuves
- Créer un calendrier dynamique des épreuves.
- Inclure des filtres par sport, date, et lieu.
![](img/agenda.png)

### 5. Parcours de la Flamme Olympique
- Visualiser le trajet de la flamme olympique sur une carte interactive.
![](img/parcours_flamme.jpg)

### 6. Guide Gastronomique
- Intégrer une fonctionnalité pour afficher les restaurants les plus proches des sites olympiques à Paris lorsqu'on les séléctionne.
- Utiliser le dataset des 200 meilleurs restaurants parisiens de TripAdvisor.
![](img/food.jpg)

### 7. Système de FAQ Intelligent
Dans un second temps, le comité olympique vous demandera de développer un outil de recherche intelligent pour les questions fréquemment posées.
- Développer un outil de recherche intelligent pour les questions fréquemment posées.
- Utiliser le machine learning pour :
  - Détecter les doublons de questions
  - Proposer les 3 questions les plus similaires à une requête donnée
- optionnel: Intégrer un système de feedback pour améliorer continuellement les réponses.

## Spécifications Techniques

### Données
Pour ce projet, le comité olympique vous conseille d'utiliser les datasets suivants:  
- [Dataset principal des Jeux Olympiques de Paris 2024](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games)  
- [Parcours de la flamme olympique](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games?select=torch_route.csv)  
- [200 meilleurs restaurants parisiens selon TripAdvisor](https://www.kaggle.com/datasets/kanchana1990/200-best-paris-eateries-tripadvisor-24)

### Framework Web
Pas de contrainte particulière, vous pouvez utiliser le framework de votre choix.
Si vous souhaitez faire le projet en Python, le comité olympique vous conseille d'utiliser Flask comme framework web principal.
  - Flask est léger et flexible, idéal pour ce type de projet éducatif.
  - Il permet une intégration facile avec diverses bibliothèques de visualisation.

### Gestion des Données
Le comité olympique vous conseille d'utiliser python pour la manipulation et l'analyse des données CSV.
- Utiliser pandas pour la manipulation et l'analyse des données CSV.
  - Pandas est parfaitement adapté pour travailler avec des fichiers CSV fournis.
  - Il offre des fonctionnalités puissantes pour le filtrage, le tri et l'agrégation des données.

### Visualisation
- Employer Plotly pour créer des graphiques interactifs (ex : dashboard des médailles).
- Utiliser Folium pour les cartes interactives (parcours de la flamme olympique, sites des compétitions).

### Interface Utilisateur
La encore vous pouvez utiliser le framework de votre choix.  
Pour ceux qui souhaitent faire le projet en Python, le comité olympique vous conseille d'utiliser Streamlit pour le développement rapide de l'interface utilisateur.
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
- Mettre en place une pipeline CI/CD avec GitLab CI pour l'intégration et le déploiement continus.
- Implémenter des tests unitaires avec pytest.
- optionnel: Utiliser Docker pour la containerisation de l'application si nécessaire pour le déploiement.

### Gestion de Projet
- Utiliser Jira pour la gestion des tâches et le suivi de l'avancement.
- Mettre en place des sprints Agile de 2 semaines.
- Organiser des stand-ups quotidiens et des revues de sprint.

### Déploiement
- Utiliser les serveurs INSA pour le déploiement de l'application web.

## Livrables
1. Code source complet sur GitLab
2. Un site web hébergé sur les serveurs INSA
3. Documentation technique et guide utilisateur
4. Rapport de performance du modèle de ML pour la FAQ
5. Présentation finale du projet

