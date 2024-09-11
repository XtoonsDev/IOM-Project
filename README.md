# LSTM Investment Optimization Model
Ce projet utilise un modèle LSTM (Long Short-Term Memory) pour optimiser les décisions d'investissement dans les ETF, les cryptomonnaies et les matières premières.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)

## État Actuel
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


## Table des Matières

- [Fonctionnalités](#fonctionnalités)
- [Utilisation](#utilisation)
- [Comment Contribuer](#contribuer)
- [Entraînement du Modèle](#entraînement-du-modèle)
- [Licence](#licence)

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

### Patterns de Continuation
1. [ ] **Flag (Drapeau)** : Petite consolidation après une forte impulsion, avant une reprise dans la même direction.
2. [ ] **Pennant (Fanion)** : Forme de petit triangle formé après une forte impulsion, indiquant une continuation.
3. [ ] **Bullish Rectangle** : Consolidation horizontale entre deux niveaux, suivie d'une cassure haussière.
4. [ ] **Bearish Rectangle** : Consolidation horizontale entre deux niveaux, suivie d'une cassure baissière.
5. [ ] **Ascending Triangle** : Triangle avec des sommets horizontaux et des creux ascendants, indiquant une cassure haussière.
6. [ ] **Descending Triangle** : Triangle avec des creux horizontaux et des sommets descendants, signalant une cassure baissière.
7. [ ] **Symmetrical Triangle** : Triangle où les sommets et les creux convergent, indiquant une cassure dans une direction indéterminée.
8. [ ] **Bullish Wedge** : Le prix se resserre vers le haut, souvent suivi d'une cassure haussière.
9. [ ] **Bearish Wedge** : Le prix se resserre vers le bas, souvent suivi d'une cassure baissière.
10. [ ] **Rising Channel** : Un canal ascendant avec des sommets et des creux parallèles, indiquant une continuation haussière.
11. [ ] **Falling Channel** : Un canal descendant avec des sommets et des creux parallèles, indiquant une continuation baissière.
12. [ ] **Measured Move Up** : Une impulsion haussière suivie d'une consolidation, puis d'une autre impulsion.
13. [ ] **Measured Move Down** : Une impulsion baissière suivie d'une consolidation, puis d'une autre impulsion.
14. [ ] **Cup and Handle** : Une forme en "U" suivie d'une légère consolidation (anse), indiquant une cassure haussière.

### Patterns de Renversement
15. [ ] **Head and Shoulders** : Sommet avec deux sommets plus petits de chaque côté, indiquant un renversement baissier.
16. [ ] **Inverse Head and Shoulders** : Inverse du Head and Shoulders, signalant un renversement haussier.
17. [ ] **Double Top** : Deux sommets consécutifs proches en hauteur, indiquant un renversement baissier.
18. [ ] **Double Bottom** : Deux creux consécutifs proches en profondeur, signalant un renversement haussier.
19. [ ] **Triple Top** : Trois sommets proches en hauteur, indiquant un renversement baissier.
20. [ ] **Triple Bottom** : Trois creux proches en profondeur, signalant un renversement haussier.
21. [ ] **Rounding Bottom** : Un creux arrondi, signalant un renversement haussier à long terme.
22. [ ] **V-Shape Bottom** : Un retournement rapide en forme de V, indiquant une forte reprise haussière.
23. [ ] **Broadening Formation** : Une formation qui s'élargit, souvent indiquant une grande volatilité.
24. [ ] **Diamond Top** : Un pattern rare en forme de diamant, signalant un renversement baissier.
25. [ ] **Diamond Bottom** : Un pattern rare en forme de diamant, signalant un renversement haussier.

### Patterns de Bougies Japonaises (Candlestick)
26. [ ] **Doji** : Une bougie où les prix d'ouverture et de clôture sont très proches, signalant une indécision.
27. [ ] **Hammer** : Petite bougie avec une longue mèche inférieure, signalant un potentiel renversement haussier.
28. [ ] **Inverted Hammer** : Petite bougie avec une longue mèche supérieure, signalant un potentiel renversement haussier.
29. [ ] **Shooting Star** : Bougie avec une longue mèche supérieure, indiquant un renversement baissier.
30. [ ] **Bullish Engulfing** : Une bougie haussière englobant totalement la précédente bougie baissière, signalant un renversement haussier.
31. [ ] **Bearish Engulfing** : Une bougie baissière englobant totalement la précédente bougie haussière, signalant un renversement baissier.
32. [ ] **Morning Star** : Un pattern en trois bougies signalant un renversement haussier.
33. [ ] **Evening Star** : Un pattern en trois bougies signalant un renversement baissier.
34. [ ] **Three White Soldiers** : Trois bougies haussières consécutives, signalant un fort retournement haussier.
35. [ ] **Three Black Crows** : Trois bougies baissières consécutives, signalant un fort retournement baissier.
36. [ ] **Gravestone Doji** : Une bougie en forme de croix avec une longue mèche supérieure, signalant un renversement baissier.
37. [ ] **Dragonfly Doji** : Une bougie en forme de croix avec une longue mèche inférieure, signalant un renversement haussier.
38. [ ] **Bullish Harami** : Une petite bougie haussière contenue dans une grande bougie baissière, signalant un renversement haussier.
39. [ ] **Bearish Harami** : Une petite bougie baissière contenue dans une grande bougie haussière, signalant un renversement baissier.
40. [ ] **Piercing Line** : Une bougie haussière qui clôture au-dessus du milieu de la précédente bougie baissière, signalant un renversement haussier.
41. [ ] **Dark Cloud Cover** : Une bougie baissière qui clôture au-dessous du milieu de la précédente bougie haussière, signalant un renversement baissier.
42. [ ] **Tweezer Top** : Deux bougies avec des sommets similaires, signalant un renversement baissier.
43. [ ] **Tweezer Bottom** : Deux bougies avec des creux similaires, signalant un renversement haussier.

### Autres Patterns
44. [ ] **Island Reversal** : Un gap dans les deux sens formant une île de prix isolée, signalant un renversement.
45. [ ] **Rising Three Methods** : Un pattern de continuation haussier avec trois petites bougies baissières au milieu de deux grandes bougies haussières.
46. [ ] **Falling Three Methods** : Un pattern de continuation baissier avec trois petites bougies haussières au milieu de deux grandes bougies baissières.
47. [ ] **Bullish Abandoned Baby** : Un gap baissier suivi d'une petite bougie Doji et d'un gap haussier, signalant un renversement haussier.
48. [ ] **Bearish Abandoned Baby** : Un gap haussier suivi d'une petite bougie Doji et d'un gap baissier, signalant un renversement baissier.
49. [ ] **Upside Gap Two Crows** : Un gap haussier suivi de deux petites bougies baissières, signalant un renversement baissier.
50. [ ] **Downside Gap Three Methods** : Un gap baissier suivi de trois petites bougies haussières, signalant une continuation baissière.
