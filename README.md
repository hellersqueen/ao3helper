# AO3 Helper — distribution Tampermonkey

Ce dépôt public contient uniquement le fichier généré nécessaire au
fonctionnement d’AO3 Helper. Le code source et le processus de build sont
maintenus séparément.

## Installation

1. Installer [Tampermonkey](https://www.tampermonkey.net/) dans le navigateur.
2. Ouvrir
   [`ao3-helper.user.js`](https://raw.githubusercontent.com/hellersqueen/ao3helper/main/dist/ao3-helper.user.js).
3. Accepter l’installation proposée par Tampermonkey.

`ao3-helper.user.js` est **autonome** : tous les modules et le panneau de
configuration sont inclus dans ce seul fichier. Aucun téléchargement
supplémentaire n’est nécessaire au démarrage, et Tampermonkey le met à jour
automatiquement via son `@updateURL`.

## Licence

MIT
