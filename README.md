# 🎰 Galactic Casino

Petit casino en un seul fichier HTML, jouable dans le navigateur, avec des **crédits virtuels**. Aucun argent réel n'est en jeu.

## Jeux
- 🚀 **Crash** : encaisse avant le crash, la courbe et le multiplicateur sont synchronisés
- 💣 **Mines** : grille de 16 cases, de 1 à 10 mines
- 🛸 **Canyon** : pilote avec les flèches ← →
- 🪙 **Pile ou face** : cote x1.94
- 🎲 **Dés** : choisis ton seuil et ta cote

## Boutique
Thèmes, badges et Boost VIP (+5 % de gains), achetables avec tes gains.

## Admin
Une page admin protégée par un code permet d'ajuster le solde et la boutique. Le code est vérifié côté navigateur (hash SHA-256) : c'est pratique pour un jeu local, pas une vraie sécurité.

## Lancer le projet
Ouvre simplement `index.html` dans ton navigateur, ou active GitHub Pages sur la branche `main`.

## Données
Le solde et les achats sont sauvegardés dans le `localStorage` du navigateur.
