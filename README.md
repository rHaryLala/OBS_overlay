# OBS Overlay

Collection de pages HTML pour les overlays, docks et outils de régie utilisés avec OBS Studio.

## Utilisation

1. Téléchargez ou clonez le dépôt en conservant l’arborescence des fichiers.
2. Dans OBS, ajoutez une **Source navigateur** et sélectionnez le fichier HTML de l’overlay souhaité. Réglez la largeur et la hauteur selon votre scène (souvent 1920 × 1080).
3. Ouvrez la page `*-dock.html` correspondante dans un navigateur ou ajoutez-la comme dock navigateur personnalisé dans OBS.
4. Gardez le dock et l’overlay associés dans le même dossier afin qu’ils puissent échanger leur état.

Les pages autonomes, comme `clock.html`, `countdown-graduation.html`, `intermission.html` et `multiview.html`, peuvent être ouvertes directement dans une source navigateur ou un navigateur web.

## Pages principales

| Fonction | Overlay / page | Dock |
| --- | --- | --- |
| Bible | `bible-overlay.html` | `bible-dock.html` |
| Facebook | `facebook-overlay.html` | `facebook-dock.html` |
| Paroles | `lyrics-overlay.html` | `lyrics-dock.html` |
| Timer | `timer-overlay.html` | `timer-dock.html` |
| Début de live | `debut-live.html` | `debut-live-dock.html` |
| Annonceur | `graduate-announcer.html` | `graduate-announcer-dock.html` |
| Bandeau intervenant | `lower-third-speaker.html` | `lower-third-speaker-dock.html` |
| Projection live | `projection-live.html` | `projection-live-dock.html` |
| UAZ Live | `uaz-live.html` | `uaz-live-dock.html` |

Le dépôt contient aussi des pages de régie ou d’information, notamment `dock.html`, `overlay-dock.html`, `GUIDE DRONE OBS.html` et les pages du dossier `Livret SPARK 2026`.

## Ressources complémentaires

Ce dépôt contient les pages HTML et `dock-ui.css`, mais pas toutes les ressources que certaines pages référencent. Selon la page utilisée, il peut être nécessaire d’ajouter les fichiers de données Bible (`bibles/*.js`), `hymns.json`, `overlay-stack.js`, `roster-2026.js` ou des images/logos, en conservant les chemins relatifs attendus par le code.

Certaines fonctions, comme les intégrations Facebook ou les paroles en ligne, nécessitent également leurs services ou paramètres propres. Aucun secret ni jeton d’accès n’est fourni dans ce dépôt.
