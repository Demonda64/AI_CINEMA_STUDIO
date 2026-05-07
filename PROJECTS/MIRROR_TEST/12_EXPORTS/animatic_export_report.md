# Rapport d'export animatic - Phase 4

## Exports disponibles

Un animatic HTML autonome a été créé :

`10_EDITING/animatic_lot01.html`

Un animatic MP4 a également été produit :

`12_EXPORTS/MIRROR_TEST_animatic_lot01.mp4`

Une v02 avec assets audio séparés a été produite :

`12_EXPORTS/MIRROR_TEST_animatic_lot01_audio_v02.mp4`

Une v03 avec respiration organique et niveaux affinés a été produite :

`12_EXPORTS/MIRROR_TEST_animatic_lot01_audio_v03.mp4`

Une copie de travail est conservée dans :

`08_GENERATIONS/assets/video/selected/MIRROR_LOT01_ANIMATIC_v01.mp4`

Ces exports utilisent les images sélectionnées en Phase 3 et reproduisent le rythme prévu dans `10_EDITING/animatic_plan.md`.

## Format

- Type HTML : HTML autonome
- Type vidéo : MP4
- Durée : 42 secondes
- Ratio MP4 : 1920x1080
- Framerate MP4 : 24 fps
- Vidéo : H.264
- Audio : AAC
- Audio HTML : sons synthétiques générés dans le navigateur
- Audio MP4 : sons synthétiques rendus avec FFmpeg
- Audio MP4 v02 : assets WAV séparés mixés avec FFmpeg
- Audio MP4 v03 : respiration organique et niveaux affinés

## Note d'environnement

L'environnement vidéo a été complété après la première version HTML : FFmpeg, Python, Node, HyperFrames CLI et Chrome Headless sont maintenant installés.

L'animatic HTML reste utile pour une validation interactive. Le MP4 sert de fichier de revue/export. Il permet de valider :
- l'ordre des plans ;
- les durées ;
- la lisibilité du message et du réveil ;
- la progression du miroir ;
- l'intention sonore minimale.

## Assets utilisés

| Ordre | Plan | Asset |
|-------|------|-------|
| 1 | S01-P02 | `08_GENERATIONS/assets/images/selected/MIRROR_S01_P02_IMAGE_v01.png` |
| 2 | S02-P03 | `08_GENERATIONS/assets/images/selected/MIRROR_S02_P03_IMAGE_v01.png` |
| 3 | S04-P01 | `08_GENERATIONS/assets/images/selected/MIRROR_S04_P01_IMAGE_v02.png` |
| 4 | S04-P04 | `08_GENERATIONS/assets/images/selected/MIRROR_S04_P04_IMAGE_v01.png` |
| 5 | S05-P02 | `08_GENERATIONS/assets/images/selected/MIRROR_S05_P02_IMAGE_v01.png` |

## Vérification technique

- Durée : 42.000 secondes
- Résolution : 1920x1080
- Framerate : 24 fps
- Codec vidéo : H.264
- Codec audio : AAC

## Vérification technique v02

- Durée : 42.000 secondes
- Résolution : 1920x1080
- Framerate : 24 fps
- Codec vidéo : H.264
- Codec audio : AAC

## Vérification technique v03

- Durée : 42.000 secondes
- Résolution : 1920x1080
- Framerate : 24 fps
- Codec vidéo : H.264
- Codec audio : AAC

## Prochaine étape

Valider le rythme et le mix de `MIRROR_TEST_animatic_lot01_audio_v03.mp4`, puis décider :

1. soit générer les plans complémentaires avant le montage final ;
2. soit passer au mix audio et au rapport de continuité final.
