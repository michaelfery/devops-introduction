# devops-introduction

Séminaire d'acculturation DevOps

## Slides Deck

Pour récupérer le deck de slides, récupérez [le dernier package de release](/releases).

## Présentation Marp

Pour utiliser les slides de la formation vous aurez besoin d'utiliser [Marp](https://marpit.marp.app/).
L'extension VS Code vous sera normalement proposée automatiquement.

En ouvrant la fenêtre de Preview du fichier markdown, vous pourrez visualiser un pré-rendu.

Pour générer les slides au format pdf, ppt ou même générer l'image de la page de titre, vous pouvez utiliser les commandes suivantes:

```bash
npm run-script og-image
npm run-script pdf
npm run-script pptx
```

A chaque commit une release sera créée avec le deck de slides aux format pdf et pptx en utilisant Github Actions.
