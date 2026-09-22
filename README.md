# Ma Collection - Benjamin

PWA statique pour gérer une collection de monnaies, pièces commémoratives, médailles et souvenirs.

## Publication GitHub Pages
1. Créer un dépôt GitHub, par exemple `ma-collection`.
2. Envoyer à la racine du dépôt : `index.html`, `manifest.webmanifest`, `sw.js` et le dossier `icons`.
3. Dans GitHub : Settings > Pages > Deploy from a branch > `main` > `/(root)`.
4. L'application sera disponible à une adresse du type : `https://UTILISATEUR.github.io/ma-collection/`.

## Installation iPhone
Ouvrir l'adresse dans Safari > Partager > Ajouter à l'écran d'accueil.

## Données
Les fiches et photos sont stockées localement dans IndexedDB sur l'appareil. GitHub n'héberge pas la collection.

## Sauvegarde
Réglages > Sauvegarde JSON. Le fichier JSON contient aussi les photos et permet une restauration complète.

## Mise à jour
Remplacer les fichiers du dépôt. Lors d'une future version, modifier le nom du cache dans `sw.js` (`ma-collection-v2`, etc.) pour forcer le renouvellement des fichiers hors ligne.
