# Plan de génération vendors - Phase 4/5

Ce document organise la suite de production avec les outils externes choisis :

- ElevenLabs pour les sons, ambiances et voix éventuelles.
- HeyGen pour les générations vidéo et mouvements de personnage.
- Grok pour l'itération de prompts, l'analyse et les variantes.

## Décision pipeline

L'animatic local reste la référence de rythme et de continuité.

Les fichiers locaux servent à préparer :
- prompts image/vidéo ;
- prompts audio ;
- intentions de montage ;
- critères de validation.

Les rendus finals ou semi-finals seront produits avec ElevenLabs, HeyGen et Grok.

## Sources de référence

| Source | Usage |
|--------|-------|
| `12_EXPORTS/MIRROR_TEST_animatic_lot01_audio_v03.mp4` | Référence de rythme |
| `08_GENERATIONS/assets/images/selected/` | Références visuelles |
| `07_SHOTS/shot_list.md` | Découpage plan par plan |
| `10_EDITING/animatic_plan.md` | Durées et ordre |
| `09_AUDIO/mix_plan_phase4.md` | Structure sonore |
| `05_ENVIRONMENTS/reference_validation.md` | Contraintes visuelles et sonores |

## Répartition par outil

### ElevenLabs

Produire ou raffiner :
- alarme sèche ;
- vibration téléphone ;
- room tone nocturne ;
- respiration organique ;
- basse miroir non musicale ;
- silence texturé.

Sorties attendues :
- WAV ou MP3 séparés par motif sonore ;
- éventuellement un mix audio complet pour l'animatic.

### HeyGen

Produire :
- plans vidéo courts à partir des images retenues ;
- mouvements subtils du protagoniste ;
- approche miroir ;
- micro-expressions du reflet ;
- version vidéo des plans clés.

Sorties attendues :
- vidéos courtes par plan ;
- idéalement nommées selon la convention `MIRROR_[SCENE]_[PLAN]_VIDEO_vXX`.

### Grok

Utiliser pour :
- améliorer les prompts vidéo ;
- générer des variantes contrôlées ;
- analyser les incohérences visuelles ;
- proposer des versions alternatives sans casser la continuité.

Sorties attendues :
- prompts révisés ;
- notes de décision ;
- variantes de formulations.

## Ordre recommandé

1. Tester les prompts HeyGen sur 2 plans critiques :
   - S04-P01 : première anomalie.
   - S04-P04 : révélation.
2. Générer les sons ElevenLabs principaux :
   - alarme ;
   - vibration ;
   - respiration ;
   - room tone ;
   - low tone.
3. Utiliser Grok pour challenger les prompts vidéo si les sorties HeyGen sont trop explicites ou trop propres.
4. Mettre à jour `generation_versions.md` et `asset_inventory.md`.
5. Remonter les vidéos dans `08_GENERATIONS/assets/video/drafts/`.
6. Sélectionner les meilleures versions dans `08_GENERATIONS/assets/video/selected/`.

## Suivi opérationnel

- Versions vendors : `08_GENERATIONS/vendor_prompts/vendor_versions.md`
- Checklist de revue : `08_GENERATIONS/vendor_prompts/vendor_review_checklist.md`
- Packets prêts à copier : `08_GENERATIONS/vendor_prompts/submission_packets/`
- Imports HeyGen : `08_GENERATIONS/assets/vendor_imports/heygen/`
- Imports ElevenLabs : `08_GENERATIONS/assets/vendor_imports/elevenlabs/`
- Imports Grok : `08_GENERATIONS/assets/vendor_imports/grok/`

## Critères de validation vendor

- L'image reste réaliste, nocturne, bleu-gris et minimale.
- Le reflet reste humain, subtil, non monstrueux.
- Aucun jump scare sonore ou visuel.
- Les mouvements sont lents et contrôlés.
- Le son n'explique jamais l'entité.
- Les exports restent compatibles avec le montage final MP4.
