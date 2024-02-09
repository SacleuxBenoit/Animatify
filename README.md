# Animatify

Animatify est une bibliothèque CSS légère et modulaire pour créer des animations fluides et personnalisables.

## Classes d'utilitaires d'animation

- `.animate`: Classe de base pour les animations. Définit une durée d'animation de 1s et remplit les deux états de l'animation.

## Classes de fonctions de temporisation

- `.easeIn`: Définit la fonction de temporisation de l'animation à `ease-in`.
- `.easeOut`: Définit la fonction de temporisation de l'animation à `ease-out`.
- `.easeInOut`: Définit la fonction de temporisation de l'animation à `ease-in-out`.
- `.ease`: Définit la fonction de temporisation de l'animation à `ease`.

## Classes d'itération d'animation

- `.animate--iteration-1` à `.animate--iteration-10`: Contrôle le nombre de fois qu'une animation est répétée.
- `.animate--infinite`: Fait en sorte que l'animation se répète indéfiniment.

## Classes de délai d'animation

- `.animate--delay-1s` à `.animate--delay-8s`: Définit le délai avant le début de l'animation.

## Classes de durée d'animation

- `.animate--duration-01s` à `.animate--duration-09s` 
et `.animate--duration-1s` à `.animate--duration-5s`: Définit la durée de l'animation.

## Animations

- `.rotate`: Fait tourner un élément de 0 à 360 degrés.
- `.bounce`: Fait rebondir un élément de 0 à -10px en hauteur.
- `.blink`: Fait clignoter un élément en passant de l'opacité 1 à 0.
- `.slideRight`: Fait glisser un élément de gauche à droite.
- `.slideLeft`: Fait glisser un élément de droite à gauche.

## Utilisation

Pour utiliser une animation, ajoutez simplement la classe `.animate` à votre élément HTML, ainsi que toute autre classe pour personnaliser l'animation.

```html
<div class="animate easeIn animate--iteration-3 animate--delay-2s animate--duration-1s">
    Hello World
</div>