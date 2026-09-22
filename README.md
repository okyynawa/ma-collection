# Ma Collection - Benjamin — v1.1

PWA statique pour gérer une collection de monnaies, pièces commémoratives, médailles, souvenirs et coffrets.

## Nouveautés v1.1
- Échelle d'état : Circulée, TB, TTB, SUP, UNC/FDC, BE/Proof avec explication.
- Type `Coffret`.
- Nombre de pièces et référence du coffret.
- Une pièce peut être rattachée à un coffret.
- Depuis la fiche d'un coffret, bouton pour ajouter directement une pièce dedans.
- Statistiques séparées pour les fiches, pièces et coffrets.

## Mise à jour GitHub Pages
Remplacer `index.html`, `sw.js`, `manifest.webmanifest`, le dossier `icons` et éventuellement ce README à la racine du dépôt. Les données déjà présentes sur l'iPhone restent dans IndexedDB.

## Données
Les fiches et photos sont stockées localement dans IndexedDB sur l'appareil. GitHub n'héberge pas la collection.

## Sauvegarde
Réglages > Sauvegarde JSON. Le fichier JSON contient aussi les photos et les liens entre coffrets et pièces.
