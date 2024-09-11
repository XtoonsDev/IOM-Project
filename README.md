# LSTM Investment Optimization Model

## Table des Matières

- [État du Projet](#état-du-projet)
- [Accessibilité au Modèle](StartUp.md) 
- [Fonctionnalités](#fonctionnalités)
- [Utilisation](#utilisation)
- [Comment Contribuer](#comment-contribuer)
- [Entraînement du Modèle](#entraînement-du-modèle)
- [Licence](#licence)

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)

## État du Projet
- **En développement** : Le modèle est en cours d'entraînement pour détecter 2 pattern (Flag et Pennant).
- **Dernière mise à jour** : 11 septembre 2024.
- **Progression** : 0/50 patterns acquis. 

## Progression du Projet

### Phases du Développement
1. [x] Installation du modèle sur serveur dédié.
2. [x] Préparation des données pour l'entraînement.
3. [x] Entraînement initial du modèle sur 2 patterns.
4. [ ] Préparation du service Web (Client)
5. [ ] Intégration de l'API pour les données en temps réel.
6. [ ] Déploiement du modèle pour l'utilisation en production.

## Introduction

L'objectif est de développer un système basé sur l'intelligence artificielle capable de détecter en temps réel des patterns techniques sur des graphiques boursiers. Utilisant un modèle LSTM (Long Short-Term Memory), le système sera entraîné à reconnaître des motifs récurrents (Pattern) dans les données financières, tels que les configurations de prix (ex : Épaules-Tête-Épaules, Double Top, etc.) et les signaux d'indicateurs techniques (comme les croisements de moyennes mobiles ou le RSI). L'approche consistera à alimenter le modèle avec des données historiques issues de divers marchés (crypto-monnaies, actions, ETF, matières premières, et autres) et à le former à identifier ces patterns, avec ou sans indicateurs techniques, afin de maximiser la détection de mouvements de marché potentiellement exploitables.

Une fois le modèle entraîné, il sera appliqué en temps réel pour analyser les fluctuations des prix sur plusieurs marchés simultanément. Dès qu'un pattern défini est détecté, le système émettra des alertes, permettant ainsi une réactivité accrue pour les prises de décision financières. Ce projet vise à exploiter les capacités des réseaux de neurones récurrents, tels que les LSTM, pour capturer la nature séquentielle et dynamique des marchés financiers, tout en automatisant la détection de configurations techniques complexes pour optimiser les stratégies de trading.




## Fonctionnalités

- **Prévision des Prix** : Utilise LSTM pour prédire les mouvements futurs des prix des actifs.
- **Optimisation de Portefeuille** : Recommande la meilleure répartition des investissements pour maximiser le rendement attendu.
- **Analyse de Sentiment (optionnel)** : Intègre les données textuelles pour ajuster les prédictions et les décisions d'investissement.
- **Interface Utilisateur** : Interface pour visualiser les prévisions et les recommandations de portefeuille.

## Utilisation

Le lien d'accès à l'IA n'est pas encore disponible.


## Comment Contribuer

Les contributions sont les bienvenues ! Voici comment vous pouvez aider :
1. **Soumettre des données** : Utilisez les modèles fournis pour partager des données de marché et des annotations de patterns. 
2. **Suggérer des améliorations** : Ouvrez une *issue* pour proposer de nouvelles fonctionnalités ou des améliorations.
3. **Faite un don** : Ce projet est développé sur mon temps libre, une donation me permet de fournir plus de temps au projet.

Pour des détails complets, veuillez consulter le fichier [CONTRIBUTING.md](CONTRIBUTING.md). (En attente de création)

Pour toutes demandes, ouvrez une *issue* (https://github.com/XtoonsDev/LSTM-Trading/issues/new)

## Entraînement du modèle

1. [liste des patterns disponibles](patterns.md).
2. [liste des indicateurs disponibles](indicateurs.md).
