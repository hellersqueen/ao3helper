# AO3 Helper — distribution Tampermonkey

Ce dépôt public contient uniquement les fichiers générés nécessaires au
fonctionnement d’AO3 Helper. Le code source et le processus de build sont
maintenus séparément.

## Installation

1. Installer [Tampermonkey](https://www.tampermonkey.net/) dans le navigateur.
2. Ouvrir
   [`ao3-helper.user.js`](https://raw.githubusercontent.com/hellersqueen/ao3helper/main/dist/ao3-helper.user.js).
3. Accepter l’installation proposée par Tampermonkey.

Le bootstrap `ao3-helper.user.js` télécharge à la demande les deux bundles
voisins :

- `ao3-helper.modules.js` pour les fonctionnalités AO3 ;
- `ao3-helper.panel.js` pour le panneau de configuration.

Les trois fichiers doivent toujours être publiés ensemble.

## Licence

MIT
