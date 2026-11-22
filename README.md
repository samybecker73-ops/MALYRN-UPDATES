# MALYRN — Canal de transition vers KAVIO

Ce dépôt public est conservé comme **pont de migration** pour les installations MALYRN 0.9.1 qui consultent encore l’ancien manifeste GitHub.

À partir de MALYRN 0.9.2, l’application interroge directement le **KAVIO UPDATE SERVICE** :
https://kavio-update-service.samy-becker73.workers.dev/malyrn/latest.json

## Rôle de ce dépôt

- Annoncer la version de transition 0.9.2 aux anciennes installations.
- Conserver un historique public des notes publiées avant le transfert.
- Ne plus servir de source officielle pour les prochaines versions.

## Version de transition

Voir [les notes MALYRN v0.9.2](releases/v0.9.2.md).

Les prochaines publications sont gérées par le Worker KAVIO documenté dans le dépôt privé KAVIO, sous `workers/kavio-update-service/`.
