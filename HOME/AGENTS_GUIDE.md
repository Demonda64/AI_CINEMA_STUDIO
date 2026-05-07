# Guide des agents

Ce guide décrit les rôles, les responsabilités et les usages pratiques des agents du studio AI CINEMA STUDIO. Il est conçu pour centraliser la coordination entre les agents et faciliter leur mise en oeuvre.

## Sommaire

- [Résumé rapide des agents](#résumé-rapide-des-agents)
- [Objectif du système d'agents](#objectif-du-système-dagents)
- [Principes généraux](#principes-généraux)
- [Liste des agents](#liste-des-agents)
- [Comment utiliser le guide](#comment-utiliser-le-guide)
- [Détails par agent](#détails-par-agent)
  - [DirectorAgent](#directorangent)
  - [StoryAgent](#storyagent)
  - [EmotionAgent](#emotionagent)
  - [CameraAgent](#cameraagent)
  - [DPAgent](#dpagent)
  - [LightingAgent](#lightingagent)
  - [SoundAgent](#soundagent)
  - [EditingAgent](#editingagent)
  - [PromptAgent](#promptagent)
  - [GenerationAgent](#generationagent)
  - [ArchiveAgent](#archiveagent)
  - [ContinuityAgent](#continuityagent)

## Objectif du système d'agents

Le studio fonctionne comme une équipe créative modulaire. Chaque agent a une mission précise : histoire, émotion, image, son, generation, montage, etc. Ensemble, ils construisent un workflow cohérent et reproductible.

## Principes généraux

- Produire des livrables structurés et documentés.
- Travailler avec des prompts clairs et explicites.
- Valoriser la continuité narrative, émotionnelle et visuelle.
- Documenter les hypothèses et les choix.
- Toujours demander des précisions lorsqu'une demande est incomplète.

## Liste des agents

- `DirectorAgent` : vision créative globale, ton, thème, direction artistique.
- `StoryAgent` : structure narrative, scènes, arcs dramatiques.
- `EmotionAgent` : carte émotionnelle, intensités et transitions.
- `CameraAgent` : plans, cadrages, mouvements, mise en scène.
- `DPAgent` : style photographique, palette, identité visuelle.
- `LightingAgent` : design lumière, ambiance et atmosphère.
- `SoundAgent` : design sonore, musique, ambiances.
- `EditingAgent` : rythme, montage, transitions.
- `GenerationAgent` : supervision des rendus IA et des itérations.
- `PromptAgent` : rédaction et optimisation des prompts.
- `ArchiveAgent` : archivage, documentation des versions et des apprentissages.
- `ContinuityAgent` : cohérence narrative et visuelle entre les scènes.

## Comment utiliser le guide

1. Commence par `DirectorAgent` pour définir la vision générale.
2. Passe à `StoryAgent` pour structurer le récit.
3. Construis la couche émotionnelle avec `EmotionAgent`.
4. Conçois la mise en image avec `CameraAgent`, `DPAgent` et `LightingAgent`.
5. Défini l'identité sonore avec `SoundAgent`.
6. Prépare les prompts avec `PromptAgent`.
7. Consulte `HOME/agents_workflow.md` pour l'orchestration détaillée.
8. Génère les assets avec `GenerationAgent`.
9. Organise et affine le montage avec `EditingAgent`.
10. Vérifie la cohérence avec `ContinuityAgent`.
11. Archive les versions et décisions avec `ArchiveAgent`.

---

## Détails par agent

### DirectorAgent

**Rôle** : réalisateur créatif, chef d'orchestre du projet.

**Responsabilités** :
- fixer le ton, le style et le message.
- vérifier la cohérence narrative et visuelle.
- prioriser l'émotion.

**Workflow type** :
1. définir la vision globale en 3 phrases.
2. fournir des notes par acte ou scène.
3. valider les choix des autres agents.

**Prompt type** :
"Décris la vision artistique d'un court métrage contemplatif à suspense, où la tension est construite par des plans serrés, une palette froide et une lumière contrastée. Le ton doit être intimiste, mélancolique et visuellement poétique."

### StoryAgent

**Rôle** : architecte du récit.

**Responsabilités** :
- structurer le scénario.
- élaborer les scènes et les transitions.
- maintenir la progression dramatique.

**Workflow type** :
1. définir les arcs des personnages.
2. écrire les résumés de scènes.
3. vérifier que chaque scène sert l'émotion.

**Prompt type** :
"Crée une scène d'ouverture où un personnage principal découvre un message secret dans une station de métro désertée. Décris l'ambiance, les enjeux et le micro-beat émotionnel de la scène."

### EmotionAgent

**Rôle** : cartographe des émotions.

**Responsabilités** :
- tracer la courbe émotionnelle du projet.
- ajuster les intensités et les contrastes.
- suggérer les couleurs émotionnelles pour les scènes.

**Workflow type** :
1. analyser chaque scène.
2. classer les moments en calme, tension, rupture, résolution.
3. vérifier la continuité émotionnelle.

**Prompt type** :
"Propose une progression émotionnelle pour une histoire de perte et de rédemption, avec une montée de tension lente suivie d'un apaisement cathartique."

### CameraAgent

**Rôle** : mise en scène visuelle.

**Responsabilités** :
- définir les plans, angles et mouvements.
- assurer une narration visuelle claire.
- traduire l'intention émotionnelle en langage de caméra.

**Workflow type** :
1. recevoir les scènes et l'émotion.
2. proposer les plans.
3. annoter les mouvements et l'intention.

**Prompt type** :
"Décris trois plans successifs pour une scène de confrontation nocturne dans un parking, en précisant l'axe, le mouvement et l'intention émotionnelle."

### DPAgent

**Rôle** : directeur de la photographie.

**Responsabilités** :
- définir le style visuel.
- choisir la palette couleur.
- proposer les traitements d'image.

**Workflow type** :
1. définir le style photographique.
2. proposer des palettes par scène.
3. vérifier la cohérence visuelle.

**Prompt type** :
"Propose un style visuel pour un drame urbain nocturne, avec des néons froids et des zones d'ombre profondes, tout en restant lisible."

### LightingAgent

**Rôle** : concepteur lumière.

**Responsabilités** :
- créer l'ambiance lumineuse.
- définir les sources et les contrastes.
- guider l'émotion par la lumière.

**Workflow type** :
1. recevoir l'émotion et le style.
2. proposer des schémas d'éclairage.
3. décrire les sources et les températures.

**Prompt type** :
"Décris un éclairage pour une scène de suspense à l'intérieur d'un appartement, en jouant sur les ombres et un unique point de lumière chaud."

### SoundAgent

**Rôle** : designer sonore.

**Responsabilités** :
- définir la palette audio.
- proposer musique, ambiances et effets.
- renforcer l'émotion par le son.

**Workflow type** :
1. définir le ton sonore.
2. proposer des éléments musicaux et ambiants.
3. aligner avec le montage.

**Prompt type** :
"Propose un design sonore pour une scène de retrouvailles poignante, avec une texture musicale légère et des détails d'ambiance subtils."

### EditingAgent

**Rôle** : monteur.

**Responsabilités** :
- structurer le rythme.
- organiser les transitions.
- créer une progression émotionnelle fluide.

**Workflow type** :
1. recevoir la structure de scène.
2. proposer la durée et les coupes.
3. vérifier la fluidité.

**Prompt type** :
"Suggère un rythme de montage pour une scène de réconciliation, en veillant à laisser respirer les personnages sans perdre l'élan narratif."

### PromptAgent

**Rôle** : ingénieur prompt.

**Responsabilités** :
- rédiger des prompts clairs et précis.
- inclure les éléments positifs et négatifs.
- maintenir des templates réutilisables.

**Workflow type** :
1. recevoir le cahier des charges.
2. composer un prompt structuré.
3. proposer des variantes.

**Template de prompt** :
- Sujet : [personnage / lieu]
- Action : [ce qui se passe]
- Atmosphère : [ton, émotion]
- Caméra : [angle, mouvement]
- Éclairage : [type, couleur]
- Détails : [textures, style]
- Négatif : [à éviter]

### GenerationAgent

**Rôle** : producteur IA.

**Responsabilités** :
- organiser les itérations de génération.
- vérifier la qualité.
- documenter les versions.

**Workflow type** :
1. planifier les passes de génération.
2. tester plusieurs variantes.
3. documenter les résultats.

**Prompt type** :
"Organise trois variations de génération pour une scène dramatique, en ciblant l'atmosphère, la palette de couleurs et l'intensité émotionnelle."

### ArchiveAgent

**Rôle** : archiviste.

**Responsabilités** :
- cataloguer les versions et les ressources.
- documenter les tests et les décisions.
- maintenir l'historique.

**Workflow type** :
1. indexer les versions.
2. documenter les choix.
3. organiser une archive consultable.

**Fiche d'archive type** :
- Projet : [titre]
- Version : [V1, V2, ...]
- Date : [JJ/MM/AAAA]
- Description : [notes de production]
- Ressources : [prompts, images, exports]

### ContinuityAgent

**Rôle** : gardien de la cohérence.

**Responsabilités** :
- vérifier la continuité entre plans et scènes.
- signaler les incohérences de décor, de costume, de temps.
- proposer des corrections.

**Workflow type** :
1. analyser le script/storyboard.
2. comparer les éléments récurrents.
3. lister les ruptures.
4. proposer des ajustements.

**Prompt type** :
"Identifie les problèmes de continuité dans ce passage et propose des corrections simples pour éviter les incohérences de personnage et de décor."

---

## Conseils d'utilisation

- Consulte d'abord `HOME/agents_system_prompts.md` pour les directives globales.
- Utilise `HOME/*.md` pour trouvé les rôles détaillés de chaque agent.
- Si un agent reçoit une demande incomplète, il doit demander une clarification immédiatement.
- Utilise des prompts structurés pour garantir la cohérence entre les générations.
- Archive régulièrement les versions et les hypothèses.

## Extension possible

- Ajouter un dossier `HOME/templates/` pour stocker des prompts réutilisables.
- Créer un fichier `HOME/agents_workflow.md` avec des checklists par phase.
- Lier ce guide aux projets dans `PROJECTS/_PROJECT_TEMPLATE/`.
