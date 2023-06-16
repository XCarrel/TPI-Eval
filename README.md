# TPI Eval

Une page HTML sans dépendances externes qui permet de remplir la grille d'évaluation des TPI

### Pourquoi ?

- Parce que je me suis souvent trouvé limité par la taille du champ 'justification' du PDF fourni sur [tpivd.ch](https://www.tpivd.ch/index.php/documentation-tpi-cfc-ordo-2014/pour-entreprise-formatrice?start=4)
- Parce que bien que le document des critères d'évaluation soit très détaillé, je trouve pénible de devoir sans cesse jongler entre ce document et la grille elle-même

### Et donc ?

- Tu ouvres cette page html dans ton navigateur préféré
  - Tape shift-F1 pour avoir de l'aide
  - S'il y a un ou plusieurs fichiers 'eval*.js' dans le dossier, tu peux en recharger un grâce à la dropdown list
  - Sinon tu peux partir sur une grille vierge
- Tu remplis les champs grisés (les champs de justification sont extensibles)
- Quand tu as un doute, tu cliques sur le numéro du critère ou tu presse shift-F1, et ... zbang!
- Tu enregistre un état intermédiaire avec le bouton 'Enregistrer'. Cela a pour effet de télécharger un fichier 'eval\<x>.js'. **Déplace ce fichier dans le dossier de TPI-Eval (remplace l'existant)**
- Quand c'est fini, tu cliques 'finaliser', ça télécharge un ficher 'Eval TPI - \<candidat>.js et la met en lecture seule.
- Tu l'imprimes depuis le navigateur

## Astuces

### Désactiver le message d’avertissement au téléchargement sur M$Edge
Lancer [ce script](edgeAllowJs.reg)
