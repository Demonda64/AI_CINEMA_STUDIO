# Agents Workflow

Ce document définit le workflow fonctionnel pour piloter les agents du studio AI CINEMA STUDIO.
Il organise les phases, les livrables et les échanges entre agents.

## Objectif

Rendre le système d'agents utilisable en définissant :
- l'ordre d'intervention
- les artefacts produits
- les formats attendus
- les points de validation

## Phases principales

### Phase 0 : préparation du projet

Agents impliqués : `DirectorAgent`, `PromptAgent`, `ArchiveAgent`

Livrables :
- brief de projet clair et complet
- vision globale du film
- cadre de styles et de thèmes
- structure de dossier initiale

Étapes :
1. Rassembler le concept, le genre, le format et la durée cible.
2. Définir le ton artistique, la palette émotionnelle, les références visuelles.
3. Documenter la stratégie de production dans `PROJECTS/<projet>/project_overview.md`.
4. Formaliser le brief de projet avec `PROJECTS/_PROJECT_TEMPLATE/brief_template.md` et/ou `PROJECTS/<projet>/01_DEVELOPMENT/brief.md`.
5. Archiver le brief initial.

> Conseil : utilisez `PROJECTS/EXAMPLE_PROJECT/01_DEVELOPMENT/brief.md` comme cas d'exemple concret.
> Pour un démarrage rapide, suivez aussi `PROJECTS/_PROJECT_TEMPLATE/quick_start.md`.

### Phase 1 : histoire et émotion

Agents impliqués : `StoryAgent`, `EmotionAgent`, `DirectorAgent`, `ContinuityAgent`

Livrables :
- structure narrative par actes et scènes
- fiches de scènes et objectifs
- carte émotionnelle par acte
- premier rapport de continuité

Étapes :
1. `DirectorAgent` confirme la vision et les messages clés.
2. `StoryAgent` rédige la structure des scènes et les arcs principaux.
3. `EmotionAgent` trace la progression émotionnelle.
4. `ContinuityAgent` vérifie les incohérences initiales.

### Phase 2 : identité visuelle et son

Agents impliqués : `CameraAgent`, `DPAgent`, `LightingAgent`, `SoundAgent`

Livrables :
- plan de caméra par scène
- style visuel et palette couleur
- fiches d'éclairage
- brief sonore et motifs musicaux

Étapes :
1. `CameraAgent` propose les cadrages et plans clés.
2. `DPAgent` définit la photographie, la couleur et le traitement d'image.
3. `LightingAgent` crée les ambiances lumieuses.
4. `SoundAgent` structure le design sonore et les textures.
5. Vérifier la cohérence visuelle et émotionnelle entre les agents.

### Phase 3 : prompts et génération

Agents impliqués : `PromptAgent`, `GenerationAgent`, `ArchiveAgent`

Livrables :
- prompts de génération structurés
- prompts négatifs
- versions de génération et notes de qualité
- inventaire des assets produits

Étapes :
1. `PromptAgent` prépare les prompts pour chaque scène et chaque phase de génération.
2. `GenerationAgent` lance les passes IA et documente les résultats.
3. `ArchiveAgent` enregistre les meilleures versions et les tests infra.
4. Itérer jusqu'à atteindre la cohérence souhaitée.

### Phase 4 : montage, continuité, post-production

Agents impliqués : `EditingAgent`, `ContinuityAgent`, `SoundAgent`, `ArchiveAgent`

Livrables :
- script de montage et rythme
- notes de coupes et transitions
- rapport de continuité final
- asset list et archives finales

Étapes :
1. `EditingAgent` organise le montage temporel et le tempo.
2. `ContinuityAgent` valide la cohérence image/histoire.
3. `SoundAgent` affine les textures sonores pour le montage.
4. `ArchiveAgent` prépare le dossier final du projet.

## Format de livraison recommandé

Pour chaque agent, utiliser un fichier Markdown clair :
- `HOME/<AgentName>.md` pour la définition du rôle.
- `PROJECTS/<projet>/<phase>/<element>.md` pour les livrables.
- `HOME/agents_system_prompts.md` pour les prompts maîtres.
- `HOME/agents_workflow.md` pour le workflow.

### Exemple de noms de fichiers

- `PROJECTS/MonProjet/01_DEVELOPMENT/project_overview.md`
- `PROJECTS/MonProjet/02_PREPRODUCTION/scene_list.md`
- `PROJECTS/MonProjet/02_PREPRODUCTION/emotion_map.md`
- `PROJECTS/MonProjet/06_STORYBOARD/storyboard_plan.md`
- `PROJECTS/MonProjet/07_SHOTS/shot_list.md`
- `PROJECTS/MonProjet/08_GENERATIONS/generation_prompts.md`
- `PROJECTS/MonProjet/08_GENERATIONS/generation_versions.md`
- `PROJECTS/MonProjet/11_POST/post_production_notes.md`
- `PROJECTS/MonProjet/12_EXPORTS/export_report.md`
- `PROJECTS/MonProjet/13_ARCHIVE/postmortem.md`

## Orchestration recommandée

1. `DirectorAgent` confirme la vision créative.
2. `StoryAgent` structure le récit.
3. `EmotionAgent` valide l'arc émotionnel.
4. `CameraAgent` / `DPAgent` / `LightingAgent` construisent l'image.
5. `SoundAgent` prépare l'univers audio.
6. `PromptAgent` génère les instructions de production.
7. `GenerationAgent` produit les assets IA.
8. `EditingAgent` module le rythme.
9. `ContinuityAgent` vérifie les incohérences.
10. `ArchiveAgent` archive les résultats.

## Checklists par phase

### Phase 0 checklist
- [ ] Brief complet formalisé
- [ ] Vision globale écrite
- [ ] Styleboard / références listées
- [ ] Dossier projet créé
- [ ] Archive initiale enregistrée

### Phase 1 checklist
- [ ] Structure des scènes validée
- [ ] Arcs émotionnels définis
- [ ] Fiches de scènes rédigées
- [ ] Première validation de continuité

### Phase 2 checklist
- [ ] Plans de caméra établis
- [ ] Palette visuelle définie
- [ ] Schémas d'éclairage rédigés
- [ ] Brief sonore structuré

### Phase 3 checklist
- [ ] Prompts de génération préparés
- [ ] Prompts négatifs définis
- [ ] Itérations documentées
- [ ] Assets sélectionnés et archivés

### Phase 4 checklist
- [ ] Structure de montage définie
- [ ] Transitions et rythme validés
- [ ] Continuité finale vérifiée
- [ ] Archive finale complétée
