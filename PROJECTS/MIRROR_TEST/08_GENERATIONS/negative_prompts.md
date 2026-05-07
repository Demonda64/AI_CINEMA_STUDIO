# Prompts négatifs et contraintes - Phase 3

Ces contraintes doivent être appliquées à toutes les générations visuelles de "Mirror".

## Prompt négatif global

`explicit monster, creature, demon, zombie, ghost sheet, gore, blood, wounds, mutilation, exaggerated facial distortion, cartoon face, fantasy horror, gothic castle, haunted mansion, neon lighting, saturated colors, red dominant lighting, dramatic lightning, jump scare, open mouth scream, weapon, violence, text errors, unreadable text, extra fingers, deformed hands, duplicated limbs, warped body, plastic skin, beauty lighting, glossy commercial look, overdesigned bedroom, cluttered room, cinematic action scene`

## Contraintes de cohérence

### Personnage
- Même homme sur tous les plans.
- 25-35 ans.
- Fatigué, cernes visibles.
- Pyjama ou vêtements de nuit sombres simples.
- Expressions retenues : agacement, confusion, anxiété, horreur silencieuse.
- Pas de cri ouvert sauf si explicitement demandé plus tard.

### Décor
- Chambre minimaliste.
- Miroir mural assez grand.
- Réveil digital sur table de nuit.
- Téléphone visible ou proche selon la scène.
- Pas d'objets décoratifs trop nombreux.

### Couleur et lumière
- Palette bleu-gris désaturée.
- Lumière motivée par réveil, téléphone, lampe faible ou salle de bain.
- Rouge uniquement pour le réveil, discret.
- Éviter les couleurs saturées.

### Reflet
- Présence humaine ou quasi humaine.
- Anomalie subtile.
- Pas de monstre.
- Pas de visage grotesque.
- Pas d'effet surnaturel évident avant la Scène 4.

### Texte à l'écran
- Réveil : `3:17`.
- Message : `Tu aurais dû le laisser branché.`
- Si le modèle déforme le texte, générer une version sans texte puis ajouter le texte en post-production.

## Critères de rejet

Une génération doit être rejetée si :
- Le message ou l'heure sont illisibles dans un plan où ils sont essentiels.
- La présence ressemble à un monstre explicite.
- Le décor devient gothique, fantastique ou trop chargé.
- La palette devient chaude ou saturée.
- Le protagoniste change clairement d'âge, visage ou style.
- Le miroir révèle l'anomalie avant les plans prévus.
- Le plan ressemble à une affiche promotionnelle au lieu d'un photogramme de film.

