# Suivi des versions vendors - ElevenLabs / HeyGen / Grok

Ce fichier suit les assets produits hors pipeline local.

## Convention de nommage

### HeyGen

`HEYGEN_[SCENE]_[PLAN]_VIDEO_v[NUMERO].mp4`

Exemples :
- `HEYGEN_S04_P01_VIDEO_v01.mp4`
- `HEYGEN_S04_P04_VIDEO_v02.mp4`

### ElevenLabs

`ELEVEN_[MOTIF]_v[NUMERO].wav`

Exemples :
- `ELEVEN_alarm_3h17_v01.wav`
- `ELEVEN_breathing_close_v02.wav`

### Grok

`GROK_[TYPE]_[SUJET]_v[NUMERO].md`

Exemples :
- `GROK_prompt_review_s04_p04_v01.md`
- `GROK_audio_analysis_v01.md`

## Dossiers d'import

| Dossier | Usage |
|---------|-------|
| `08_GENERATIONS/assets/vendor_imports/heygen/` | Exports vidéo HeyGen bruts |
| `08_GENERATIONS/assets/vendor_imports/elevenlabs/` | Exports audio ElevenLabs bruts |
| `08_GENERATIONS/assets/vendor_imports/grok/` | Notes, analyses et prompts Grok |

## Tableau de suivi

| ID vendor | Outil | Plan / Motif | Prompt source | Fichier importé | Résultat | Décision | Notes |
|-----------|-------|--------------|---------------|-----------------|----------|----------|-------|
| HEYGEN_S04_P01_VIDEO_v01 | HeyGen | S04-P01 | `heygen_video_prompts.md` | À importer | À produire | En attente | Test prioritaire : anomalie subtile |
| HEYGEN_S04_P04_VIDEO_v01 | HeyGen | S04-P04 | `heygen_video_prompts.md` | À importer | À produire | En attente | Test prioritaire : révélation miroir |
| ELEVEN_alarm_3h17_v01 | ElevenLabs | Alarme | `elevenlabs_audio_prompts.md` | À importer | À produire | En attente | Son sec, irritant, court |
| ELEVEN_phone_vibration_v01 | ElevenLabs | Vibration | `elevenlabs_audio_prompts.md` | À importer | À produire | En attente | Pas de notification mélodique |
| ELEVEN_room_tone_bedroom_v01 | ElevenLabs | Room tone | `elevenlabs_audio_prompts.md` | À importer | À produire | En attente | Très discret |
| ELEVEN_breathing_close_v01 | ElevenLabs | Respiration | `elevenlabs_audio_prompts.md` | À importer | À produire | En attente | Organique, anxieuse, sans voix |
| ELEVEN_low_tone_mirror_v01 | ElevenLabs | Basse miroir | `elevenlabs_audio_prompts.md` | À importer | À produire | En attente | Non musical |
| GROK_prompt_review_s04_p01_v01 | Grok | S04-P01 | `grok_iteration_prompts.md` | À importer | À produire | En attente | Amélioration prompt HeyGen |
| GROK_prompt_review_s04_p04_v01 | Grok | S04-P04 | `grok_iteration_prompts.md` | À importer | À produire | En attente | Amélioration prompt HeyGen |

## Décisions possibles

- **Retenir** : asset utilisable en montage.
- **Retoucher** : asset prometteur mais nécessite une nouvelle version.
- **Rejeter** : asset incompatible avec le ton ou la continuité.
- **Archiver** : utile comme référence mais pas pour le montage.

