# 🎰 Galactic Casino

Petit casino en un seul fichier HTML, jouable dans le navigateur, avec des **crédits virtuels**. Aucun argent réel n'est en jeu.

## Jeux
- 🚀 **Crash** : encaisse avant le crash, la courbe et le multiplicateur sont synchronisés
- 💣 **Mines** : grille de 16 cases, de 1 à 10 mines
- 🛸 **Canyon** : rochers, comètes annoncées par une flèche rouge et murs à brèche ; tout accélère avec la cote
- 🪙 **Pile ou face** : cote x1.94
- 🎲 **Dés** : choisis ton seuil et ta cote
- 🔵 **Plinko** : une bille, 8 rangées de clous, trois niveaux de risque
- 🎡 **Roue** : 20 cases, trois niveaux de risque
- 🃏 **Hi-Lo** : plus haut ou plus bas, enchaîne et encaisse
- 🎰 **Machine à sous** : trois rouleaux, jusqu'à x400
- 🔢 **Keno** : 1 à 5 numéros, 8 tirés sur 20
- 🗼 **Tour** : huit étages, quatre niveaux de difficulté

Chaque nouveau jeu a un retour théorique d'environ 97 %, calculé à partir des vraies probabilités.

## Boutique
Thèmes, badges, vaisseaux pour Canyon et Boost VIP (+5 % de gains), achetables avec tes gains.

## Et aussi
- **Encaissement automatique** au Crash : choisis un multiplicateur et la manche encaisse toute seule
- **Bonus quotidien** de 100 crédits, toutes les 20 heures
- **Statistiques** : manches jouées, taux de victoire, meilleur gain, bilan net et 15 dernières manches
- **Sons** générés dans le navigateur (aucun fichier), désactivables depuis l'en-tête

## Admin
Une page admin protégée par un code permet d'ajuster le solde et la boutique. Le code est vérifié côté navigateur (hash SHA-256) : c'est pratique pour un jeu local, pas une vraie sécurité.

## Lancer le projet
Ouvre simplement `index.html` dans ton navigateur, ou active GitHub Pages sur la branche `main`.

## Données
Le solde et les achats sont sauvegardés dans le `localStorage` du navigateur.
