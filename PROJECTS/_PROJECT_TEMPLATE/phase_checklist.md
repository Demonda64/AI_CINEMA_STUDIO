# Phase Checklist

Ce document fournit une checklist complète pour valider chaque phase du workflow.
Utilisez-le en parallèle avec `HOME/agents_workflow.md` pour suivre l'avancement du projet.

## Phase 0 : Préparation du projet

**Agents impliqués** : DirectorAgent, PromptAgent, ArchiveAgent

**Livrables attendus** :
- [ ] Brief de projet complet (`01_DEVELOPMENT/brief.md`)
- [ ] Vue d'ensemble du projet (`01_DEVELOPMENT/project_overview.md`)
- [ ] Concept clé documenté (`01_DEVELOPMENT/concept.md`)
- [ ] Thèmes et messages principaux (`01_DEVELOPMENT/themes.md`)
- [ ] Dossier projet créé avec structure complète
- [ ] Archive initiale enregistrée (`13_ARCHIVE/`)

**Points de validation** :
- [ ] Le brief répond à tous les champs du template.
- [ ] La vision créative est claire et partagée.
- [ ] Les références visuelles et sonores sont listées.
- [ ] Le format de livraison est défini.
- [ ] Les délais et contraintes sont documentés.

**Prochaine étape** : Passage à Phase 1 lorsque tous les éléments sont validés.

---

## Phase 1 : Histoire et émotion

**Agents impliqués** : StoryAgent, EmotionAgent, DirectorAgent, ContinuityAgent

**Livrables attendus** :
- [ ] Structure narrative complète (`02_PREPRODUCTION/scene_list.md`)
- [ ] Synopsis détaillé (`02_PREPRODUCTION/synopsis.md`)
- [ ] Carte émotionnelle par scène (`01_DEVELOPMENT/emotion_map.md`)
- [ ] Fiches de personnages principaux
- [ ] Arcs émotionnels validés
- [ ] Rapport initial de continuité

**Points de validation** :
- [ ] Chaque scène a un objectif clair.
- [ ] L'arc émotionnel progresse logiquement.
- [ ] Les personnages ont des motivations définies.
- [ ] Les conflits centraux sont identifiés.
- [ ] Pas d'incohérence majeure détectée.

**Prochaine étape** : Passage à Phase 2 lorsque l'histoire est validée.

---

## Phase 2 : Identité visuelle et son

**Agents impliqués** : CameraAgent, DPAgent, LightingAgent, SoundAgent

**Livrables attendus** :
- [ ] Plan de caméra par scène (`06_STORYBOARD/storyboard_plan.md`)
- [ ] Liste de plans (`07_SHOTS/shot_list.md`)
- [ ] Palette couleur documentée (`LIGHTING_SYSTEM/color_palette.md` ou `03_WORLD_BUILDING/`)
- [ ] Fiches d'éclairage par scène
- [ ] Brief sonore et motifs musicaux (`09_AUDIO/README.md`)
- [ ] Références visuelles et sonores validées

**Points de validation** :
- [ ] Le style visuel est cohérent avec le brief.
- [ ] Les plans soutiennent l'émotion narrative.
- [ ] La palette couleur respecte la vision créative.
- [ ] Le design sonore complète l'ambiance visuelle.
- [ ] Continuité visuelle entre les scènes confirmée.

**Prochaine étape** : Passage à Phase 3 lorsque l'identité visuelle et sonore est validée.

---

## Phase 3 : Prompts et génération IA

**Agents impliqués** : PromptAgent, GenerationAgent, ArchiveAgent

**Livrables attendus** :
- [ ] Prompts de génération par scène (`08_GENERATIONS/generation_prompts.md`)
- [ ] Prompts négatifs définis et testés
- [ ] Versions de génération documentées (`08_GENERATIONS/generation_versions.md`)
- [ ] Notes de qualité pour chaque version
- [ ] Meilleure version sélectionnée par scène
- [ ] Inventaire des assets produits

**Points de validation** :
- [ ] Les prompts couvrent tous les éléments visuels clés.
- [ ] Chaque version est documentée avec date et observations.
- [ ] La cohérence visuelle entre les scènes est vérifiée.
- [ ] Les assets sélectionnés correspondent au brief.
- [ ] Les itérations sont tracées et justifiées.

**Prochaine étape** : Passage à Phase 4 lorsque tous les assets IA sont validés.

---

## Phase 4 : Montage, continuité, post-production

**Agents impliqués** : EditingAgent, ContinuityAgent, SoundAgent, ArchiveAgent

**Livrables attendus** :
- [ ] Script de montage et rythme (`10_EDITING/edit_notes.md`)
- [ ] Notes de coupes et transitions
- [ ] Stabilisation et correction d'image (`11_POST/post_production_notes.md`)
- [ ] Mix audio finalisé
- [ ] Rapport de continuité final
- [ ] Export master complété (`12_EXPORTS/export_report.md`)
- [ ] Archive finale complètement documentée

**Points de validation** :
- [ ] Le montage suit la progression émotionnelle définie.
- [ ] Les transitions sont motivées et fluides.
- [ ] La continuité image/son/histoire est validée.
- [ ] Les exports respectent les specs définies.
- [ ] La documentation est complète pour archivage.

**Prochaine étape** : Archivage et postmortem.

---

## Archivage et Postmortem

**Livrables attendus** :
- [ ] Bilan du projet documenté (`13_ARCHIVE/postmortem.md`)
- [ ] Tous les fichiers de travail archivés
- [ ] Versions majeures conservées
- [ ] Notes de décisions et leçons apprises
- [ ] Recommandations pour projets futurs

**Points de validation** :
- [ ] Les décisions créatives majeures sont documentées.
- [ ] Les problèmes rencontrés et solutions sont notés.
- [ ] Les leçons apprises sont claires.
- [ ] Les recommandations sont utiles pour la suite.
- [ ] L'archive est organisée et facile à retrouver.

---

## Utilisation

1. **Copier ce fichier** dans votre projet : `PROJECTS/<VotreProjet>/phase_checklist.md`
2. **Cocher les éléments** au fur et à mesure de votre progression.
3. **Valider chaque phase** avant de passer à la suivante.
4. **Archiver la checklist complétée** dans `13_ARCHIVE/` à la fin du projet.

## Liens utiles

- [Brief Template](brief_template.md)
- [Quick Start Guide](quick_start.md)
- [Agents Workflow](../HOME/agents_workflow.md)
- [Example Project](../EXAMPLE_PROJECT/README.md)
