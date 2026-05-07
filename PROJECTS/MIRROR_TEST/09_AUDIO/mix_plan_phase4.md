# Plan de mix audio - Phase 4

Ce document prépare le passage du son temporaire de l'animatic vers un mix plus organique.

## État actuel

L'animatic MP4 v01 contenait une piste audio synthétique générée directement dans FFmpeg :

- alarme courte ;
- vibration bruitée ;
- tonalités basses non musicales ;
- silence entre les événements.

Une v02 a maintenant été produite avec des assets audio séparés :

- `09_AUDIO/assets/selected/alarm_beep_single.wav`
- `09_AUDIO/assets/selected/phone_vibration_pulse.wav`
- `09_AUDIO/assets/selected/room_tone_bedroom.wav`
- `09_AUDIO/assets/selected/breathing_close_temp.wav`
- `09_AUDIO/assets/selected/low_tone_mirror.wav`

Export de revue :

`12_EXPORTS/MIRROR_TEST_animatic_lot01_audio_v02.mp4`

Une v03 a ensuite remplacé la respiration temporaire par une respiration plus organique et a adouci les niveaux :

- `09_AUDIO/assets/selected/breathing_organic_v01.wav`

Export de revue recommandé :

`12_EXPORTS/MIRROR_TEST_animatic_lot01_audio_v03.mp4`

Cette piste est la version recommandée pour revue de l'animatic lot 01.

## Objectif du mix final

Rendre le son plus physique et domestique tout en gardant la retenue :

- alarme sèche et irritante ;
- vibration réaliste du téléphone ;
- room tone nocturne ;
- respiration progressive ;
- basse presque imperceptible au miroir ;
- aucune musique mélodique.

## Timeline audio proposée

| Timecode | Plan | Élément sonore | Intention |
|----------|------|----------------|-----------|
| 00:00-00:05 | S01-P02 | Alarme + silence coupé | Agacement, routine |
| 00:05-00:12 | S02-P03 | Vibration + souffle froid | Intrusion |
| 00:12-00:22 | S04-P01 | Room tone grave + respiration lointaine | Doute |
| 00:22-00:34 | S04-P04 | Silence réduit + basse très faible | Révélation |
| 00:34-00:42 | S05-P02 | Tonalité basse + silence | Fin ouverte |

## Assets audio à produire ou trouver

- `alarm_3h17.wav`
- `phone_vibration.wav`
- `room_tone_bedroom.wav`
- `breathing_close.wav`
- `low_tone_mirror.wav`

## Niveaux recommandés

- Alarme : au premier plan, mais sans saturation.
- Vibration : plus courte et plus intrusive que l'alarme.
- Room tone : très bas.
- Respiration : audible seulement après le message.
- Basse miroir : ressentie plus qu'entendue.

## Critères de validation

- Le son ne doit pas expliquer la présence.
- Aucun jump scare.
- La dynamique doit laisser de vrais silences.
- Le mix doit rester intelligible sur petits haut-parleurs.
- La tension doit augmenter sans musique identifiable.

## Décision

Le mix v03 est intégré pour revue. Il remplace la respiration temporaire et garde les niveaux dans une zone plus retenue. La validation finale dépend maintenant d'une écoute humaine du MP4.
