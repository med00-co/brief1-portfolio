# Modèle de départ — Brief 1 (Sprint 1) — notes pour le formateur

## Contenu du dossier

- `site/` : le site d'une seule page à remettre aux apprenants (à publier dans un dépôt GitHub qu'ils pourront forker).
- `maquette/maquette-portfolio.svg` : la maquette de cette page, à importer dans Figma.
- `maquette/maquette-portfolio.png` : un aperçu de la maquette.

## Importer la maquette dans Figma

1. Créer un nouveau fichier de design dans Figma.
2. Glisser-déposer `maquette-portfolio.svg` sur le canevas (ou Fichier > Placer une image).
3. La page arrive sous forme de calques modifiables, regroupés par section : En-tête, Présentation, Compétences, Projets, Contact, Pied de page. Les textes restent des textes, en police Inter.
4. Partager le fichier en lecture : chaque apprenant le duplique dans son espace.

Largeur de la maquette : 1440 px. Contenu centré sur 1100 px.

## Ce que le modèle laisse volontairement à faire

| Dans le modèle | Tâche du brief |
| --- | --- |
| Contenu générique (« Prénom Nom », textes et images provisoires) | Modifier |
| Couleurs et police définies dans des variables CSS (`:root`) | Modifier la charte |
| 3 projets d'exemple | Passer à 4 cartes au minimum |
| Une seule page, menu en ancres (`#projets`, `#contact`) | Séparer en 3 pages |
| Projets empilés en une colonne, sans CSS Grid | Manipuler : passer en grille |
| Section Compétences sur la page unique | Manipuler : la déplacer vers À propos |
| Formulaire sans champ Sujet, e-mail en `type="text"`, aucun `required` | Manipuler : compléter le formulaire |
| Pas de page À propos | Créer |

Le modèle n'est pas responsive : c'est l'objet du Brief 2.
