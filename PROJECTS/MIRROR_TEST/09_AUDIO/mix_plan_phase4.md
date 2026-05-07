# Plan de mix audio - Phase 4

Ce document prépare le passage du son temporaire de l'animatic vers un mix plus organique.

## État actuel

L'animatic MP4 contient une piste audio synthétique générée avec FFmpeg :

- alarme courte ;
- vibration bruitée ;
- tonalités basses non musicales ;
- silence entre les événements.

Cette piste valide le rythme sonore mais ne constitue pas encore un mix final.

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

Le mix final n'est pas encore validé. La prochaine passe doit remplacer les sons synthétiques par des sources plus naturelles ou des créations audio dédiées.

