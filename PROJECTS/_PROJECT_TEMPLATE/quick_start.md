# Quick Start Projet

Ce guide rapide explique comment démarrer un nouveau projet dans AI CINEMA STUDIO.

## 1. Créer la structure de projet

- Copier `PROJECTS/_PROJECT_TEMPLATE/` dans un nouveau dossier `PROJECTS/<NomDuProjet>/`
- Conserver la structure :
  - `01_DEVELOPMENT`
  - `02_PREPRODUCTION`
  - `03_WORLD_BUILDING`
  - `04_CHARACTERS`
  - `05_ENVIRONMENTS`
  - `06_STORYBOARD`
  - `07_SHOTS`
  - `08_GENERATIONS`
  - `09_AUDIO`
  - `10_EDITING`
  - `11_POST`
  - `12_EXPORTS`
  - `13_ARCHIVE`

## 2. Remplir le brief de projet

- Ouvrir `PROJECTS/_PROJECT_TEMPLATE/brief_template.md`
- Copier le contenu dans `PROJECTS/<NomDuProjet>/01_DEVELOPMENT/brief.md`
- Compléter : concept, personnages, univers, identité visuelle, prompts IA, contraintes.

## 3. Utiliser la checklist de phase

- Copier `PROJECTS/_PROJECT_TEMPLATE/phase_checklist.md` dans votre projet : `PROJECTS/<NomDuProjet>/phase_checklist.md`
- Utiliser cette checklist pour valider chaque phase (Phase 0 à Phase 4).
- Cocher les éléments au fur et à mesure de votre progression.
- Archiver la checklist complétée dans `13_ARCHIVE/` à la fin du projet.

## 4. Connecter le brief au workflow

- Référez-vous à `HOME/agents_workflow.md` pour savoir quand et comment chaque agent utilise le brief.
- Utilisez la liste de phases pour positionner le brief dans la Phase 0.
- Comparez avec `PROJECTS/EXAMPLE_PROJECT/01_DEVELOPMENT/brief.md` pour voir un exemple de brief terminé.
- Enregistrez le brief initial dans `PROJECTS/<NomDuProjet>/13_ARCHIVE/`.

## 5. Lancer la phase 1

- Remplir `PROJECTS/<NomDuProjet>/02_PREPRODUCTION/scene_list.md`
- Ajouter un synopsis dans `PROJECTS/<NomDuProjet>/02_PREPRODUCTION/synopsis.md`
- Créer une carte émotionnelle dans `PROJECTS/<NomDuProjet>/01_DEVELOPMENT/emotion_map.md`

## 6. Passer aux phases suivantes

- Créer les environnements et personnages dans `03_WORLD_BUILDING`, `04_CHARACTERS`, `05_ENVIRONMENTS`
- Établir le storyboard et les plans dans `06_STORYBOARD` et `07_SHOTS`
- Préparer les prompts de génération dans `08_GENERATIONS/generation_prompts.md`
- Documenter l'audio dans `09_AUDIO/README.md`
- Organiser le montage dans `10_EDITING/README.md`
- Archiver les versions finales dans `13_ARCHIVE/`

## 7. Bonnes pratiques

- Documenter chaque décision dans Markdown.
- Poser des questions si un élément du brief est flou.
- Garder les prompts et versions d'assets dans l'archive.
- Suivre le workflow par phase de `HOME/agents_workflow.md`.
- Utiliser la `phase_checklist.md` pour valider chaque phase avant de progresser.
