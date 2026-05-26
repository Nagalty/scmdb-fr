# Traduction FR pour SCMDB – Star Citizen

Traduction française des données de Star Citizen pour SCMDB : missions, descriptions, lieux, objets, réputation et autres textes issus du jeu.

Ce projet communautaire vise à rendre le contenu de Star Citizen plus accessible aux joueurs francophones, notamment pour mieux comprendre les missions et les informations affichées sur SCMDB.
---
## 🚀 Utiliser la traduction

👉 Clique directement sur ce lien :

https://scmdb.net/?lang=https://raw.githubusercontent.com/Nagalty/scmdb-fr/main/lang-FR.json

L’interface de SCMDB reste en anglais, mais les données issues du jeu sont chargées en français quand elles sont disponibles.
---
## 🔧 Fonctionnement

Cette traduction est générée à partir du fichier `global.ini` français de Star Citizen, enrichi avec le travail communautaire utilisé également autour de SC Atlas.

Le fichier SCMDB est généré avec **SC Atlas Toolbox**, l’outil interne utilisé pour préparer, vérifier et exporter les données de traduction destinées à :

- SC Atlas
- la traduction ingame
- SCMDB

L’objectif est de garder une base cohérente entre le jeu, SC Atlas et SCMDB.
---
## 🛰️ Lien avec SC Atlas

SC Atlas est un projet communautaire indépendant autour de Star Citizen.

Il permet notamment de centraliser des outils et données utiles aux joueurs francophones, comme :

- la traduction française du jeu
- le suivi des plans possédés / manquants
- des guides communautaires
- des outils liés aux données locales de Star Citizen

La traduction SCMDB utilise la même base de travail que SC Atlas afin d’éviter d’avoir une traduction différente entre les outils.
---
## 📦 Version

Version actuelle : **Star Citizen 4.8.0 Live – 11875683**

Dernière mise à jour : **26 mai 2026**

Export SCMDB :

- clés SCMDB analysées : 2693
- clés traduites depuis le `global.ini` FR : 2496
- clés conservées en anglais faute de traduction disponible : 197
- variables dynamiques conservées
- balises SCMDB / Star Citizen conservées
- enrichissements `[PL]` inclus quand disponibles
---

## ⚠️ Limites connues

Certaines clés restent en anglais lorsque le texte correspondant n’existe pas dans le `global.ini` FR.

Cela peut concerner notamment :

- certaines missions récentes
- certaines descriptions longues
- certains lieux techniques ou internes
- certains textes encore absents de la traduction française officielle

Les variables dynamiques comme `[LOCATION]`, `[DESTINATION]`, `[TARGET]`, `[SHIP]`, ou `~mission(...)` sont volontairement conservées quand elles sont nécessaires au fonctionnement de SCMDB ou du jeu.

Certaines traductions peuvent aussi être approximatives, trop littérales ou manquer de cohérence de ton. Des corrections pourront être ajoutées au fil des retours.
---
## 🔄 Mise à jour

À chaque nouvelle version importante de Star Citizen :

1. récupération du nouveau `global.ini`
2. application des enrichissements communautaires
3. vérification avec SC Atlas Toolbox
4. génération du fichier langue SCMDB
5. remplacement du fichier `lang-FR.json`
6. mise à jour de ce README

👉 Le lien d’utilisation reste toujours le même.
---

## 🙏 Crédits

Cette traduction est basée sur le travail de **Le Cirque Lisoir** et de la communauté francophone Star Citizen.

Fichier source : `global.ini`

Adaptation, enrichissement, vérification et conversion SCMDB par **Nagalty**, via SC Atlas Toolbox.

Un grand merci à toutes les personnes qui contribuent à rendre Star Citizen plus accessible aux joueurs francophones.
---
## 💡 Objectif du projet

Permettre aux joueurs francophones de :

- mieux comprendre les missions
- lire plus facilement les descriptions et objectifs
- identifier les contenus liés aux plans potentiels `[PL]`
- profiter pleinement de l’expérience Star Citizen sans barrière de langue
- utiliser SCMDB avec des données plus lisibles en français
---
## 👤 À propos

Projet maintenu par **Nagalty**  
Créateur de contenu autour de Star Citizen et des jeux immersifs.

YouTube : https://www.youtube.com/@Nagalty-YT  
Twitch : https://www.twitch.tv/nagalty  
TikTok : https://www.tiktok.com/@nagalty

💬 Si tu utilises la traduction, n’hésite pas à faire un retour ou à proposer des améliorations.
