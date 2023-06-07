# TPI Eval

## Description

Version 2 
TPI Eval est une page HTML simple, sans dépendances externes, qui permet de remplir la grille d'évaluation des TPI (travail pratique individuel).

## Motivation

La motivation derrière la création de TPI Eval est de surmonter les limitations du document PDF fourni sur tpivd.ch. La taille du champ de "justification" dans le PDF est souvent limitée. De plus, passer constamment du document détaillé des critères d'évaluation à la grille d'évaluation elle-même peut être fastidieux.

## Comment l'utiliser

1. Ouvrez la page HTML dans votre navigateur web préféré.
2. Appuyez sur `Shift+F1` pour accéder à la section d'aide.
3. La sauvegarde des évaluations dans des fichiers `evalx.js` n'est plus nécessaire. Les évaluations sont désormais stockées dans une base de données NoSQL appelée "DBevals".
4. Au démarrage de la page, un système de popups s'affiche et vous propose différentes options : Importation des anciens fichiers "evalx.js" pour la rétrocompatibilité. Ces fichiers seront hargés dans la base de données DBevals.
5. La page affiche une liste de boutons correspondant aux évaluations disponibles dans la base de données. Cliquez sur un bouton pour charger une évaluation spécifique.
6. Remplissez les champs de l'évaluation chargée. Les champs de justification sont extensibles.
7. Lorsque vous avez terminé, cliquez sur le bouton "Finaliser" pour enregistrer l'évaluation dans la base de données. Un fichier "Eval TPI - <candidat>.js" sera téléchargé, mais il ne sera plus nécessaire pour le fonctionnement de l'application.
8. Vous pouvez également charger une nouvelle évaluation à partir de la liste des boutons ou commencer une nouvelle évaluation vide.
9. Utilisez le bouton "Options" pour accéder à différentes fonctionnalités supplémentaires :
   - "Supprimer tout" : Supprime toutes les évaluations de la base de données.
   - "Charger la base de données" : Charge toutes les évaluations de la base de données et met à jour la liste des boutons.
  
10. Pour imprimer une évaluation au format "evalx.js", vous pouvez toujours utiliser l'option de téléchargement fournie.

Veuillez noter que l'enregistrement des évaluations se fait automatiquement dans la base de données et qu'il n'est plus nécessaire de manipuler manuellement les fichiers `evalx.js`. De plus, une fenêtre contextuelle s'affiche pour confirmer l'importation d'une évaluation précédemment enregistrée.

## Licence

TPI Eval est un logiciel open source sous licence [MIT License](https://opensource.org/licenses/MIT).
