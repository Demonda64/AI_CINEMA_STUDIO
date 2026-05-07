# Suivi des versions de génération - Phase 3

Ce fichier servira à documenter les essais de génération, les choix retenus et les corrections nécessaires.

## Convention de nommage

Format recommandé :

`MIRROR_[SCENE]_[PLAN]_[TYPE]_v[NUMERO]`

Exemples :
- `MIRROR_S01_P02_IMAGE_v01`
- `MIRROR_S02_P03_IMAGE_v02`
- `MIRROR_S04_P04_VIDEO_v01`

## Tableau de suivi

| ID version | Plan | Type | Prompt source | Résultat | Problème | Décision | Notes |
|------------|------|------|---------------|----------|----------|----------|-------|
| MIRROR_S01_P02_IMAGE_v01 | S01-P02 | Image | `generation_prompts.md` | À générer | - | En attente | Vérifier lisibilité `3:17` |
| MIRROR_S02_P03_IMAGE_v01 | S02-P03 | Image | `generation_prompts.md` | À générer | - | En attente | Vérifier lisibilité du message |
| MIRROR_S04_P01_IMAGE_v01 | S04-P01 | Image | `generation_prompts.md` | À générer | - | En attente | Anomalie subtile uniquement |
| MIRROR_S04_P04_IMAGE_v01 | S04-P04 | Image | `generation_prompts.md` | À générer | - | En attente | Reflet humain, non monstrueux |
| MIRROR_S05_P02_IMAGE_v01 | S05-P02 | Image | `generation_prompts.md` | À générer | - | En attente | Fin ouverte |

## Plans prioritaires à générer

1. S01-P02 : réveil `3:17`
2. S02-P03 : message texte
3. S04-P01 : première anomalie du reflet
4. S04-P04 : révélation du reflet
5. S05-P02 : dernier reflet

## Grille d'évaluation

Chaque génération doit être évaluée sur 5 critères :

| Critère | Question | Score |
|---------|----------|-------|
| Cohérence personnage | Le même homme semble-t-il présent ? | /5 |
| Cohérence décor | La chambre et le miroir restent-ils constants ? | /5 |
| Lisibilité narrative | Le plan raconte-t-il clairement son objectif ? | /5 |
| Ton visuel | L'image reste-t-elle réaliste, froide et minimale ? | /5 |
| Subtilité horreur | L'anomalie reste-t-elle psychologique plutôt que spectaculaire ? | /5 |

## Décision

- **Retenir** : score total 20/25 ou plus, aucun critère essentiel raté.
- **Retoucher** : score total 15-19/25 ou problème corrigeable en post-production.
- **Rejeter** : score sous 15/25, incohérence majeure, ou violation des prompts négatifs.

