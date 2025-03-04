# Jeu de Combat contre des Monstres

## 📖 Description

Ce projet est un jeu de combat entre un chevalier et des monstres. Le joueur incarne un chevalier qui doit affronter deux groupes de monstres pour accumuler un maximum de points. Le combat repose sur un système de **Pierre-Feuille-Ciseaux**, où chaque attaque est déterminée par le choix des armes.

## 🎮 Fonctionnalités

- Mode de jeu avec **deux types de combats** :
  - Un premier groupe de monstres combattus **un par un**.
  - Un deuxième groupe de monstres attaquant **simultanément**.
- Système de combat basé sur **Pierre-Feuille-Ciseaux**.
- Différents niveaux de monstres avec des statistiques variées.
- Calcul dynamique des points en fonction des attaques et des monstres vaincus.
- Sauvegarde et rechargement automatique des scores des joueurs.
- Affichage des statistiques des joueurs, triées par pseudo ou par score.

## ⚔️ Règles du Combat

Chaque attaque suit ces règles :

- **Pierre** bat **Ciseaux**.
- **Feuille** bat **Pierre**.
- **Ciseaux** battent **Feuille**.
- Une arme spéciale **(#)** bat toutes les autres.
- Une arme inutile **(O)** perd contre toutes les autres.
- En cas d’égalité, personne ne perd de points.

Un monstre de niveau supérieur dispose de plus de points de vie et d’attaques plus puissantes.

## 🏆 Système de Score

- **+10 points** par attaque gagnée.
- **+50 x niveau du monstre** pour un monstre vaincu en combat 1v1.
- **+100 x niveau du monstre** pour un monstre vaincu en combat simultané.
- Score final enregistré automatiquement.

Développé par Ghassan Jabbour et Sami Halilou dans le cadre du projet **SAÉ S1.02 - Comparaison d’approches algorithmiques** à **Université Clermont Auvergne**.
