# MALYRN — Canal officiel de mises à jour

Ce dépôt public héberge le manifeste de versions utilisé par le client de mise à jour de MALYRN.

## Fichier lu par l’application

`latest.json` à la racine du dépôt.

URL brute :
https://raw.githubusercontent.com/samybecker73-ops/MALYRN-UPDATES/main/latest.json

## Publier une nouvelle version

1. Déployer d’abord les fichiers de l’application MALYRN sur son hébergement HTTPS.
2. Mettre à jour `version`, `published_at`, `summary`, `changes` et `release_notes_url` dans `latest.json`.
3. Ajouter les notes de version correspondantes dans `releases/`.
4. Conserver `product: "MALYRN"` et `channel: "stable"`.

Le dépôt annonce les versions : il ne stocke pas les fichiers PWA et ne remplace pas leur déploiement. L’application demande au navigateur de vérifier un nouveau Service Worker sur son propre domaine.

## Version actuellement publiée

Voir [les notes MALYRN v0.9.1](releases/v0.9.1.md).
