# Protocole de Mémoire (MCP)

## Objectif
Définir comment Claude Nexus stocke, organise et récupère les informations importantes pour maintenir la continuité et le contexte à travers les interactions.

## Structure des données mémorielles

### 1. Mémoire à court terme
- **Conversations récentes** - Stockage des échanges des dernières 24 heures
- **Contexte de session** - Objectifs, tâches et thématiques de la conversation en cours
- **Variables temporaires** - Données transitoires nécessaires à la tâche actuelle

### 2. Mémoire à moyen terme
- **Projets en cours** - Détails des projets actuels avec leurs états et priorités
- **Préférences récentes** - Choix et ajustements récents de l'utilisateur
- **Contextes récurrents** - Modèles d'interaction pour différentes situations

### 3. Mémoire à long terme
- **Profil utilisateur** - Préférences durables, domaines d'expertise et centres d'intérêt
- **Base de connaissances personnelles** - Informations spécifiques à l'utilisateur
- **Historique des projets** - Archive des projets terminés avec leurs résultats

## Mécanismes d'accès et de récupération

1. **Indexation thématique** - Organisation des informations par thèmes et domaines
2. **Recherche contextuelle** - Récupération basée sur la pertinence par rapport au contexte actuel
3. **Association temporelle** - Connexions entre événements et informations basées sur la chronologie

## Implémentation technique

### Stockage
- Fichiers JSON pour les données structurées
- Documents Markdown pour les informations textuelles longues
- Base de données vectorielle pour la recherche sémantique (optionnel)

### Processus de mise à jour
1. Extraction des informations clés des conversations
2. Validation et structuration des données
3. Indexation et stockage
4. Archivage et compression des données anciennes

## Considérations éthiques
- Protection des informations sensibles
- Transparence sur les données conservées
- Paramètres de contrôle utilisateur

## Prochaines étapes
- Développer les schémas JSON pour chaque type de mémoire
- Créer les scripts d'extraction et de structuration
- Implémenter un prototype de système de récupération