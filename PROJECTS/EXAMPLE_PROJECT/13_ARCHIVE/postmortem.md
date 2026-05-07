# Postmortem

## Résumé

Ce document résume les choix créatifs, les problèmes rencontrés et les leçons tirées du projet d'exemple "Dernier Passage".

## Décisions principales

- Le film se concentre sur un personnage solitaire dans une station de métro futuriste.
- La narration est intérieure, construite autour d'un message découvert et de souvenirs.
- L'esthétique visuelle privilégie le contraste froid/chaud et des plans intimistes.
- La palette sonore mise sur l'ambiance nocturne et les nappes synthétiques.

## Ce qui a bien fonctionné

- La structure du projet est claire et modulaire.
- Les fichiers de prompts permettent de guider la génération IA par scène.
- Le découpage en phases facilite l'implémentation du workflow.
- L'approche émotionnelle est cohérente avec le thème de rédemption.

## Ce qui peut être amélioré

- Ajouter des fiches de personnages plus détaillées (motivations, arcs, backstory).
- Créer des storyboards visuels ou des croquis pour les plans clés.
- Ajouter une feuille de route de génération avec des versions précises et des évaluations.
- Renforcer l'archive avec des exemples de sorties de chaque itération.

## Leçons apprises

- Un projet IA de film doit combiner narrative, émotion et style dès les premières phases.
- Les prompts sont plus efficaces lorsqu'ils sont très structurés et spécifiques.
- L'archivage doit inclure non seulement les livrables finaux, mais aussi les décisions et les tests intermédiaires.

## Recommandations pour la suite

- Utiliser `HOME/agents_workflow.md` comme cadre d'orchestration pour tous les projets.
- Ajouter des fichiers de test de prompt dans `08_GENERATIONS`.
- Documenter les versions d'assets dans `13_ARCHIVE` avec des références claires.
- Développer un modèle de brief standardisé pour le début de chaque projet.
