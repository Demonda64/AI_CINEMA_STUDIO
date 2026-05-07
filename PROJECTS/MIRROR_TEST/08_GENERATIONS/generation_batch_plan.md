# Plan de lot de génération - Phase 3

Ce document prépare le premier lot de génération d'images pour "Mirror". Il reprend les cinq plans prioritaires définis dans `generation_versions.md`.

## Objectif du lot 01

Créer les images clés minimales nécessaires pour tester la cohérence visuelle du film :

1. Le motif temporel : réveil `3:17`
2. L'intrusion : message texte
3. Le doute : première anomalie du reflet
4. Le climax : révélation du reflet
5. La fin ouverte : dernier reflet

## Dossiers de sortie

- `08_GENERATIONS/assets/images/drafts/` : générations brutes.
- `08_GENERATIONS/assets/images/selected/` : versions retenues.
- `08_GENERATIONS/assets/images/rejected/` : versions rejetées utiles à garder pour comparaison.
- `08_GENERATIONS/assets/video/drafts/` : essais vidéo courts.
- `08_GENERATIONS/assets/video/selected/` : versions vidéo retenues.

## Nommage

Utiliser la convention :

`MIRROR_[SCENE]_[PLAN]_[TYPE]_v[NUMERO].[extension]`

Exemples :
- `MIRROR_S01_P02_IMAGE_v01.png`
- `MIRROR_S04_P04_IMAGE_v03.png`
- `MIRROR_S04_P04_VIDEO_v01.mp4`

## Lot 01 - Images prioritaires

### MIRROR_S01_P02_IMAGE_v01

**Plan** : S01-P02  
**Objectif** : réveil `3:17`, motif temporel.

**Prompt** :
`extreme close-up of a small digital alarm clock displaying 3:17 in dim red digits, bedside table in darkness, blue gray nocturnal bedroom atmosphere, realistic dust and plastic texture, shallow depth of field, cinematic psychological horror, quiet tension, no visible monster`

**Contrôle qualité** :
- `3:17` lisible.
- Rouge discret, pas dominant.
- Pas de présence visible.

### MIRROR_S02_P03_IMAGE_v01

**Plan** : S02-P03  
**Objectif** : message texte, intrusion impossible.

**Prompt** :
`insert shot of a smartphone screen in a dark bedroom showing a text message from an unknown number: "Tu aurais dû le laisser branché.", cold phone screen glow, realistic hand holding the phone, blue gray shadows around, cinematic psychological horror, intimate intrusion, readable text`

**Contrôle qualité** :
- Message lisible et exact.
- Téléphone source lumineuse principale.
- Ambiance intime, pas spectaculaire.

### MIRROR_S04_P01_IMAGE_v01

**Plan** : S04-P01  
**Objectif** : première anomalie du reflet.

**Prompt** :
`medium shot of the same tired man standing in a dark bedroom facing a large wall mirror, his reflection appears almost normal but subtly delayed or slightly wrong in posture, ambiguous human presence in the reflection, blue gray desaturated low light, realistic domestic interior, restrained psychological horror, no monster, no gore, quiet dread`

**Contrôle qualité** :
- Anomalie subtile.
- Reflet encore presque contestable.
- Aucun monstre explicite.

### MIRROR_S04_P04_IMAGE_v01

**Plan** : S04-P04  
**Objectif** : révélation du reflet.

**Prompt** :
`close-up in a large mirror of an ambiguous human reflection that is not quite the same as the tired man, pale face, direct stare, slight impossible smile, blue gray desaturated low light, realistic domestic psychological horror, subtle abnormal reflection, no monster, no gore, no exaggerated distortion, quiet terrifying stillness`

**Contrôle qualité** :
- Regard direct.
- Sourire très léger, non caricatural.
- Horreur psychologique, pas effet gore.

### MIRROR_S05_P02_IMAGE_v01

**Plan** : S05-P02  
**Objectif** : dernier reflet, fin ouverte.

**Prompt** :
`final insert shot of a large wall mirror in a dark minimalist bedroom, faint ambiguous human presence still visible in the reflection, almost motionless, blue gray desaturated low light, realistic domestic psychological horror, quiet unresolved ending, no monster, no gore, subtle dread`

**Contrôle qualité** :
- Présence très subtile.
- Fin non explicative.
- Image calme et inquiétante.

## Prompt négatif global

Appliquer le prompt négatif de `08_GENERATIONS/negative_prompts.md` à chaque génération.

## Procédure d'évaluation

1. Sauvegarder chaque image brute dans `assets/images/drafts/`.
2. Renseigner `generation_versions.md`.
3. Évaluer chaque version dans `quality_notes.md`.
4. Déplacer ou copier les meilleures versions dans `assets/images/selected/`.
5. Mettre à jour `asset_inventory.md`.

