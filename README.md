# TPI Eval

Une page HTML sans dépendance externe qui permet de remplir la grille d'évaluation des TPI

### Pourquoi ?

- Parce que je me suis souvent trouvé limité par la taille du champ 'justification' du PDF fourni sur [tpivd.ch](https://www.tpivd.ch/index.php/documentation-tpi-cfc-ordo-2014/pour-entreprise-formatrice?start=4)
- Parce que bien que le document des critères d'évaluation soit très détaillé, je trouve pénible de devoir sans cesse jongler entre ce document et la grille elle-même

### Et donc ?

- Tu ouvres cette page html dans ton navigateur préféré
  - S'il y a un fichier 'eval.js' dans le dossier, il est automatiquement rechargé
  - Sinon tu as une grille vierge 
- Tu remplis les champs grisés (les champs de justification sont extensibles)
- Tu enregistre un état intermédiaire avec le bouton 'Enregistrer'. Cela a pour effet de télécharger un fichier 'Eval TPI \<candidat>.js'
- Pour reprendre une grille en cours, tu dois déplacer ce fichier dans le répertoire où se trouve le html et le renommer 'eval.js'
- Quand c'est fini, tu cliques 'finaliser', ça sauve la feuille une dernière fois et la met en lecture seule
- Tu l'imprimes
