# Matrix Rain Effect

Ce projet est une implémentation simple de l'effet de pluie typique du film "Matrix" utilisant HTML, CSS et JavaScript pur. Il utilise des caractères aléatoires tombant pour simuler l'effet et a un fond noir, tout comme l'effet original du film.

## Fonctionnalités

- Utilise la police `Matrix` pour un rendu authentique.
- Prend en charge la plupart des navigateurs modernes grâce à l'élément canvas.
- Les caractères tombent de manière aléatoire pour un effet dynamique.

## Aperçu

![Rendu de la page](./myMatrix-complet.GIF)


## Prérequis

Assurez-vous d'avoir le fichier de police `mtx.ttf` dans le même dossier que votre fichier HTML pour que l'effet de police Matrix fonctionne correctement.

## Comment l'utiliser ?

Il vous suffit d'ouvrir le fichier HTML dans un navigateur moderne pour voir l'effet de pluie Matrix en action.

## Explication du code

Le code utilise deux éléments `<canvas>` pour dessiner les caractères. Le premier dessine les caractères principaux et le second sert à ajouter un effet de brillance.

Le JavaScript gère la création et l'animation des caractères tombant. Il commence par initialiser les caractères, puis les anime pour qu'ils tombent à des vitesses aléatoires.

## Auteurs
  
Librement inspiré du travail de Riaz LASKAR [voir ici](https://codepen.io/riazxrazor/pen/Gjomdp)  
  
Paul WOISARD  
  