# Instructions d'import vendors

## Où déposer les fichiers

### HeyGen

Déposer les vidéos dans :

`08_GENERATIONS/assets/vendor_imports/heygen/`

Noms attendus :
- `HEYGEN_S04_P01_VIDEO_v01.mp4`
- `HEYGEN_S04_P04_VIDEO_v01.mp4`

### ElevenLabs

Déposer les sons dans :

`08_GENERATIONS/assets/vendor_imports/elevenlabs/`

Noms attendus :
- `ELEVEN_alarm_3h17_v01.wav`
- `ELEVEN_phone_vibration_v01.wav`
- `ELEVEN_room_tone_bedroom_v01.wav`
- `ELEVEN_breathing_close_v01.wav`
- `ELEVEN_low_tone_mirror_v01.wav`

### Grok

Déposer les notes dans :

`08_GENERATIONS/assets/vendor_imports/grok/`

Noms recommandés :
- `GROK_prompt_review_s04_p01_v01.md`
- `GROK_prompt_review_s04_p04_v01.md`
- `GROK_video_analysis_s04_p01_v01.md`
- `GROK_video_analysis_s04_p04_v01.md`

## Après import

1. Mettre à jour `08_GENERATIONS/vendor_prompts/vendor_versions.md`.
2. Évaluer avec `08_GENERATIONS/vendor_prompts/vendor_review_checklist.md`.
3. Copier les assets retenus vers :
   - vidéos : `08_GENERATIONS/assets/video/selected/`
   - audio : `09_AUDIO/assets/selected/`
4. Mettre à jour `08_GENERATIONS/asset_inventory.md`.
5. Produire un nouvel export MP4 si nécessaire.

